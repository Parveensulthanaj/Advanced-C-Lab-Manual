# Advanced-C-Lab-Manual
## EXP NO:3A C PROGRAM TO DISPLAY STACK ELEMENTS USING AN ARRAY.

## Aim:
To write a C program to display stack elements using an array.
## Algorithm:
1.	Include Necessary Header Files
2.	Declare Global Variables
3.	Define the Display Function
4.	Main Function (or Other Relevant Code)
5.	Initialize the stack and top as needed.
6.	Perform stack operations (push, pop, etc.).
7.	Use the display function to visualize the stack's contents
 
## Program:
```
int stack[40],top,i; void display()
{
for(i=top;i>=0;i--)
{
printf("%d\n",stack[i]);
}
}
```
## Output:

![Screenshot 2025-04-26 203027](https://github.com/user-attachments/assets/8f126a02-fd20-4a72-b789-e9d8318c88e6)


## Result:
Thus, the program to display stack elements using an array is verified successfully.
 

## EXP NO:3B  PROGRAM TO PUSH THE GIVEN ELEMENT IN TO A STACK USING ARRAY.
## Aim:
To create a C program to push the given element in to a stack using array.
## Algorithm:
1.	Declare global variables for the stack size, top index, and the stack itself.
2.	Define the push function to add a floating-point number to the stack.
3.	Initialize the stack size, top index, and the stack itself.
4.	Call the push function as needed.
 
## Program:
```
int size=3,top=1; float stack[40];
void push (float data)
{
if (top==size-1 )
{
printf("stack is full\n");
}
else
{
top ++; stack[top] = data;
}
}
```
## Output:


![Screenshot 2025-04-26 203052](https://github.com/user-attachments/assets/dd3bf811-1b3e-412a-ac91-c7fc3f389e82)


## Result:
Thus, the program to push the given element in to a stack using array is verified successfully
 
## EXP NO:3C  C PROGRAM TO DISPLAY QUEUE ELEMENTS USING ARRAY.
## Aim:
To write a C program to display queue elements using array

## Algorithm:
1.	Declare global variables for the queue, rear, front, and iteration.
2.	Define the display function to print the elements of the queue.
3.	Initialize the queue, rear, and front as needed.
4.	Call the display function and perform other queue operations as needed.
 
## Program:
```
int queue[50], rear, front,i; void display()
{
if(front==-1)
{
printf("No elements to display");
}
else
{
for(i=front;i<=rear;i++)
{
printf("%d ",queue[i]);
}
}
}
```
## Output:

![Screenshot 2025-04-26 203108](https://github.com/user-attachments/assets/20e93d98-d04d-4428-aa12-c7e4047f1c2e)


## Result:
Thus, the program to display queue elements using array is verified successfully.
 
## EXP NO:3D C PROGRAM TO INSERT ELEMENTS IN QUEUE USING ARRAY.
## Aim:
To write a C program to insert elements in queue using array.

## Algorithm:
1.	Declare global variables for the size, rear, front, and the queue itself.
2.	Define the enqueue function to add a float to the queue.
3.	Initialize the rear, front, and size of the queue as needed.
4.	Call the enqueue function as needed.

## Program:
```
int size=4, rear=-1, front=-1; float queue[50];
void enqueue(float data)
{
if(rear<size)
{
if(front==-1)
{
front=0;
}
rear=rear+1; queue[rear]=data;
}
}
```
## Output:

![Screenshot 2025-04-26 203125](https://github.com/user-attachments/assets/fd3544d2-f3fd-490c-b1bc-7fef0a9cb09c)

 
## Result:
Thus, the program to insert elements in queue using array is verified successfully.
 
## EXP NO:3E C FUNCTION TO DELETE ELEMENTS IN QUEUE USING ARRAY

## Aim:

To create a function in C that deletes an element from a queue implemented using an array.

## Algorithm:

1.	Check if the Queue is Empty
o	If the front pointer is -1, it means the queue is empty, and there are no elements to delete. Print a message indicating that the queue is empty.
2.	Delete the Front Element
o	If the queue is not empty, the element at the front index is deleted.
o	Increment the front pointer by 1 to remove the element and point to the next element in the queue.
3.	Check if the Queue Becomes Empty After Deletion:
o	After deletion, check if the front pointer has passed the rear pointer (front > rear). If this is true, reset both front and rear to -1, indicating that the queue is now empty.
4.	End the Function.


## Program:
```
int front, rear;
void dequeue()
{
    if(front==-1&&rear==-1)
    printf("Queue Underflow.");
    else if(front==rear)
    front=rear=-1;
    else{
        front=front+1;
    }
}
```
## Output:

 
![Screenshot 2025-04-26 203145](https://github.com/user-attachments/assets/01606e03-9769-45ba-82f4-c87a443d37be)


## Result:
Thus, the function that deletes an element from a queue implemented using an array is verified successfully.




