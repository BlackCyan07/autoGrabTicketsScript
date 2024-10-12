# 铁路12306自动抢票脚本
~~小白程序员编写，可能会有一堆bug，如果发现请上传至issue~~
### 准备工作：
- Python3环境
- 软件包
  - json 
    ```pip install json```
  - yaml 
    ```pip install yaml```
  - requests 
    ```pip install requests```
  - PrettyTable
    ```pip install prettytable```
  - DrissionPage
    ```pip install drissionpage```
  - pypinyin
    ```pip install pypinyin```
### 使用方法：
- 克隆本仓库  
  ```git clone https://github.com/BlackCyan07/autoGrabTicketsScript```
- 打开配置文件*config.yml*进行配置，详细配置说明请参考*config.yml*文件。
- 在终端中运行*script.py*  
  ```python script.py```  
  脚本会根据配置文件中的设置自动登录铁路12306，进行抢票操作   
### 若您有任何疑问或建议，欢迎提交issue。