python-sdk的client-config.py中都使用绝对路径，在根路径/home/fiscos-bcos/下。

使用Django框架需要安装环境，以调用库。

运行服务端在SupplyChainProject目录下使用./manage.py runserver。
首页地址是localhost:8000/SupplyChainApp/index

SupplyChainProject/SupplyChainApp目录下的connect.py文件用于连接服务端和python-sdk，其中设置了合约的地址to_address，如要重新部署需要重新设置。合约在python-sdk/constracts目录下，命名为SupplyChain1.sol。