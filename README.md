# Stack-Code
Code for PUSH,POP,PEEP AND DISPLAY USING SWITCH CASE
#include<stdio.h>

#define MAX 50
int stack [MAX]
int max = MAX;
int top = -1;

void push(){
int data; 
printf("Enter data\n");
scanf("%d",&data);
if(top == max-1){
printf("Overflow");
}
else{
top++;
stack[top]=data;
}
}
