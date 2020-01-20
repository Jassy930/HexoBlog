---
abbrlink: '0'
---
主页面标题：
post.swig  LINE36    
```
{{ next_url(post.path + 'index.html', post.title or __('post.untitled'), {class: 'post-title-link', itemprop: 'url'}) }}
```