# SPLUNK-1
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/ratio command.png?raw=true" alt="ratio command">
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/ratio.png?raw=true" alt="ratio">
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/table.png?raw=true" alt="ratio">

# source="n8ixlr.csv" sourcetype="csv" host=6b06fe86d4ec | eval ratio=(DOWNLOAD_MEGABITS/UPLOAD_MEGABITS) | table _time, IP_ADDRESS, DOWNLOAD_MEGABITS, UPLOAD_MEGABITS, ratio

# 2020-02-23 14:30:00 - 2020-02-23 23:30:00

# 9 hr recovery

<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/severity%20count.png?raw=true" alt="severity count">
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/all%20critical.png?raw=true" alt="severity critical">
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/alert.png?raw=true" alt="alert">


