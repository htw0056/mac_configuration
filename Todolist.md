# Mac环境配置Todolist

## 系统设置

* “通用”：边栏图标小

* “Dock”：大小最小，位于左边，最小化为应用图标

* “安全性与隐私”：允许任何来源应用，隐私-辅助功能-允许下面应用控制电脑

* “键盘”：将F1、F2等用作功能键

* “键盘”：配置物理键盘CMD与ALT互换。Capslock设置为无操作

* “键盘”：启用“快捷键-所有控制”

* "共享"：修改电脑名称

* "用户与群组"：关闭Guest用户，修改开机启动项

* “辅助功能”：“触控板选项”，启用拖移-三指拖移。

  ​

## 基础工具

* 安装[搜狗输入法](http://pinyin.sogou.com/mac/)

- 安装替代终端：[iTerms2](http://www.iterm2.com)
- 安装改键软件(系统10.11及以下)：[Seil](https://pqrs.org/osx/karabiner/seil.html.en)与[Karabiner](https://pqrs.org/osx/karabiner/)
  - 在“系统设置-键盘-修饰键”中将Capslock设置为“无操作”
  - 使用Seil将CapsLock的Keycode改为80
  - 替换Karabiner的[配置文件](https://github.com/htw0056/mac_configuration/blob/master/KarabinerConfiguration/private.xml)`private.xml`
- 安装改键软件(系统10.12以上)：[Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - 下载[caps_locl.json](https://github.com/htw0056/mac_configuration/blob/master/KarabinerConfiguration/caps_lock.json)
  - ` cp caps_lock.json .config/karabiner/assets/complex_modifications/caps_lock.json`
  - 如果有外接键盘，在Karabiner-Elements内设置外接键盘alt和command互换（目前Karabiner-Elements会覆盖系统默认配置）
- 安装窗口管理软件：[Moom](https://manytricks.com/moom/)
  - 激活，配置Moom的激活键为Hyper+A
  - 配置Tab和空格为全屏，方向键为`move to half`，回车为无动作。
- 安装文档阅读器：[Dash](https://kapeli.com)
  - 激活，下载`Python, Java, PostgreSQL`文档。




## 应用

* 编辑器：[VSCode](https://code.visualstudio.com)，[Typora](https://www.typora.io), [Sublime](https://www.sublimetext.com/)
* IM软件：[钉钉](https://www.dingtalk.com)
* 浏览器：[Google Chrome](http://www.google.cn/intl/zh-CN/chrome/browser/desktop/index.html)
* 解压软件：[Keka](http://www.kekaosx.com/en/)




## 开发环境

* IDE：[IntelliJ IDEA Ultimate](http://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/download/#section=mac), [eclipse](http://www.eclipse.org/downloads/eclipse-packages/)

* Anaconda安装至`~/anaconda`

* JDK安装至默认位置：[JDK Downloads](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

* [Maven](https://maven.apache.org/)安装到`/usr/local/maven`

* `Homebrew`： `https://brew.sh/`

* Git 安装

* Vim安装与配置：`brew install vim`

* 启用[Configuration](https://github.com/htw0056/mac_configuration/tree/master/configuration),配置个性化SHELL环境

  ```bash
  cd configuration
  ./setup
  ```

  ​

