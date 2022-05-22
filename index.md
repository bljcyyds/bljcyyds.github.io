## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/bljcyyds/bljcyyds.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Project
bookshop: http://101.43.159.211:8084

### git tips
```markdown
#创建test，初始化git
- mkdir test
- cd test
- git init
- git status

#添加项目到本地仓库
- git add --all
- git status
- git commit -m "BookShop测试"

##添加到GitHub
- git remote add origin https://github.com/bljcyyds/test.git
- git push -u origin master

#重设ssl
- git remote set-url origin https://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@github.com/bljcyyds/test.git

#LibreSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443 
- networksetup -setv6off Wi-Fi

#在github里添加，直接 git pull
#在电脑上添加先git add . && git commit -m "push test" ，再push

#版本冲突
- git mergetool

- git clone https://github.com/Eins51/BookShop.git
- cd BookShop
- git status
- git add .
- git commit -m '解释'
- git push

#remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/Eins51/BookShop.git/'
- git remote set-url origin https://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@github.com/Eins51/BookShop.git
```

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bljcyyds/bljcyyds.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
