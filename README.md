# cisco_plaza

eee
1. В течение 24 часов все потребители оборудования Cisco на территории России будут отключены от Смарт аккаунтов.
2. В течение суток будет инициировано проверка лицензирования со стороны серверов Cisco
 
Что рекомендовано сделать:
1. На выходе инфраструктуры в сеть Интернет поставить жесткий access-list с запретом трафика на адрес tools.cisco.com
 
Если этого не сделать, то устройства, требующие лицензирования и/или подписки, перестанут функционировать. Будет остановка функционала.
Это касается:
1. Всех решений безопасности (Cisco ISE, Cisco ASA)
2. Телефония и унифицированные коммуникации (UC)
3. Все решения Software-defined
 
Если сделать, то будет отложенный период от 30 до 90 дней, когда функционал оборудования сохранится.
