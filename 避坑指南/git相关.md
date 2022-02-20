配置vscode项目和git交互
    1.去https://git-scm.com/download/win 下载git
    2.新建一个文件夹，shift+鼠标右键，选择git bash here ,输入git clone %项目地址%.git 拉取项目(拉去远端空仓库，再将已有项目复制过来，可将已有项目与远端关联)
    3.vs装git blame插件，在插件拓展设置找到并进入json文件,增加一行"git.path": "%你的Git路径%\\git.exe"你自己git路径
    4.然后就可以修改文件，提交、拉取了
    5.如果需要输入user name和user email，在项目文件夹右键，运行git bash在终端窗口运行命令：
        git config user.name "设置你的名字"
        git config user.email "这里面设置你的邮箱地址"

设置gitBash后无法测试游戏？
    设置默认配置文件为：powerShell

PR提交更改：
    改了代码后，源代码管理-提交-确认-同步，网页git-在自己fork的库pull requests-new pll-create pull

PULL同步远程库：
    源代码管理-更多操作-拉取/推送-拉取自-上流

可以上传小文件，可以提交，但无法上传整个项目？
    可能是免费版单个文件大小超过上限，整个项目大小超过上限，缩小文件大小/只传代码
