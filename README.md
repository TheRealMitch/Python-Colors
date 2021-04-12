# Python-Colors

Change the color of the print() function in Python 3.
For terminals that support color.

## Examples:

```python
from colors import Colors
print("I" + Colors.Red + Colors.Blink + " Love " + Colors.Full_Reset + "You")
print(Colors.Yellow + Colors.Blink + "WARNING" + Colors.Full_Reset)
# Do not forget the Colors.Full_Reset after using colors :)s :)
```
```python
from replit import clear # pip3 install replit # or you can use subproccess to clear
from time import sleep
from colors import Colors

times = int(input("How many times do you want it to run? ")) # 12
Sleep_time = float(input("Put the sleep time: ")) # 0.5 # 0.25 # 1
message = input("The message you need to print: ") # Hellow, how are you

warning_colors = [Colors.Red, Colors.Yellow, Colors.Green]
for i in range(times):
    for i in warning_colors:
        print(i + str(message) + Colors.Full_Reset)
        sleep(Sleep_time)
        clear()
```
```python
from colors import Colors

background = Colors.BackgroundCyan + Colors.Black_Dim + "Cool Background" + Colors.Full_Reset
background_blink = Colors.Black_Dim + Colors.BackgroundCyan + Colors.Blink + "Cool Background" + Colors.Full_Reset
print(background)
print(background_blink)
```
---

- **Follow me**: [Github](https://github.com/TheRealMitch)
- **Watch me Sing -->** [Youtube](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
