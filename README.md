# BLE-
基于NRF52832防丢器实现
开发环境使用的是：Keil MDK5 ：https://www.keil.com/
工程文件在examples\ble_peripheral\ble_app_proximity\pca10040\s132\arm4目录下.
程序下载前首先下载协议栈到BLE芯片，本例使用的协议栈为S132 版本，可以访问Nordic官网找到:https://infocenter.nordicsemi.com/
协议栈起始地址位112K，首先整片擦除，后下载协议栈:下载完后可以下载工程，首先把工程编译一下，通过后点击KEIL 上的下载按键.配套主机使用安卓或者IOS开发的APP,一般测试开发使用Nrf-toolBox.
