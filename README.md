# command_help  

    command help for zsh  命令行笔记   
>command_help_git.txt  git命令笔记   
command_help_screen.txt  screen相关命令笔记   
command_help_pod.txt   ios 开发pod 命令笔记   
command_help_protobuf.txt  谷歌protobuf相关命令笔记   
command_help_python.txt   python 相关命令笔记

# start  
 
**1**.首先把command_help 库克隆到本地一个目录下  
**2**.mac 自带zsh 命令行，其他系统请自行搜索如何安装zsh  
**3**.在终端中输入 **vim ~/.zshrc** 打开zsh的配置文件  
**4**.找到“#aliases” 这一行 配置命令行别名，更多别名参考zshAliases.txt 文件

**注意**：必须根据自己的command_help 库文件路径自定义配置
配置如下别名：  
  
>alias zshconfig="vim  ~/.zshrc"   
alias command_help='cd command_help文件夹的路劲'           
alias command_help_git='vim command_help_git.txt文件的路径'  
alias command_help_screen='vim command_help_screen.txt文件的路径'  
alias command_help_pod='vim command_help_pod.txt文件的路径'  
alias command_help_screen='vim command_help_protobuf.txt文件的路径'  
alias command_help_pod='vim command_help_python.txt文件的路径'  
  
**5**.**例如**:**command_help** 库我放在 **/Users/song/Documents/B_Work/** 目录下           
  
>alias command_help='cd /Users/song/Documents/B_Work/command_help'           
alias command_help_git='vim /Users/song/Documents/B_Work/command_help/command_help_git.txt'  
alias command_help_screen='vim /Users/song/Documents/B_Work/command_help/command_help_screen.txt'  
alias command_help_pod='vim /Users/song/Documents/B_Work/command_help/command_help_pod.txt'  
alias command_help_protobuf='vim /Users/song/Documents/B_Work/command_help/command_help_protobuf.txt'  
alias command_help_python='vim /Users/song/Documents/B_Work/command_help/command_help_python.txt'

# test  
  
>终端输入command_help 对应 进入 command_help 所在目录  
终端输入 command_help_git 对应 vim打开 command_help_git 文件    
终端输入 command_help_screen 对应 vim打开 command_help_screen 文件    
终端输入 command_help_protobuf 对应 vim打开 command_help_protobuf 文件    
终端输入 command_help_python 对应 vim打开 command_help_python 文件  

# other
     
  配合强大的插件##“oh my zsh”## 使用zsh 命令行  
  详情请查看本人简书文章:["oh my zsh 安装以及使用"](http://www.jianshu.com/p/563dc1da2199)
    

