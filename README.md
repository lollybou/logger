# logger
## Logger
Simple logger class

____
## INSTALLATION
```$ pip install log-py```
____
Example:
```python
import py-log
log = py-log.Log("logs",False)
log.info("Info")
log.warning("Warning")
log.error("Error")
log.personal("Title", "Text", "Color")
print(log.get_today_log()) 
```
Result:
```
[19:50:53] [Info] Info              #
[19:50:53] [Warn] Warning           #
[19:50:53] [Error] Error            #
[19:50:53] [Title] Text             # 
```
