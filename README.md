## GF的个人主页 2025年6月20日开始，GF更新
## 删除某一板块
   1）如果不需要某个板块，需要删除
      a.可以直接删除 `contents` 文件夹下对应的 `.md` 文件。
      b.需要删除 index.html 文件中的对应内容。
      c.需要删除 scripts.js 文件中的对应内容。
      d.如果有图片，可以删除 `static/assets/img` 文件夹下对应的图片。
      e.如果有引用的其他文件，可以删除 `static/assets/files` 文件夹下对应的文件。
      f.如果有引用的其他网页，可以删除 `static/assets/links` 文件夹下对应的文件。
      g.如果有引用的其他网页的图片，可以删除 `static/assets/links` 文件夹下对应的图片。


## -----------------------------------------------------------------------------------------------------------------------------------

## 介绍 | Introduction

这是一个**通用的个人主页模板**，基于 [Sen Li 的学术主页模板](https://github.com/senli1073/senli1073.github.io) 进行修改。  


项目的目录结构如下 | The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) 修改各个板块的内容 | Modify the content of each section, which corresponds to `contents/*.md`.

(3) 调整网站设置 | Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) 替换图片 | Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) 提交更改 | Push it: 
```
git commit -am 'init'
git push
```

