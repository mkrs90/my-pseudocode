# How An Elevator Works

## INIT 
- Up and down button on each floor
    - directionalBtn

- button inside the elevator that have floor numbers
    - floorBtn

- An array of floors numbers for the building
    - floorArray

- door - can be open or closed
    - doorStatus
    - doors can be held open or shut early
    - warning sounds when door has been held open for to long

- display that shows which floor the elevator is on
    - floorNum
    - a sound plays when the elevator arrives to specific floor number


### START 

- **IF** button has been pressed.

- **READ** the floor the button was pressed on. 

- **IF** current floor is less than floor button was pressed on  **INCREMENT** floor by 1 until floor **EQUALS** the floor the button was pressed on.

- Once the floor has been reached - open door for 10sec then close(**IF** not blocked)

    - **IF** Door is is still open after 10 secs give warning and rerun 10sec timer.

- Wait for input of which floor to travel to.

- **CALCULATE** **IF** the floor selected is greater than the current floor you are on. **IF** true the direction will be set to travel up. **Else** it will be set to travel down. 

- Travel to the furthest call in your current direction **UNTIL** you reaches that floor

- Only move **IF** the door is closed.

- **INCREMENT** one floor at a time **UNTIL** you reach the floor requested. 

- **WHILE** traveling stop at all calls that have selected the same direction you are currently going.
    
- Once the furthest call has been reached switch directions.

- Answer all car calls matching new direction.

- Continue **UNTIL** the furthest call has been reached 

- **REPEAT** until all calls have been handled. 

### END - once all car calls have been handled.









