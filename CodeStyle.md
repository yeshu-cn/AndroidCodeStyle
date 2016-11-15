# Android命名规范

## 包命名
业务模块和代码模块相互结合的划分包的结构，业务模块优先级高

>
* com.xx.activities
* com.xx.base
* com.xx.adapter
* com.xx.tools
* com.xx.bean
* com.xx.db
* com.xx.view
* com.xx.service
* com.xx.broadcast
* com.xx.net

## Java类命名
描述+类型

> 类型
> 
* XXActivity
* XXService
* XXReceiver
* XXProvider
* XXFragment
* XXDialog
* XXAdapter
* XXUtils
* XXManager
* BaseXX


## Layout文件命名
>
* activity_xx.xml
* fragment_xx.xml
* dialog_xx.xml
* item_xx.xml

## ID命名

1. 类型\_模块_描述（layout文件内模块，不是指app级别的模块，因为layout文件已经能区分所在模块）
2. 类型_描述 （layout文件很简单的情况）
3. 描述 （layout文件很简单的情况）


> 类型
> 
* (TextView) text_  
* (ImageView) image_
* (Button) btn_
* (Menu) menu_


## Drawable资源命名

类型\_描述_[状态].png

>类型
>
* ic_xx.png
* menu_xx.png
* btn_xx.png
* divider_xx.png
* tab_xx.png
* background_xx.png

>状态
>
* xx_normal.png
* xx_pressed.png
* xx_focused.png
* xx_disabled.png
* xx_selected.png



## String资源命名

模块_描述
> 例如
> 
* registration\_email_hint  
* registration\_name_hint

如果不属于任何模块
>
* error_xx
* msg_xx
* title_xx
* action_xx

## Color资源命名

根据主题来命名颜色，参考https://www.materialpalette.com/cyan/red

	<color name="colorPrimary">#198cf4</color>
    <color name="colorPrimaryDark">#303F9F</color>
    <color name="colorPrimaryLight">#3F51B5</color>
    <color name="colorTextIcons">#3F51B5</color>
    <color name="colorAccent">#007aeb</color>
    <color name="colorTextAccent">#007aeb</color>
    <color name="colorPrimaryText">#DD000000</color>
    <color name="colorSecondaryText">#89000000</color>
    <color name="colorDivider">#ebebeb</color>


## Class member ordering

1. Constants
2. Fileds
3. Constructors
4. Override methods and callbacks
5. Public methods
6. Private methods
7. Inner classes or interfaces


## 参考
* http://android.jobbole.com/83659/
* https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md
