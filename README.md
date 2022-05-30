# logger
## Logger
Simple logger class

____
## INSTALLATION
```$ pip install log-py```
____
Example:
```python
from py-log import Log
log = Log("logs")
log.info("Info")
log.warning("Warning")
log.error("Error")
log.personal("Title", "Text")
print(log.get_today_log()) 
```
Result:
```config
[19:50:53] [Info] Info
[19:50:53] [Warn] Warning
[19:50:53] [Error] Error
[19:50:53] [Title] Text
```
____
# Log file deletion example:
```python
from py-log import Log
log = Log("logs")
log.delete_today_log()
log.delete_log("2022-05-30")
```

