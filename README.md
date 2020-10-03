# GitHub-Hosts
解决 GitHub 在中国大陆的解析问题。   
Hosts 中的内容可能并不全面，也欢迎添加相关服务域名后提交 Pull Request 请求。

## 免责声明
本 Repo 仅提供 GitHub Hosts 解析，不对您在相关网站上的任何操作承担任何责任(包括法律责任)，您在相关网站上的任何操作都将由您自己负责。

## 如何使用？
如果您正在使用 Linux / macOS 或其他类 Unix 系统:
```
nano /etc/hosts
```
然后将此 Repo 中的 hosts 内容添加到您系统中 hosts 文件的末尾。*非常不建议直接覆盖文件。*

如果您在使用 Windows 系统:   
请使用管理员权限的记事本打开 ```C:\Windows\System32\drivers\etc\hosts```, 然后将此 Repo 中的 hosts 内容添加到您系统中 hosts 文件的末尾。*非常不建议直接覆盖文件。*

## 如何贡献？
如果您想添加更多 GitHub 的服务域名，您可以先在 [IPAddress.com](https://www.ipaddress.com/) 查找该域名的解析 IP, 然后将其添加到您系统的 Hosts 中尝试能否正常使用。如果可以，则可以在本项目提交 Pull Request.   
请注意，在提交 PR 时也请将测试图片进行提交，以便加快处理进度。
