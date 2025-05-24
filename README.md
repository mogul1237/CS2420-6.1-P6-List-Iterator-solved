# CS2420-6.1-P6-List-Iterator-solved

Download Here: [CS2420 6.1 P6 – List Iterator solved](https://jarviscodinghub.com/assignment/6-1-p6-list-iterator-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Linked-List Iterator
You may not use the standard template library for this or any other project this semester unless specifically mentioned in the instructions.
Disclaimer: I have not used any code other than my own (or that in the textbook) for this project I also have not used any
function or data-structure from the Standard-Template Library I understand that any violation of this disclaimer will result in a 0 for the
project.
Purpose
Understanding external iterators and linked lists.
Instructions
• Create a List class with the following member functions:
Listo //i.e. default constructor
o •cist()
o void push_front(const int& value) // add new node to front of the list
o void push_back(const int& value) // add new node to back of the list
o void remove(const int& value) // removes ALL nodes in list with this value
o Iterator begin() // iterator to the beginning of the list
o Iterator end() // iterator tothe end of the list
o int size() // number of elements currently in list
o void PrintListO // mainly for debugging
• documentation of the above member functions can be found at:
o https://en.cppreference.com/w/cpp/container/list
• Create an External Iterator class called Iterator with the following member functions:
o Iterator(Node *start) // The iterator initially points to “start”.
o int operator*() // dereference the iterator
o Iterator operator++() // advance the iterator
o bool operatorl=(const Iterator& other) // returns true if and only if other iterator does not equal this iterator
o bool is_item() // returns true if Iterator points to a valid Node (if nullptr return false…)
• Create a Node class
o NodeO
o data
o next
o Observer tmp; // required for Unit Testing
Complete the implementation of all the functions using a Linked List as the underlying implementation.
Use the code in Main.cpp to verify that your List functions properly. (You can add your Project Prologue comments to the beginning of
List.cpp)
Initial List
98765432
Displaying List
98765432
Displaying List
98765432
Displaying List
87543211
1 øø123456789
with external iterators
1 øø123456789
with new for-loop
1 øøl
without
2
3456789
e ‘s, 9’s, or 6’s


