# BluetoothChat
设计的是一个Android蓝牙聊天系统，该系统是通过Android的蓝牙聊天应用程序来实现两个设备通过蓝牙进行连接并聊天的功能
设计的是一个Android蓝牙聊天系统，该系统是通过Android的蓝牙聊天应用程序来实现两个设备通过蓝牙进行连接并聊天的功能
实现的步骤：UI界面的开发设计；设置蓝牙的操作权限；获得本机蓝牙地址；在子线程中创建蓝牙的服务对象，并编写打开按钮监听事件；
使用handler通讯机制，将子线程的运行情况更新到控件中；在子线程中添加信息提示；新建子线程，使用socket发送数据；
关闭服务。我们还在该系统内添加了国际化，中文和英文，满足不同用户的需求。
最后运行测试，成功实现了两台设备用蓝牙连接进行聊天的功能。
