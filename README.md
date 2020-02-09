# USB_Protocol_CH
FengJungle整理的USB协议2.0中文版（持续更新）

日期：2019/7/6
修改：2020/2/9

目录
1	简介	5
	1.1	Bus Topology	5
		1.1.1	USB host	6
		1.1.2	USB device	6
	1.2	USB总线协议	7
	1.3	鲁棒性	7
	1.4	USB设备的拔插	7
2	USB数据流模型	8
	2.1	Implementer Viewpoints	8
	2.2	USB总线拓扑	9
	2.3	USB Communication Flow	9
		2.3.1	设备端点	10
		2.3.2	管道	11
	2.4	传输（Transfers）	11
		2.4.1	控制传输（Control Transfers）	12
		2.4.2	中断传输（Interrupt Transfers）	14
		2.4.3	批量传输（Bulk Transfers）	15
		2.4.4	同步传输（Isochronous Transfers）	17
		2.4.5	分离传输（Split Transaction）	17
3	USB物理规范和电气规范	17
	3.1	USB线缆	18
	3.2	电气规范	18
		3.2.1	USB的插入检测机制	18
		3.2.2	信号	18
4	USB 通信协议	21
	4.1	字节顺序	21
	4.2	USB 数据格式	22
		4.2.1	域（Field）	23
		4.2.2	包（Packet）	25
		4.2.3	事务（Transaction）	26
5	USB Device Framework	29
	5.1	USB设备状态	29
		5.1.1	连接(Attached)	30
		5.1.2	上电(Powered)	30
		5.1.3	默认状态(Default)	31
		5.1.4	地址(Address)	31
		5.1.5	配置状态(Configured)	31
		5.1.6	挂起状态(Suspended)	31
	5.2	总线枚举(Bus Enumeration)	32
	5.3	USB请求处理的限制	34
	5.4	设备请求	34
	5.5	标准设备请求	36
		5.5.1	Clear Feature	38
		5.5.2	Get Configuration	38
		5.5.3	Get Descriptor	38
		5.5.4	Get Interface	40
		5.5.5	Get Status	40
		5.5.6	Set Address	41
		5.5.7	Set Configuration	42
		5.5.8	Set Descriptor	43
		5.5.9	Set Feature	43
		5.5.10	Set Interface	44
	5.6	描述符(Descriptor )	44
		5.6.1	设备（Device）	44
		5.6.2	设备限定（Device_Qualifier）	46
		5.6.3	配置（Configuration）	47
		5.6.4	其他速度配置（Other_Speed_Configuration）	48
		5.6.5	接口（Interface）	48
		5.6.6	端点（Endpoint）	49
		5.6.7	字符串（String）	50
6	USB Hub	51




