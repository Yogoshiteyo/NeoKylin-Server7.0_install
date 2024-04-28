# Yogoshiteyo-NeoKylin-Server7.0_install
## 1. 制作启动U盘
### 1.1 下载并安装ventoy
ventoy下载链接：[https://github.com/ventoy/Ventoy/releases](https://github.com/ventoy/Ventoy/releases/download/v1.0.97/ventoy-1.0.97-windows.zip)

插入U盘

打开ventoy2disk

![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/b0984ab4-5ac3-452b-a4d3-ad0105f03e14)

点击安装（制作过程中会将U盘格式化，请确保U盘中没有重要文件）

### 1.2 将NeoKylin-Server7.0的镜像拷贝至U盘中
F:\NeoKylin-Server7.0-Release-Build09.06-20220311-X86_64

## 2. 开始安装
### 2.1 从U盘启动
各服务器厂商启动选项不一样，一般为F12.具体需要注意服务器启动时的提示信息，按BOOT MENU对应的按键。

选择插入的U盘，即可进入ventoy中

### 2.2安装Neokylin
进入ventoy后，选择NeoKylin-Server7.0-Release-Build09.06-20220311-X86_64

![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/820c6ede-472f-46e5-a66c-e0b43fae4612)

进入安装页面，选择第一项
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/7a0f9e4c-6951-4465-89fd-f6d67fe069f5)

按ENTER开始安装
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/3ee380b0-d1a2-4d5a-a65b-4692c8cfdcd1)

默认中文，点击继续
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/e1071f7c-3f35-4134-a07c-c208d27edaf4)

点击“安装位置”自定义分区
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/eabf5426-24fe-4938-9aea-895c4b584ac3)

选择“我要配置分区”> 完成
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/d4f6113b-6bf5-4a0b-ba51-e653c4f0f0a8)

选择“分区方案”为“标准分区”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/c7e1f49d-6347-4c5c-974a-bc5ca951a401)

点击“+”，新增挂载点，
1). 添加挂载点“/boot”容量设为1G
2). 添加挂载点“swap”，容量设为与内存相等
3). 添加挂载点“/”,容量不填，直接点“添加挂载点”，将剩余的所有空间分配至“/”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/41bf0f8e-5e6e-4841-a57c-0dd65c1a9085)
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/67b7e0cf-bd17-4e67-9ed7-8a781f42924e)

点击“完成”>“接受更改”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/06eeeb64-626c-4d90-b133-b7038f915718)

选择“网络和主机名”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/0248883d-13e2-46f8-9ea6-a04e80fc56ab)

点击“配置”，选择“常规”，将“可用时自动连接到这个网络”勾选
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/040fbbdc-9758-46c0-ad38-e8d42761bc31)

选择IPV4配置，点击“添加”，配置IP地址，子网掩码，网关及DNS，点击保存
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/02df8aa6-2cd9-44a5-b36a-30e4be63ed4f)

点击“完成”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/2f62e29e-7b74-4364-b044-a1b9c7cbf6f9)

点击“开始安装”，点击“ROOT密码”，设置好密码，点击“完成”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/7f543e8b-1c22-4716-b7b9-9c270f946893)
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/437fc3be-bac2-4123-8f8d-38fed0f9b180)

安装完成后点击“重启”
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/fce5cbcd-3699-42eb-abac-338cf5624b66)

登录系统
![image](https://github.com/Yogoshiteyo/Yogoshiteyo-NeoKylin-Server7.0_install/assets/58699906/d1990133-c20f-43a5-a1d8-153a59df9f35)

