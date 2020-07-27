# BluetoothDemo

## 新增功能
新增android蓝牙同时连接多台设备的功能。

仅支持连接ble设备。

## 说明
    原始项目https://github.com/wdmxzf/BluetoothDemo.git

* 自定义 Service 对蓝牙的操作进行封装
* 使用 BluetoothAdapter.startDiscovery()； 方法进行设备扫描
* 使用 BluetoothGatt 进行蓝牙连接
* BluetoothGattCallback 对数据进行回调处理
* 该demo只需知道蓝牙设备的命令，就可以向蓝牙设备发送指令，不需要了解通道是什么。

