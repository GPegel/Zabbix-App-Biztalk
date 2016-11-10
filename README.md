# Zabbix-App-Biztalk
This Zabbix template is based on the BizTalk Message Agent.

# Please note:
This template is still under construction. Due to other priorities I need to put this on hold for a while.

# Biztalk components
The following BizTalk components will be checked. All the data is comming from the performance monitor located on the BizTalk node (Perfmon)
- Active Instance Count
- Database Size
- High Process Memory
- High System Memory
- High Thread Count
- In-Process message count
- Message Delivery delay
- Message Delivery incoming rate
- Message delivery outgoing rate
- Message Delivery throttling state
- Message Delivery throttling state duration
- Message Publishing throttling state
- Message Publishing throttling state duration
- Total Batches committed
- Total Messages delivered
- Total Messages published
- Thread Count

This template includes 216 items, 51 triggers and 17 graphs. 

The items are created for the following basic host instances:
BizTalkHost_32bit
BizTalkProcessHost
BizTalkReceiveHost
BizTalkSendHost
BiztalkTrackingHost

There is a possibility that you have more than these 'host instances' so I created HostInstance1 -> HostInstance8.

Feel free to change/edit the items, triggers and/or graphs.