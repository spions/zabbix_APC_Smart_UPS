# zabbix_APC_Smart_UPS

Шаблон для мониторинга источников бесперебойного питания APC Smart-UPS по SNMP v1.

Элементы данных:

APC Smart UPS - Ampers	 .1.3.6.1.4.1.318.1.1.1.4.2.4.0 		
APC Smart UPS - Battery Capacity 	.1.3.6.1.4.1.318.1.1.1.2.2.1.0  		
APC Smart UPS - Battery Temp 	.1.3.6.1.4.1.318.1.1.1.2.2.2.0		
APC Smart UPS - Environment Temp 	.1.3.6.1.4.1.318.1.1.10.2.3.2.1.4.1 		
APC Smart UPS - Input Frequency 	.1.3.6.1.4.1.318.1.1.1.3.2.4.0 		
APC Smart UPS - Input Voltage 	.1.3.6.1.4.1.318.1.1.1.3.2.1.0		
APC Smart UPS - Load 	.1.3.6.1.4.1.318.1.1.1.4.2.3.0 		
APC Smart UPS - On Battery 	.1.3.6.1.4.1.318.1.1.1.2.1.2.0 		
APC Smart UPS - Output Frequency 	.1.3.6.1.4.1.318.1.1.1.4.2.2.0 		
APC Smart UPS - Output Voltage	.1.3.6.1.4.1.318.1.1.1.4.2.1.0 		
APC Smart UPS - Runtime	.1.3.6.1.4.1.318.1.1.1.2.2.3.0		
		

http://support.ipmonitor.com/tutorials/1b349d0e187f4746807ae10eda7fe2c8.aspx			
APC Smart UPS - Basic Output Status (On-line)	.1.3.6.1.4.1.318.1.1.1.4.1.1.0		
APC Smart UPS - Battery Status	.1.3.6.1.4.1.318.1.1.1.2.1.1.0		
APC Smart UPS - Replace Battery	.1.3.6.1.4.1.318.1.1.1.2.2.4.0		
			

Для корректной работы шаблона, рекомендуется добавить преобразование значений: "Администрирование -> Общие -> Преобразование значений"

PC Battery Replacement Status:
1  unknown
2  notInstalled
3  ok
4  failed
5  highTemperature
6  replaceImmediately
7  lowCapacity

APC Battery Status:	
1  unknown
2  batteryNormal
3  batteryLow
