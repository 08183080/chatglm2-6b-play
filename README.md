# chatglm2-6b-play
just finetune chatglm2-6b
# daily log
- [x] 3/6, 远程微操指导客户chatglm2-6b的微调
  - [x] 远程指导客户带他读ptune文档
  - [x] ptune官方doc: https://github.com/THUDM/ChatGLM2-6B/tree/main/ptuning
  - [x] 【客户: 如何全面更新参数呢】使用deepspeed工具 https://github.com/microsoft/DeepSpeed
  - [x] 不打无准备之仗, 之前没实际跑过, 晚上不禁略微面红耳赤笑死
  - [x] 客户公司是A6000, 显卡有48G显存, 完全可以支持全参数训练
  - [x] 客户在公司的电脑运行出现报错, 错误log我让他转储, transformer包需要更新以及torch训练?
- [x] 3/11, 今天回到上海, 白天和客户聊了聊, 才发现客户公司的服务器是win10, 用windows运行shell脚本, 电脑cuda和torch安装也不尽如人意, 我懵逼了
  - [x] 晚上我实在忍不住下场了, 我可以在电脑上设置pip.ini设置python安装包的默认下载源(清华): https://www.cnblogs.com/mini-monkey/p/11175485.html
  - [x] pip install -r requirements.txt是可以把所有的包下载下来的, 在网络通畅的情况下 
