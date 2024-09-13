## Basics
    OPERATOR NUMBER MOTION
    Upper case letter UP from cursor O
    Lower case letter DOWN from curso o

    p - put after
    P - put before
    x - delete
    i - insert before character
    A - append to end of line

    R - replace till stopped

### motions
    w - start of next word
    e - end of current word
    0 - to the start of line
    % - matching bracket

    U - undo the line

## Replace
    :%s/old/new/gc  - replace with confirm in the whole file

## REtrieve
    :r FILENAME - insert file
## External commands

    :r !ack console - read output of the ack command into the current buffer

## Navigation
    CTRL o previous position
    CTRL i next position

    Use CTRL+<hjkl> to switch between windows

## Code manipulation
    "leader ca" code actions over errors and warning
    "leader f" format buffer


## RANDOM
    "leader /" find in current buffer 
    "gc" to comment visual regions/lines
    "gd" go to definition


    :w - will write to stdin of the next command like :w !wc -w



# options

    set ic - ignore case
    /<search term>\c


### links

https://www.moolenaar.net/habits.html
