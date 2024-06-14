# HFS_RCE

### 声明

**本工具仅用于个人安全研究学习。由于传播、利用本工具而造成的任何直接或者间接的后果及损失，均由使用者本人负责，工具作者不为此承担任何责任。**

------
CVE-2024-23692

version = 2.3m

------

NAME:
   HFS - 命令执行

USAGE:
    [global options] command [command options] [arguments...]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --target_url url, -u url          读取单个目标的url
   
   --target_file File, -f File       从File读取批量读取URL
   
   --target_command value, -c value  执行命令
   
   --output File, -o File            扫描结果输出到File (default: "success.txt")
   
   --proxy url, -p url               代理的url地址
   
   --thread 数量, -t 数量                批量扫描时的线程数量 (default: 20)
   
   --help, -h                        show help

------

### 截图
![image](https://github.com/ggfzx/HFS_RCE/assets/86279656/dab41b70-a3df-4f23-a66c-65ccb6d761cb)
