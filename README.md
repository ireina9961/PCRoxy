# PCRoxy  

## 简介  
本项目是基于`mitmproxy`的开源PCR网络代理工具。  
本项目目前仍处于早期测试阶段，功能受限，文档缺失且不保证接口向后兼容性。  

## 快速上手  
1. 将项目克隆至本地并准备好python3环境。本项目建议使用3.9及以上版本。  
2. `pip install -r requirements.txt`安装依赖  
3. `python run.py`启动项目。你应当能看到浏览器自动打开了一个页面。  
4. 为需要使用代理的设备配置代理并安装证书。`PCRoxy`代理地址可以在终端或网页右下侧看到，默认为`http://*:8012`；代理配置完成后可访问`http://mitm.it`下载并安装证书。  
5. 启动游戏。若此前配置正确，你可以在浏览器点击并浏览加密的数据内容。在你登陆时，插件也会输出从请求与响应中获取到的信息。  

## 插件配置与使用  
插件的配置与使用方法请参考plugins下的README.md。  

## 有疑问&&有建议  
欢迎issue，欢迎pr，欢迎创作插件。  

## TODO  
- `asyncio`支持  
- 更多模式及基于插件的修改管理  
- 将类注册为插件或同一插件上下文信息传递  
- 更多的有用插件  
- 完善文档  

## 免责声明
本项目仅供学习研究使用。错误使用本项目可能为您的虚拟财产带来风险，使用者应为自己的操作负责。  