# Python-Colors
---
## Examples:
```python
from colors import Colors
print("I" + Colors.Red + "Love" + Colors.Full_Reset + "You")
Print(Colors.Yellow + Colors.Blink + "WARNING" + Colors.Full_Reset)
# Do not forget the Colors.Full_Reset after using colors :)
```
```python
from replit import clear # pip3 install replit # or you can use subproccess to clear
from time import sleep

times = int(input("How many times do you want it to run? ")) # 12
Sleep_time = float(input("Put the sleep time: ")) # 0.5
message = input("The message you need to print: ")

warning_colors = [Colors.Red, Colors.Yellow]
for i in range(times):
    for i in warning_colors:
        print(i + str(message) + Colors.Full_Reset)
        sleep(Sleep_time)
        clear()
```
```python
from colors import Colors

background = Colors.BackgroundCyan + Colors.Black_Dim + "COOL Background" + Colors.Full_Reset
print(background)
```
---
**Follow me**: https://github.com/TheRealMitch
