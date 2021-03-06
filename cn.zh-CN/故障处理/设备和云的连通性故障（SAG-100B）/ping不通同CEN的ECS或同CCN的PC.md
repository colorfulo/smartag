# ping不通同CEN的ECS或同CCN的PC {#trouble_j3z_yyf_4fb .troubleshooting}

## 故障现象 { .condition}

终端无法连接到阿里云，例如ping不通同CEN的ECS或同CCN的PC。

## 可能原因 { .cause}

-   终端到设备的链路故障。
-   设备到阿里云的VPN链路故障。
-   目标ECS故障。
-   运营商网络故障。

1.  登录[智能接入网关控制台](https://smartag.console.aliyun.com/sag/cn-shanghai/sags)。 
2.  单击智能接入网关实例ID，查看设备状态是否为**可用**。 
    -   如果离线，请参考[设备显示离线](cn.zh-CN/故障处理/设备和云的连通性故障（SAG-100WM）/设备显示离线.md#)处理。
    -   如果未离线，请确认设备是否处于**可用**状态，如若不是，请检查设备是否绑定CCN或者是否到期，否则请跳转至[3](#step3)。
3.  请检查设备的配置是否符合预期。 
    -   在智能接入网关控制台，检查设备配置的私网网段和绑定的云连接网是否符合预期。
    -   在设备WEB配置上检查设备WAN和LAN的配置是否符合预期，如果配置正常，请跳转至[4](#step4)。
4.  可能是设备内部软件问题， 可以尝试重启盒子进行恢复或提交工单处理。 

