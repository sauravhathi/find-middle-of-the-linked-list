# Find Middle of a Linked List

## Problem Statement

Given a linked list, find the middle of the linked list. For example, if the given linked list is 1->2->3->4->5 then the output should be 3. If there are even nodes, then there would be two middle nodes, we need to print the second middle element. For example, if given linked list is 1->2->3->4->5->6 then the output should be 4.

## DEMO

### https://sauravhathi.github.io/find-middle-of-the-linked-list

## SCREENSHOTS

### 1. Home Page



### 2. Input Page



### 3. Output Page



## Algorithm

1. Initialize two pointers, `fast` and `slow`, to the head of the linked list.
2. Move `fast` two nodes and `slow` one node at a time.
3. When `fast` reaches the end of the linked list, `slow` will be at the middle of the linked list.

## Functions

### `getList()`

This function returns the list entered by the user.

### `validateArray(list)`

This function validates the list entered by the user. It returns `true` if the list is valid and `false` if the list is invalid.

### `reset()`

This function resets the page.

### `Node(data)`

This function creates a node for the linked list.

### `LinkedList()`

This function creates a linked list.

### `add(data)`

This function adds a node to the linked list.

### Node `findMiddle()`

This function finds the middle of the linked list and returns the middle element.

### `findMiddle()`

This function finds the middle of the linked list and prints the middle element.

## Classes

### `Node`

This class creates a node for the linked list.

### `LinkedList`

This class creates a linked list.

## Variables

### `list`

This variable stores the list entered by the user.

### `listError`

This variable stores the error message for the list.

### `resultDiv`

This variable stores the result div.

### `result`

This variable stores the result.

### `linkedList`

This variable stores the linked list.

### `middle`

This variable stores the middle element of the linked list.

### `ul`

This variable stores the unordered list.

### `indexOfListUl`

This variable stores the unordered list of the index of the elements.

### `li`

This variable stores the list item.

### `indexOfListLi`

This variable stores the list item of the index of the elements.

### `temp_index`

This variable stores the index of the middle element.

### `p`

This variable stores the paragraph.