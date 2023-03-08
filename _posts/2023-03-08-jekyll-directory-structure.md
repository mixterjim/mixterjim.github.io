---
title: Jekyll 目录结构
date: 2023-03-08 20:00:00 +0800
categories: [Blogging, Tutorial]
tags: [jekyll]
---
| 文件夹        | 文件                                                   | 描述                   |
|---------------------|:---------------------------------|:-----------|
| _config.yml   |                                                        | 配置文件               |
| _data         |                                                        | 数据文件，会被全局加载 |
|               | members.yml                                            |                        |
| _drafts       |                                                        | 草稿文件，不需要日期   |
|               | begin-with-the-crazy-ideas.md                          |                        |
|               | on-simplicity-in-technology.md                         |                        |
| _includes     |                                                        | 重复使用的布局         |
|               | footer.html                                            |                        |
|               | header.html                                            |                        |
| _layouts      |                                                        | 页面模板               |
|               | default.html                                           |                        |
|               | post.html                                              |                        |
| _posts        |                                                        | 文章                   |
|               | 2007-10-29-why-every-programmer-should-play-nethack.md |                        |
|               | 2009-04-26-barcamp-boston-4-roundup.md                 |                        |
| _sass         |                                                        |                        |
|               | _base.scss                                             |                        |
|               | _layout.scss                                           |                        |
| _site         |                                                        | 静态网页               |
| .jekyll-cache |                                                        | 缓存                   |
| index.html    |                                                        | 可以使用md文件         |


