+++
title = 'Hello World'
date = 2024-07-15T12:29:40+08:00
draft = true
+++
## 添加内容

添加新页面

```yaml
hugo new content content/posts/my-first-post.md
```

标题title不能使用空格否则会报错

```yaml
Error: failed to resolve "content/posts/HUGO" to an archetype template
PS D:\HUGO\ChanceApp> hugo new content content/posts/HUGO-编写文章.md
```

保存草稿内容不能使用hugo server,应该使用

```yaml
hugo server --buildDrafts
hugo server -D
```

