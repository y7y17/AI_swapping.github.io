# TinyFace
 <a href="https://pypi.python.org/pypi/tinyface"><img src="https://img.shields.io/pypi/pyversions/tinyface.svg" alt="Compatible Python versions."></a>

基于Python和tinyface库实现的AI换脸小工具，支持通过上传图片实现人脸快速交换，适合普通用户使用
## 特性
- **极简设计**：专注于人脸交换功能，界面简洁，依赖轻量，一键实现换脸功能<br>
- **硬件友好**：在普通计算机中可运行，无须额外插件<br>
- **离线操作**：上传的图像不会被收集，保护隐私
## 使用方法
- **环境要求**<br>
系统：Windows/macOS/Linux<br>
配置Python环境:
```bash
pip install -r requirements.txt
```
- **务必成功运行py文件方可使用网页，否则将无法加载出换脸图片**
```bash
python .\tinyface-api.py
```
- **访问网页**
Py文件运行成功后，在同一目录下打开html文件访问网页
- **界面操作**
上传图片，注意input image中的人脸与reference face中必有一张人脸一致，destination image为换脸目标图片
上传成功后点击一键换脸
## 声明
本网页建立于优秀的开源项目TinyFace之上进行开发
**请务必遵守法律法规**，不得滥用真实人脸数据侵犯他人权益，开发者不对任何滥用行为负责
本项目仅限于个人娱乐，不得用于商业用途，确保使用时获得授权
## 改进邀请
本项目在input image只有一张人脸时具有上传重复图片的局限性，我们欢迎社区开发者参与项目改进
