Material Design 中文协同翻译
=============================================

Google I/O 2014发布的Material Design将会成为统一Android，Chrome等平台的设计语言规范，对Android从业人员意义重大，我们一帮不知天高地厚的人正通过互联网的方式将其翻译成中文~

我们欢迎每一个人参与进来~~

#一起来参与
如果想做出贡献(翻译或者校对)的话，请加QQ群：137198122，谢谢！

原文文档：
http://www.google.com/design/spec/material-design/introduction.html

# 参与步骤（页尾有详细的过程演示）
* fork主仓库（https://github.com/1sters/material_design_zh）
* 按照章节（页面）认领翻译(每次申请一个章节)，在下面这个`README.md`里找还没有被人申请的章节，写上（@你的github号），给主仓库的`develop`分支提pull request；
* 提的pull request 被确认，合并到主仓库后，代表你申请的章节*占位*完成，开始翻译；
* 翻译过程请参 *翻译协作规范* ，完成翻译后提交pull request给主仓库的`develop`分支；
* 校核完成后，从主仓库的`develop`分支合并到主`master`分支；
* 全部翻译完成后，生成PDF文档和网页发布；

# 翻译协作规范
为了让大家协作顺畅，需要每一个人遵循如下协作规范~

- 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
- 翻译后的文档请放到SOURCE文件夹下的对应章节中，然后pull request即可，我会用gitbook编译成网页
- 工作分支为`develop`，用于GitHub的pages服务
- fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到`develop`分支中
- 有其他任何问题都欢迎发issue，我们看到了会尽快回复


如果不熟悉的Markdown的，请参考

- https://help.github.com/articles/markdown-basics
- https://help.github.com/articles/github-flavored-markdown
# 目录

* Material Design 
  * [Introduction](http://www.google.com/design/spec/material-design/introduction.html)  by [iceskysl](https://github.com/iceskysl) at 2014.6.26
* Animation
  * [Authentic Motion](http://www.google.com/design/spec/animation/authentic-motion.html) by [zhenbeiju](https://github.com/zhenbeiju) at 2014.6.26
  * [Responsive Interaction](http://www.google.com/design/spec/animation/responsive-interaction.html)
  * [Meaningful Transitions](http://www.google.com/design/spec/animation/meaningful-transitions.html)
  * [Delightful Details](http://www.google.com/design/spec/animation/delightful-details.html)
* Style
  * [Color](http://www.google.com/design/spec/style/color.html)
  * [Typography](http://www.google.com/design/spec/style/typography.html)
  * [Icons](http://www.google.com/design/spec/style/icons.html)
  * [Imagery](http://www.google.com/design/spec/style/imagery.html)
* Layout
  * [Principles](http://www.google.com/design/spec/layout/layout-principles.html)
  * [Metrics and Keylines](http://www.google.com/design/spec/layout/metrics-and-keylines.html)
  * [Structure](http://www.google.com/design/spec/layout/structure.html)
* Components
  * [Bottom Sheets](http://www.google.com/design/spec/components/bottom-sheets.html)
  * [Buttons](http://www.google.com/design/spec/components/buttons.html)
  * [Cards](http://www.google.com/design/spec/components/cards.html)
  * [Chips](http://www.google.com/design/spec/components/chips-tokens.html)
  * [Dialogs](http://www.google.com/design/spec/components/dialogs.html)
  * [Dividers](http://www.google.com/design/spec/components/dividers.html)
  * [Grids](http://www.google.com/design/spec/components/grids.html)
  * [Lists](http://www.google.com/design/spec/components/lists.html)
  * [List controls](http://www.google.com/design/spec/components/list-controls.html)
  * [Menus](http://www.google.com/design/spec/components/menus.html)
  * [Progress and Activity](http://www.google.com/design/spec/components/progress-activity.html)
  * [Sliders](http://www.google.com/design/spec/components/sliders.html)
  * [Snackbars and Toasts](http://www.google.com/design/spec/components/snackbars-and-toasts.html)
  * [Subheaders](http://www.google.com/design/spec/components/subheaders.html)
  * [Switches](http://www.google.com/design/spec/components/switches.html)
  * [Tabs](http://www.google.com/design/spec/components/tabs.html)
  * [Text fields](http://www.google.com/design/spec/components/text-fields.html)
  * [Tooltips](http://www.google.com/design/spec/components/tooltips.html)
* Patterns
  * [Selection](http://www.google.com/design/spec/patterns/selection.html)
  * [Gestures](http://www.google.com/design/spec/patterns/gestures.html)
  * [Promoted Actions](http://www.google.com/design/spec/patterns/promoted-actions.html)
  * [Settings](http://www.google.com/design/spec/patterns/settings.html)
  * [Imagery Treatment](http://www.google.com/design/spec/patterns/imagery-treatment.html)
  * [Search](http://www.google.com/design/spec/patterns/search.html)
* Usability
  * [Accessibility](http://www.google.com/design/spec/usability/accessibility.html)
* Resources
  * [Layout Templates](http://www.google.com/design/spec/resources/layout-templates.html)
  * [Sticker Sheets](http://www.google.com/design/spec/resources/sticker-sheets.html)
  * [Roboto Font](http://www.google.com/design/spec/resources/roboto-font.html)
  * [Color Palettes](http://www.google.com/design/spec/resources/color-palettes.html)


#协作过程演示

## fork主仓库
打开https://github.com/1sters/material_design_zh ，fork一份自己的仓库；

## 初始化本地仓库

```sh
iceskysls-MacBook-Pro:1sters iceskysl$ git clone git@github.com:IceskYsl/material_design_zh.git
Cloning into 'material_design_zh'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0)
Receiving objects: 100% (3/3), done.
Checking connectivity... done.
iceskysls-MacBook-Pro:1sters iceskysl$ cd material_design_zh
```
## 创建并切换工作分支

```sh
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git branch develop
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git checkout develop
Switched to branch 'develop'
```
## 添加远程主仓库

```sh
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git remote add upstream https://github.com/1sters/material_design_zh.git
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git remote -v
origin	git@github.com:IceskYsl/material_design_zh.git (fetch)
origin	git@github.com:IceskYsl/material_design_zh.git (push)
upstream	https://github.com/1sters/material_design_zh.git (fetch)
upstream	https://github.com/1sters/material_design_zh.git (push)
```
## 和远程主仓库保持更新

```sh
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git fetch upstream
remote: Counting objects: 43, done.
remote: Compressing objects: 100% (33/33), done.
remote: Total 41 (delta 12), reused 32 (delta 3)
Unpacking objects: 100% (41/41), done.
From https://github.com/1sters/material_design_zh
 * [new branch]      develop        -> upstream/develop
 * [new branch]      master     -> upstream/master
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git merge upstream/ing
Updating 6899552..ea46595
Fast-forward
 README.md         | 115 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-----------------------------------------------
 SOURCE/SUMMARY.md |  51 +++++++++++++++++++++++++++++++++++++++++++++++++++
 2 files changed, 119 insertions(+), 47 deletions(-)
 create mode 100644 SOURCE/SUMMARY.md
```

## 推送本地修改到自己的远端仓库

```sh
 iceskysls-MacBook-Pro:material_design_zh iceskysl$ git st
 On branch ing
 Changes not staged for commit:
   (use "git add <file>..." to update what will be committed)
   (use "git checkout -- <file>..." to discard changes in working directory)

 	modified:   README.md

 no changes added to commit (use "git add" and/or "git commit -a")

iceskysls-MacBook-Pro:material_design_zh iceskysl$ git add .
iceskysls-MacBook-Pro:material_design_zh iceskysl$ git commit -m "完成规范编写"

iceskysls-MacBook-Pro:material_design_zh iceskysl$ git push origin ing
Counting objects: 46, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (39/39), done.
Writing objects: 100% (44/44), 7.50 KiB | 0 bytes/s, done.
Total 44 (delta 13), reused 0 (delta 0)
To git@github.com:IceskYsl/material_design_zh.git
 * [new branch]      develop -> develop
```

## 发Pull Request
 
 推送自己的远端仓库（develop分支)到主仓库（develop分支)