#### update
简单改造，适配公司内部的gitlab，方便自己使用，欢迎继续改造

> 改造后的文件在`release/v10.x`，欢迎下载使用

##### 改造点
- 头部导航调整修复，可以跳转`namespace`和`project`
- 非权限项目的`path_with_namespace`获取失败问题修复
- 非权限项目首次进入时`file-title-name`获取失败问题修复，并添加当前文件跳转
- `toggle`热键改为`Esc`

##### 版本说明（改造后的版本从`10`开始）
- 10.0 修复上面列举的改造点
- 10.1 添加进入项目则展示project tree

##### @TODO 待改造点
- [x] 进入项目则展示tree
- [ ] 当前文件的commit信息没及时更新

## gitlab-tree  <img src="http://images2015.cnblogs.com/blog/282019/201511/282019-20151106105737086-1425638412.png" alt="gitlab tree logo" width="10%" height="10%"/>

Chrome extension to display Gitlab code in tree format. Useful for developers who frequently read source in Gitlab and do not want to download or checkout too many repositories. The first gitlab assistant tool for code browsing.

### features

* support all the enterprise intranet gitlab service
* Easy-to-navigate code tree like web IDEs, simple and non-invasive
* ~~Fast browsing with pjax~~
* UI looks like Gitlab default UI
* hotkey support( hit <kbd>[</kbd> to toggle gitlab-tree sidebar )
* support gitlab 9.x version( 8.x user use v1.5) :collision: :sparkles:
* no page refresh when browsing code file

### usage

1. install gitlab-tree
2. open a gitlab file url then you'll find a tree panel in the left of chrome window, OR just simple locate to Repository -> Files Tab.
3. still not work?  please feel free to let me know.

### screenshot

![](./docs/snapshot-gitlab9.gif)

![](./docs/gitlab-tree.png)


<center>code with :heart: by FrankFan</center>
