NVMe_RDT_TESTER
==============================
SSD 產品測試軟體
	單機於高溫高壓環境下同時對96個Drive進行測項測試，也可依需求而分區進行不同測項測試。
-----------------------------------------------------------------
### 當前版本 ###
[PLM] RDS-000133

版號: v0.9.1

日期:2018/07/09

更新事項:
		1. 完善User Specify測項功能
		2. Test Report
		3. Port Status 資訊更新
		4. 修改RDT Editor(JSON Format)於Python 3.5 排序異常

------------

### 主要功能 ###

*Application:
				
				1. 軟體設計風格仿照Flexstar套裝軟體
				2. 軟體需包含JEDECClient/JEDECEnterprist/User Specify三種測項
				3. 同時可針對多Drive進行測項測試
				4. 針對User Specify需額外設計編輯器，進行組譯並於NVRe_RDT_TESTER APP進行操作
				5. Chamber進行溫度控制操作
	
### 環境 ###

*Environment:
				OS系統Ubuntu 16.04
				nvme-cli v1.5 or higher
				FIO v.2.x or higher
				JAVA OPEN JDK 8.0 or higher
				 
				


