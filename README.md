# Karel's commands

|command|description|
|---|---|
|move()|	Asks Karel to move forward one block. Karel cannot respond to a move() command if there is a wall blocking its way.|
|turn_left()|Asks Karel to rotate 90 degrees to the left (counterclockwise)|
|pick_beeper()|Asks Karel to pick up one beeper from a corner and stores the beeper in its beeper bag, which can hold an infinite number of beepers. Karel cannot respond to a pick_beeper() command unless there is a beeper on the current corner.|
|put_beeper()|Karel cannot respond to a put_beeper() command unless there are beepers in its beeper bag.|


```
from karel.stanfordkarel import *

def main():
   move()
   pick_beeper()
   move()
```

```
def turn_right():
  turn_left()
  turn_left()
  turn_left()
```
