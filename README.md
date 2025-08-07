# Python List Operations
This project demonstrates basic list operations in Python, including creating, modifying, and querying lists.

## Operations Performed
1. Creates an empty list called `my_list`
2. Appends elements: 10, 20, 30, 40
3. Inserts value 15 at the second position
4. Extends the list with [50, 60, 70]
5. Removes the last element
6. Sorts the list in ascending order
7. Finds and prints the index of value 30

## Code

```python
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()
print("Index of 30:", my_list.index(30))
print("Final list:", my_list)

## Expected Output

Index of 30: 3
Final list: [10, 15, 20, 30, 40, 50, 60]

## Requirements
- Python installed 
## How to Run
1. Save the code to a file ( `my_List.py`)
2. Run the script: `my_List.py`

This README:
- Uses clear markdown formatting
- Explains the purpose concisely
- Lists all operations performed
- Includes the code in a readable format
- Shows expected output
- Specifies requirements
- Provides simple running instructions
