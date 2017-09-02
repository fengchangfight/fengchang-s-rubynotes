### Install rvm
curl -L get.rvm.io | bash -s stable
running result: 
```
Installing RVM to /Users/xiefengchang/.rvm/
    Adding rvm PATH line to /Users/xiefengchang/.profile /Users/xiefengchang/.mkshrc /Users/xiefengchang/.bashrc /Users/xiefengchang/.zshrc.
    Adding rvm loading line to /Users/xiefengchang/.profile /Users/xiefengchang/.bash_profile /Users/xiefengchang/.zlogin.
Installation of RVM in /Users/xiefengchang/.rvm/ is almost complete:

  * To start using RVM you need to run `source /Users/xiefengchang/.rvm/scripts/rvm`
    in all your open shell windows, in rare cases you need to reopen all shell windows.

# xiefengchang,
#
#   Thank you for using RVM!
#   We sincerely hope that RVM helps to make your life easier and more enjoyable!!!
#
# ~Wayne, Michal & team.

In case of problems: https://rvm.io/help and https://twitter.com/rvm_io

  * WARNING: You have '~/.profile' file, you might want to load it,
    to do that add the following line to '/Users/xiefengchang/.bash_profile':

      source ~/.profile
```
查看rvm版本：
···
rvm -v
···
列出ruby可安装版本信息：
```
rvm list known
```
安装某版本ruby:
```
rvm install 2.1.4
```
使用该版本ruby作为默认版本：
```
rvm use 2.1.4 --default
```
查看已安装的ruby:
```
rvm list
```
卸载一个已安装的ruby版本：
```
rvm remove 2.1.4
```
查看已有gem源：
···
gem source
···

切换源
```
$ gem update --system
$ gem uninstall rubygems-update
$ gem sources -r http://rubygems.org/
$ gem sources -a http://ruby.taobao.org
```

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/fengchangfight/fengchang-s-rubynotes/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/fengchangfight/fengchang-s-rubynotes/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
