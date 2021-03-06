----
- Name: bearychat
- Platform: iOS

----
# 3.11.6 / 2019-02-17
## Added
- 支持分享来自其他 App 的文件至 BearyChat

## Fixed
- 修复输入框中无法显示补全列表的 bug


# 3.11.5 / 2019-02-03
## Fixed
- 修复 token 过期的 bug
- 修复在 iPad 上设置手机消息崩溃的 bug
- 修复设置界面勾选状态缺失的 bug
- 修复重复显示恢复归档讨论组操作的 bug


# 3.11.3 / 2019-01-16
## Added
- 支持部分复制消息气泡的文字
- 增加更新日志入口
- 优化长文本消息作为文本片段发送
- 优化新消息通知推送

## Fixed
- 修复多选操作的 bug
- 修复 token 过期的 bug
- 修复其他问题


# 3.11.2 / 2018-12-10
## Added
- 新增网络诊断
- 新增帮助中心入口

## Fixed
- 优化部分页面的下拉刷新操作
- 修复某些情况下 App 卡死问题
- 修复 iOS 9 崩溃问题
- 部分 UI/UX 调整


# 3.11.1 / 2018-11-09
## Added
- 新增聊天界面返回按钮未读数字的展示
- 支持应用内切换语言
- 新增搜索历史展示

## Fixed
- 优化启动屏设计
- 优化页面内字体样式
- 修复音视频会议 bug

# 3.11.0 / 2018-10-23
## Added
- 新增设备管理，方便管理多设备登录
- 自定义字体大小覆盖全局
- 修改密码页面增加重置密码入口
- 扩大 Markdown 语法支持影响范围

## Fixed
- 优化消息菜单 UI
- 调整个人信息页面内容
- 完善会话列表没有最近会话时的占位图
- 统一成员列表排序规则
- 移除在线状态
- 修复 iOS 12 适配问题


# 3.10.5 / 2018-09-11
## Added
- 支持批量处理消息
- 支持调整消息字体大小
- 支持文件的浏览与上传

## Fixed
- 优化了一些界面的 UI 和交互
- 一些稳定性和性能的改进


# 3.10.4 / 2018-06-30
## Added
- 最近消息列表新增发送状态

## Fixed
- 统一讨论组操作权限
- 访客权限调整
- 优化了部分界面的 UI 和交互


# 3.10.3 / 2018-06-07
## Added
- 支持 LDAP/SAML 统一认证方式
## Fixed
- 优化部分界面 UI 和交互
- 稳定性和性能的改进


# 3.10.2 / 2018-05-21
## Fixed
- 修复通讯录界面样式问题
- 修复忘记域名找到团队的登录问题
- 优化了一些界面的 UI 和交互
- 稳定性和性能的改进

# 3.10.1 / 2018-05-14
## Added
- 新增私聊会话的已读未读状态显示
## Fixed
- 优化了一些界面的 UI 和交互
- 稳定性和性能的改进

# 3.10 / 2018-04-25
## Added
- 新增音视频会议
- 新增消息转发
- 新增离开状态
- 新增已注销成员、归档讨论组列表，支持团队成员查看和已注销成员、归档讨论组历史聊天记录
- 支持 Live Photo
- 优化了一些界面的 UI 和交互
- 一些稳定性和性能的改进

# 3.9.2 / 2018-03-03
## Added
- 新增备注名称功能
- 新增隐藏会话功能
- 新增转移讨论组管理员功能
- 优化了一些界面的 UI 和交互
- 一些稳定性和性能的改进

# 3.7 / 2017-07-31
## Added
- 首页搜索改版, 支持消息, 文件, 联系人和部门
- 支持 Spotlight
- 支持 SVG 和 WebP 格式图片
- 支持更多的 Reaction
- 部分交互和 UI 优化

## Fixed
- 修复 iPad 上的 Crash 问题

# 3.6.1 / 2017-06-27
## Fixed
- 修复删除最近消息列表时的 Crash 问题

# 3.6 / 2017-06-14
## Added
- 支持 Share Extension

## Fixed
- 修复某些页面有重复条目的问题

# 3.5 / 2017-05-31
## Added
- 支持在手机上新建及管理临时讨论组

## Fixed
- 完善讨论组相关的管理功能
- 修复最近消息列表可能的错乱问题

# 3.4 / 2017-05-24
## Added
- 支持组织架构 (只有在有组织架构之后才出现入口)

## Fixed
- 修复了一处可能连接失败的 Bug

# 3.3 / 2017-05-10
## Added
- 文件及网页预览支持 Handoff
- 引用/收藏/@你的消息支持跳转

## Fixed
- 优化聊天界面的性能

# 3.2 / 2017-04-20
## Added
- 支持预览以及在别的 App 用 BearyChat 打开文件
- 在手机上也能加入讨论组了

# 3.1 / 2017-03-30
## Added
- 支持多个团队之间切换

# 3.0 / 2017-03-24
我们用 Swift 3 重写了 iOS 客户端，在交互设计、网络连接等方面做了大量优化。
## Added
- 【讨论组状态显示】已置顶讨论组将始终固定在消息页上方，并增加讨论组提醒设置提示，向左滑动可快速修改讨论组提醒或静音相关设置。
- 【「提到我的」消息列表】消息页左上方新增查看所有「提到我的」消息入口，不再错过任何一条重要消息。
- 【自定义贴纸表情】新增自定义贴纸表情功能，支持在移动端上使用或收集自定义贴纸表情。
- 【表情回应】支持对消息进行表情回应，长按消息即出现表情回应入口。
- 【机器人概况】讨论组中新增已添加机器人列表，支持讨论组内搜索机器人或查看机器人概况。
- 【成员详情页内容】丰富了成员详情页的呈现内容，补全成员「身份」、「简介」等在移动端上的展示。
- 【快捷回复设置】个人设置面板中新增快捷回复设置，支持在「通知」选项下启用表情或文字快捷回复。
## Fixed
- 【连接及推送】优化网络连接及消息推送模块，使用体验更加流畅，消息提醒及时送达。
- 【联系人查看方式】优化通讯录页面呈现方式，讨论组及成员列表支持快速切换，支持关键字搜索，定位更加精准。
- 【文件查看页面】调整文件查看页面结构，筛选条件更加清晰，轻松回顾历史文件。

# 2.8 / 2017-01-20
## Fixed
- 修复 BUG，替换倍恰新标识

# 2.7 / 2016-07-25
## Added
- 支持从 iCloud 上传文件

## Fixed
- 增加根据点击的 push 消息进入应用后自动切换到对应团队
- 修复消息流界面从后台回来可能闪退的问题
- 修复上传头像后头像地址还是以前地址的问题

# 2.6 / 2016-07-11
## Fixed
- 修复 iPhone 5/5s 下照片选择界面布局问题
- 修复最新消息列表双击 Tab 可能闪退的问题
- 修复从后台范围应用线程死锁导致数据无法加载的问题
