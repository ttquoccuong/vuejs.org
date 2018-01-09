---
title: Bản sao của HackerNews
type: examples
order: 12
---

> Đây là một bản sao của HackerNews được xây dựng dựa trên API từ Firebase, Vue 2.0 + Vue Router + Vuex, với server-side rendering.

{% raw %}
<div style="max-width: 600px;">
  <a href="https://github.com/vuejs/vue-hackernews-2.0" target="_blank">
    <img style="width: 100%;" src="/images/hn.png">
  </a>
</div>
{% endraw %}

> [Xem Demo](https://vue-hn.now.sh/)
> Lưu ý: Bản demo này có thể cần một ít thời gian để tải nếu không có ai truy cập nó trong một khoảng thời gian nhất định.
>
> [[Mã nguồn](https://github.com/vuejs/vue-hackernews-2.0)]

## Tính năng

- Server Side Rendering
  - Vue + Vue Router + Vuex làm việc cùng nhau
  - Lấy dữ liệu từ Server-side trước khi hiển thị
  - Client-side state & DOM hydration
- Single-file Vue Components
  - Hot-reload trong môi trường phát triển
  - CSS extraction for production
- Cập nhật danh sách tin trong thời gian thật với hiệu ứng lật (FLIP)

## Cấu trúc tổng quan

<img width="973" alt="Hackernew clone architecture overview" src="/images/hn-architecture.png">
