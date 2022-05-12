# SPLUNK-1
<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/ratio command.png?raw=true" alt="network diagram">

# source="n8ixlr.csv" sourcetype="csv" host=6b06fe86d4ec | eval ratio=(DOWNLOAD_MEGABITS/UPLOAD_MEGABITS) | table _time, IP_ADDRESS, DOWNLOAD_MEGABITS, UPLOAD_MEGABITS, ratio

# 2020-02-23 14:30:00 - 2020-02-23 23:30:00

# 9 hr recovery

<img src="https://github.com/MateiGanea/SPLUNK-1/blob/main/screenshots/ratio.png?raw=true" alt="network diagram">
