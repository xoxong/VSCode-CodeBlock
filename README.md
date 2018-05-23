# 目录
- [目录](#)
    - [vs-code-codeBlock](#vs-code-codeblock)
    - [html](#html)
            - [> 注释部分](#)
            - [> 代码块](#)
    - [css](#css)
            - [> css兼容样式](#css)
            - [> 手机rem扩展自适应代码块](#rem)
            - [> 头部预定义初始化样式](#)
            - [> 代码注释](#)
    - [javascript](#javascript)
            - [> 注释部分](#)
            - [> 兼容处理](#)
            - [> 常用代码模板](#)
            - [> 正则表达式 常用下拉](#)


## vs-code-codeBlock

> 文件下载直接覆盖vs的代码块目录:C:\Users\Administrator\AppData\Roaming\Code\User\snippets

> 目前有 js/css/html 代码块


> 方法指令大全(直接在文件内输入指令即可 trigger为指令)
> 
> (不支持中文指令，只是参考)

## html

#### > 注释部分
- - -
snippet | trigger | readme
-|-|-
1.notes_form | notes_form ; nf | #注释：表单注释
2.notes_modu_name | notes-modular-name ; nmn | #注释：模块注释 简化版 名字
3.notes_modu | notes_modular ; nm | #注释：模块注释 类型 功能 介绍 
4.notes_company | notes_company ; nc | #公司注释 署名 作者 时间  简介 备注  
5.notes_company | notes_import ; nimport | #javascript css 版本注释 类型 介绍  

#### > 代码块 
- - -
snippet | trigger | readme
-|-|-
1.code_meta_iphone | code_meta_iphone ; cmetai | #手机meta声明 类
2.code_a_windowOpen | code_a_window_open ; cawo | #常用a标签点击跳转js
3.code_button_formsubmit | code_button_formsubmit ; formsubmit ; submit | #表单常用按钮submit
4.code_form | code_form ; cform | #常用基础表达配置
5.code_pc_background | code_pc_background ; code_pcbackground ; cpcback | #常用PC 居中背景模板

## css

#### > css兼容样式
- - - 
snippet | trigger | readme
-|-|-
1.-IE-filter- | iefilter ; filter | #IE透明度兼容css
2.code_transition | code_transition ; ctransition | #过度效果 transition 兼容
3.code_transform | code_transform ; ctransform | #变形属性 transform 放大缩小 兼容
 
#### > 手机rem扩展自适应代码块
- - - 
snippet | trigger | readme
-|-|-
1.code_iphone_rem750px | code_iphone_rem750px ; cirem750 | #手机rem扩展自适应代码块750
2.code_iphone_rem640px | code_iphone_rem640px ; cirem640 | #手机rem扩展自适应代码块640

#### > 头部预定义初始化样式
- - - 
snippet | trigger | readme
-|-|-
1.code_initialization | code_initialization ; cinitialization | #头部预定义初始化样式

#### > 代码注释
- - - 
snippet | trigger | readme
-|-|-
1.notes_modu_name | notes_modular_name ; nmn| #注释：模块注释 简化版 名字
2.notes_modu | notes_modular ; nm| #注释：模块注释 类型 功能 介绍

## javascript

#### > 注释部分
- - - 
snippet | trigger | readme
-|-|-
1.notes_code | notes_code ; nmn | #不带参代码块介绍
2.notes_code_parameter | notes_modular ; nm | #带参代码块介绍

#### > 兼容处理
- - - 
snippet | trigger | readme
-|-|-
1.$.ie_version | $code_ieversion ; $ieversion ; $ie | #IE兼容相关
2.$.PC/iPhone/Android | $code_pc ; $pciphone ; $pcandroid | #判断是手机还是pc

#### > 常用代码模板
- - - 
snippet | trigger | readme
-|-|-
1.$.scrolltop | $code_scrolltop ; $scrolltop  | #动画跳转到顶部
2.$.fontCarousel | $code_fontCarousel ; $fontCarousel | #字体轮播上下滚动
3.$.formPost | $code_formpost ; $formpost | #表单提交默认模板 获取 判断 提交 返回
4.$.timedifference | $timedifference | #时间差改变数据
5.$.dynamicInfo | $code_info ; $info | #动态添加客户信息
6.$.MouseMovement | $code_mousemovement ; $cmm | #跟随鼠标移动

#### > 正则表达式 常用下拉
- - - 
snippet | trigger | readme
-|-|-
1.$.RegExp_s | $regexp ; $re | #常用正则表达式集锦

code | readme
-|-
1./^0?1[3\|4\|5\|8\|7][0-9]\d{8}$/ | #公司常用手机验证
2./^1[3\|4\|5\|8\|7][0-9]\d{8}$/ | #手机验证



