
## Introduction



This repo is for deployment only. Click the following links to `Dev Repository` and `Demo Site`.

- [ ] [Dev Repository](https://github.com/esblog/esblog.github.io/tree/dev) 
- [x] [Deployed Site](https://github.com/esblog/esblog.github.io/)  deployed by Hexo from `Dev Repository`
- [ ] [Demo Site](http://blog.eson.org) host the `Deployed Repository` 



e.g
You can edit the README file in [Dev Repo](https://github.com/esblog/esblog.github.io/tree/dev/source/README.md)

## Hexo Render

该文件未被render，但是能够被页面访问。

This file is not rendered by Hexo, in order to be readable in github markdown.

It can be accessible in `Web Site` by absolute path.


```yml
# _.yml  site_configuration
skip_render:
  - "**/README.md"
  - "*/README.md"
```
