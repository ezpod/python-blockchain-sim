# Python仿真区块链

使用Python开发一个多节点的仿真区块链，并基于该仿真区块链网络开发一个去中心化的数据分享应用。
适合进行区块链原理性研究，或者在自己的笔记本上仿真区块链网络并进行研究性实验，例如毕业设计
项目或课题研究。本项目代码完整的教程请访问博客[Python仿真区块链](http://blog.hubwiz.com/2020/04/01/python-sim-blockchain/)。


## 代码使用说明

首先克隆项目仓库：

```
$ git clone https://github.com/ezpod/python-blockchain-sim.git
```

安装必要的Python项目依赖：

```
$ cd python_blockchain_app
$ pip install -r requirements.txt
```

启动我们的仿真区块链节点：

```
$ export FLASK_APP=node_server.py
$ flask run --port 8000
```

现在我们的一个仿真区块链节点实例已经启动并在8000端口监听。

开启另一个终端运行我们的去中心化应用：

```
$ python run_app.py
```

现在应用已经启动，可以通过这个网址访问： http://localhost:5000.


下图展示了如何利用web界面向我们的仿真区块链提交内容：

![python仿真区块链](http://blog.hubwiz.com/2020/04/01/python-sim-blockchain/Fig1.png)

下图展示了如何利用web界面启动节点挖矿：

![python仿真区块链](http://blog.hubwiz.com/2020/04/01/python-sim-blockchain/Fig2.png)

下图展示了如何利用web界面重新同步区块链数据：

![python仿真区块链](http://blog.hubwiz.com/2020/04/01/python-sim-blockchain/Fig3.png)
