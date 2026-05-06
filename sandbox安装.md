# 1 下载安装文件
```
项目地址：
https://github.com/sandboxie-plus/Sandboxie
下载地址：
https://github.com/sandboxie-plus/Sandboxie/releases/download/v1.17.2/Sandboxie-Classic-x64-v5.72.2.exe
```

# 2 设置沙箱路径
```
配置->编辑配置文件->GlobalSettings项添加并保存：
FileRootPath=D:\Sandbox\%SANDBOX%
配置->编辑配置文件->重新载入配置
```

# 3 编辑快捷方式
```
创建快捷方式后属性中编辑目标：
"D:\Program Files\Sandboxie\Start.exe" /box:Browser 原始目标
```
