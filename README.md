# Ubuntu_Init
ubuntu 16.04 系统一键环境配置脚本

配置完毕的界面如所示:

[![9LX7y.md.png](https://s1.ax2x.com/2017/10/13/9LX7y.md.png)](https://simimg.com/i/9LX7y)

## 运行

在Ubuntu_Init目录，输入以下命令

`chmod u+x Linux_Init.sh`

然后运行脚本:

`./Linux_Init.sh`

- [x] 换USTC源
- [x] 更新系统软件
- [x] 更换目录为英文(若是中文目录的话)
- [x] 启动器移动到屏幕底部
- [x] 同步windows/Ubuntu双系统时间
- [x] 安装vim
- [x] 安装git
- [x] 安装openjdk8
- [x] 安装搜狗中文输入法
- [x] 删除Amazon的链接
- [x] 安装标题栏网速监控软件

## Sogou Pinyin input method configuration

搜狗拼音输入法配置

点击右上角输入法，搜狗拼音->设置->高级->打开Fcitx设置，如下图所示：

[![9L5Fe.md.png](https://s1.ax2x.com/2017/10/13/9L5Fe.md.png)](https://simimg.com/i/9L5Fe)

Fcitx配置如下图所示，如果没有"键盘-英语(美国)"，点击"+"号添加即可.

[![9L9ud.md.png](https://s1.ax2x.com/2017/10/13/9L9ud.md.png)](https://simimg.com/i/9L9ud)


## Title bar network speed monitoring software configuration

标题栏网速监控软件配置

点击右上角监控栏的Preferences按钮，在打开的设置面板里面按照如下设置：

[![9EqyO.md.png](https://s1.ax2x.com/2017/10/13/9EqyO.md.png)](https://simimg.com/i/9EqyO)

勾选"Run on startup",开机启动.

[![9Ewlq.md.png](https://s1.ax2x.com/2017/10/13/9Ewlq.md.png)](https://simimg.com/i/9Ewlq)

在"Customize output"栏添加"net:{net}"项，添加网速监控.

