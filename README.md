# readyCode
readyCode is a Python module to help Python developers develop their applications easily. This module promotes simplicity, readability, and reusable code.

## Overview of Functions

### `close_files(*files)`

This function closes multiples files at the same time.

#### Example

```
file_1 = open("file_1.txt")
file_2 = open("file_2.txt", "a")
file_3 = open("file_3.txt")

close_files(file_1, file_2)

file_4 = open("file_4.txt", "w")
file_5 = open("file_5.txt", "r+")

close_files(file_3, file_4, file_5)
```


### `get_keys(dictionary, value)`

This function gets the keys, of a dictionary, with a particular value.

#### Example

```
available_items = {"Apple": 4.99, "Banana": 4.99, "Cabbage": 12.99, "Dates": 9.99, "Eggplants": 10.99}

five_dollar_items = get_keys(available_items, 4.99)
```

### `file_exists(file, iterable=[])`

This function finds if a give files exists within a folder.

#### Example

```
code_exists = file_exists("readyCode.py")

print(code_exists)
```

## Contact Us

Do you have any suggestions, questions, comments, or concerns? Reach out to the developer with aarindave@gmail.com!
