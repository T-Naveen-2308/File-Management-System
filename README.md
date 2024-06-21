# Threaded Binary Search Tree Operations

## Overview

This C program implements operations (insertion, deletion, and traversal) in a Threaded Binary Search Tree (TBST).

## Features

- **Insertion**: Insert a new node with a given key into the TBST.
- **Deletion**: Delete a node with a given key from the TBST.
- **Inorder Traversal**: Display nodes in ascending order.
- **Preorder Traversal**: Display nodes in pre-order sequence.
- **Error Handling**: Proper handling of duplicate keys and absent keys during deletion.

## Usage

1. **Compilation**:
   - Compile the program using a C compiler (e.g., gcc):
     ```bash
     gcc -o tbst_operations tbst_operations.c
     ```

2. **Execution**:
   - Run the compiled executable:
     ```bash
     ./tbst_operations
     ```

3. **Menu Options**:
   - Choose from the following options:
     - `1. Insert`: Insert a new node into the TBST.
     - `2. Delete`: Delete a node from the TBST.
     - `3. Inorder Traversal`: Display nodes in ascending order.
     - `4. Preorder Traversal`: Display nodes in pre-order sequence.
     - `5. Quit`: Exit the program.

## Example

```plaintext
1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 1
Enter the number to be inserted : 50

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 1
Enter the number to be inserted : 30

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 1
Enter the number to be inserted : 70

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 3
30 50 70 

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 2
Enter the number to be deleted : 30

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 3
50 70 

1. Insert
2. Delete
3. Inorder Traversal
4. Preorder Traversal
5. Quit

Enter your choice : 5
