# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
|   A   |   B   |   C   |   A AND B   |   A AND B AND NOT C   |
| ----- | ----- | ----- | ----------- | --------------------- |
| False | False | False |    False    |        False          |
| False | False | True  |    False    |        False          |
| False | True  | False |    False    |        False          |
| False | True  | True  |    False    |        False          |
| True  | False | False |    False    |        False          |
| True  | False | True  |    False    |        False          |
| True  | True  | False |    True     |        True           |
| True  | True  | True  |    True     |        False          |


### b
|   A   |   B   |   C   |   B AND NOT C   |   A AND NOT (B AND NOT C)  |
| ----- | ----- | ----- | --------------- | -------------------------- |
| False | False | False |      False      |          False             |
| False | False | True  |      False      |          False             |
| False | True  | False |      True       |          False             |
| False | True  | True  |      False      |          False             |
| True  | False | False |      False      |          True              |
| True  | False | True  |      False      |          True              |
| True  | True  | False |      True       |          False             |
| True  | True  | True  |      False      |          True              |


### c
|   A   |   B   |   C   |   A OR NOT B   |   (A OR NOT B) AND (A OR C)  |
| ----- | ----- | ----- | -------------- | ---------------------------- |
| False | False | False |      True      |            False             |
| False | False | True  |      True      |            True              |
| False | True  | False |      False     |            False             |
| False | True  | True  |      False     |            False             |
| True  | False | False |      True      |            True              |
| True  | False | True  |      True      |            True              |
| True  | True  | False |      True      |            True              |
| True  | True  | True |      True      |            True              |


### d
|   A   |   B   |   C   |   D   |  B OR NOT C   |   NOT A AND D  | A AND NOT (B OR NOT C) | A AND NOT (B OR NOT C) AND (NOT A AND D) | 
| ----- | ----- | ----- | ----- | ------------- | -------------- | ---------------------- | -------------------------------------- |
| False | False | False | False |      False    |      False     | False | False |
| False | False | False | True  |      False    |      True      | False | False |
| False | False | True  | False |      True     |      False     | False | False |
| False | False | True  | True  |      True     |      True      | False | False |
| False | True  | False | False |      True     |      False     | False | False |
| False | True  | False | True  |      True     |      True      | False | False |
| False | True  | True  | False |      True     |      False     | False | False |
| False | True  | True  | True  |      True     |      True      | False | False |
| True  | False | False | False |      True     |      False     | False | False |
| True  | False | False | True  |      True     |      False     | False | False |
| True  | False | True  | False |      False    |      False     | True  | False |
| True  | False | True  | True  |      False    |      False     | True  | False |
| True  | True  | False | False |      True     |      False     | False | False |
| True  | True  | False | True  |      True     |      False     | False | False |
| True  | True  | True  | False |      True     |      False     | False | False |
| True  | True  | True  | True  |      True     |      False     | False | False |


## Question 2

### a
![LogicGateOne](https://github.com/mcgeecaitlin/comp110-worksheet-4/blob/master/LogicGateOne.JPG)

### b
![LogicGateTwo](https://github.com/mcgeecaitlin/comp110-worksheet-4/blob/master/LogicGateTwo.JPG)

### c
![LogicGateThree](https://github.com/mcgeecaitlin/comp110-worksheet-4/blob/master/LogicGateThree.JPG)

### d
![LogicGateFour](https://github.com/mcgeecaitlin/comp110-worksheet-4/blob/master/LogicGateFour.PNG)


## Question 3

### a
|   A   |   B   |   A OR B   |   NOT (A OR B)  |
| ----- | ----- | ---------- | --------------- |
| False | False |   False    |       True      |
| False | True  |   True     |       False     |
| True  | False |   True     |       False     |
| True  | True  |   True     |       False     |

|   A   |   B   |   NOT A AND NOT B  |
| ----- | ----- | ------------------ |
| False | False |        True        |
| False | True  |        False       |
| True  | False |        False       |
| True  | True  |        False       |


### b
|   A   |   B   |   A AND B  |   NOT (A AND B) |
| ----- | ----- | ---------- | --------------- |
| False | False |   False    |      True       |
| False | True  |   False    |      True       |
| True  | False |   False    |      True       |
| True  | True  |   True     |      False      |     

|   A   |   B   |   NOT A OR NOT B  |
| ----- | ----- | ----------------- |
| False | False |        True       |
| False | True  |        True       |
| True  | False |        True       |
| True  | True  |        False      |

### c
|   A   |   B   |   C   |   A AND B  |  A AND C  | (A AND B) OR (A AND C) | 
| ----- | ----- | ----- | ---------- | --------- | ---------------------- |
| False | False | False |   False    |   False   |          False         |
| False | False | True  |   False    |   False   |          False         |
| False | True  | False |   False    |   False   |          False         |
| False | True  | True  |   False    |   False   |          False         |
| True  | False | False |   False    |   False   |          False         |
| True  | False | True  |   False    |   True    |          True          |
| True  | True  | False |   True     |   False   |          True          |
| True  | True  | True  |   True     |   True    |          True          |

|   A   |   B   |   C   |   B OR C   |   A AND (B OR C)  |
| ----- | ----- | ----- | ----------- | ---------------- |
| False | False | False |     False   |      False       |
| False | False | True  |     True    |      False       |
| False | True  | False |     True    |      False       |
| False | True  | True  |     True    |      False       |
| True  | False | False |     False   |      False       |
| True  | False | True  |     True    |      True        |
| True  | True  | False |     True    |      True        |
| True  | True  | True  |     True    |      True        |


### d
|   A   |   B   |   C   |   A OR B   |   A OR C  | (A OR B) AND (A OR C) | 
| ----- | ----- | ----- | ---------- | --------- | --------------------- |
| False | False | False |   False    |   False   |         False         |
| False | False | True  |   False    |   True    |         False         |
| False | True  | False |   True     |   False   |         False         |
| False | True  | True  |   True     |   True    |         True          |
| True  | False | False |   True     |   True    |         True          |
| True  | False | True  |   True     |   True    |         True          |
| True  | True  | False |   True     |   True    |         True          |
| True  | True  | True  |   True     |   True    |         True          |


|   A   |   B   |   C   |   B AND C   |   A OR (B AND C)  |
| ----- | ----- | ----- | ----------- | ----------------- |
| False | False | False |     False   |      False        |
| False | False | True  |     False   |      False        |
| False | True  | False |     False   |      False        |
| False | True  | True  |     True    |      True         |
| True  | False | False |     False   |      True         |
| True  | False | True  |     False   |      True         |
| True  | True  | False |     False   |      True         |
| True  | True  | True  |     True    |      True         |


## Question 4

### a

### b

### c

### d

