# How An Elevator Works

## START
1. IF button is pressed, travel to the floor the button was pressed on.

2. Once the elevator reaches the floor it will open the doors

3. User enters the elevator and makes a selection of which floor they want to travel too.

4. If the floor selected is greater than current floor elevator direction will be set to up. 
    else it will be set to down. (The elevator will always travel to the furthest call in its current direction)

5. Elevator will only move if the door is closed.

6. Elevator will rise one floor at a time and open doors once it reaches floor selected by user.    

7. while traveling the elevator will stop at all calls that have selected the same direction it is currently going
    
8. Once it has reached the furthest call it will then travel in the opposite direction it was going.

9. The elevator will answer all car calls matching its direction.

10. The elevator will continue until it has reached the furthest call of its current direction.

11. Repeat until all calls have been handled. 

## END

### INIT

Floor array - lists all the floor numbers
Floor direction - either up or down









