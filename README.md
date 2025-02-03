# Mario

## Instructions

Toward the end of World 1-1 in Nintendo's Super Mario Bros, Mario must ascend right-aligned pyramid of bricks, as shown in the below.

![Mario](mario.png)

In a file called `mario.py`, implement a program in Python that recreates that pyramid, using hashes (`#`) for bricks, as in the below.

```
       #
      ##
     ###
    ####
   #####
  ######
 #######
########
```

Prompt the user for an `int` for the pyramid's actual height, so that the program can also output shorter pyramids like the below.

```
  #
 ##
###
```

If the user entered a height of 0 and below, output `Incorrect height.`

## Sample Checkpoints

### Sample Input 1

```
1
```

### Sample Output 1

```
#
```

### Sample Input 2

```
5
```

### Sample Output 2

```
    #
   ##
  ###
 ####
#####
```

### Sample Input 3

```
-1
```

### Sample Output 3

```
Incorrect height.
```


