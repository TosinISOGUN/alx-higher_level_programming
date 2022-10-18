# Python - Everything is Object

## Table of Contents
| Files | Description |
| --- | --- |
|0-answer.txt	| What function would you use to print the type of an object? |
| 1-answer.txt	| How do you get the variable identifier (which is the memory address in the CPython implementation)? |
| 2-answer.txt	| a = 89, b = 100. Do a and b point to the same object? |
| 3-answer.txt	| a = 89, b = 89. Do a and b point to the same object? |
| 4-answer.txt	| a = 89, b = a. Do a and b point to the same object? |
| 5-answer.txt	| a = 89, b = a + 1. Do a and b point to the same object? |
| 6-answer.txt |	s1 = "Holberton", s2 = s1, print(s1 == s2). What do these 3 lines print? |
| 7-answer.txt |	s1 = "Holberton", s2 = s1, print(s1 is s2). What do these 3 lines print? |
| 8-answer.txt	| s1 = "Holberton", s2 = "Holberton", print(s1 == s2). What do these 3 lines print? |
| 9-answer.txt	| s1 = "Holberton", s2 = "Holberton", print(s1 is s2). What do these 3 lines print? |
| 10-answer.txt	| l1 = [1, 2, 3], l2 = [1, 2, 3], print(l1 == l2). What do these 3 lines print? |
| 11-answer.txt	| l1 = [1, 2, 3], l2 = [1, 2, 3], print(l1 is l2). What do these 3 lines print? |
| 12-answer.txt	| l1 = [1, 2, 3], l2 = l1, print(l1 == l2). What do these 3 lines print? |
| 13-answer.txt| 	l1 = [1, 2, 3], l2 = l1, print(l1 is l2). What do these 3 lines print? |
| 14-answer.txt	| l1 = [1, 2, 3], l2 = l1, l1.append(4), print(l2). What does this script print? |
| 15-answer.txt	| l1 = [1, 2, 3], l2 = l1, l1 = l1 + [4], print(l2). What does this script print? |
| 16-answer.txt	| def increment(n): n += 1; a = 1, increment(a), print(a). What does this script print? |
| 17-answer.txt	| def increment(n): n.append(4); l = [1, 2, 3], increment(l), print(l). What does this script print? |
| 18-answer.txt	| def assign_value(n, v): n = v; l1 = [1, 2, 3], l2 = [4, 5, 6], assign_value(l1, l2), print(l1). What does this script print? |
| 19-copy_list.py	| Python function def copy_list(l): that returns a copy of a list
| 20-answer.txt	| a = (). Is a a tuple? |
| 21-answer.txt	| a = (1, 2). Is a a tuple? |
| 22-answer.txt	| a = (1). Is a a tuple? |
| 23-answer.txt	| a = (1, ). Is a a tuple? |
| 24-answer.txt	| a = (1), b = (1), a is b. What does this script print? |
| 25-answer.txt	| a = (1, 2), b = (1, 2), a is b. What does this script print? |
| 26-answer.txt	| a = (), b = (), a is b. What does this script print? |
| 27-answer.txt	| a = [1, 2, 3, 4], id(a), 139926795932424, a = a + [5], id(a). Will the last line of this script print 139926795932424? |
| 28-answer.txt	| a = [1, 2, 3], id (a), 139926795932424, a += [4], id(a). Will the last line of this script print 139926795932424? |
| 100-magic_string.py	| Python function magic_string() that returns a string “BestSchool” n times the number of the iteration. |
| 101-locked_class.py	| Python class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name. |


## Requirements & Environment
<img src="https://alx-apply.hbtn.io/brand_alx/share_image_2019.jpg" width="300" height="100" />

### Python Scripts
- Allowed editors: `vi`, `vim`, `emacs`.
- All files are interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- A README.md file at the root of the repo, containing a description of the repository
- A README.md file, at the root of the folder of this project, is mandatory
- Coding Style;
  - Pycodestyle (version 2.8.*)
- All files must be made executable.

### `.txt` Answer Files
- Only one line
- No Shebang
- All files should end with a new line.


## Authors & Credits
- [Oluwatomisin ISOGUN](https://@github.com/TosinISOGUN)
> Other collaborators are acknowledged within the repository.
