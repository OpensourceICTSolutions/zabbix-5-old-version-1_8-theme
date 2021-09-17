# Zabbix version 5.4 theme with Zabbix version 1.8 look and feel

Welcome to the Opensource ICT Solutions GitHub, where you'll find all kinds of usefull Zabbix resources. This Repository contains a theme which transforms your Zabbix 5.4 setup to a Zabbix 1.8 look and feel.

## Installation Guide

1. Navigate to the link above.
2. Download the three files: (oldisnew.css),(tablehead2.gif) and APP_add_on.text.
3. On your Zabbix server CLI there should be a directory called /usr/share/zabbix/assets/styles/. Put the (oldsinew.css) and (tablehead2.git)files here.
4. For APP_add_on.txt add the text to the APP.php located at the directory /usr/share/zabbix/include/classes/core/ inside of (class APP extends ZBase).(this allows you to actually see the theme inside of the dropdown.)
5. Now, at the Zabbix GUI navigate to Profile under User settings and change the theme.
6. Enjoy your new theme! 

