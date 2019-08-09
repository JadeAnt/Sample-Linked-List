#include <stdio.h>
#include <stdlib.h>

struct Node{
  int data;
  struct Node* next;
};

struct Node* head;

Node* Insert(Node* head, int x){
  struct Node* temp = (struct Node*)malloc(sizeof(struct Node*));
  
  temp -> data = x;
  temp -> next = NULL;
  
  if(head != NULL){
    temp -> next = head;
    head = temp;
  }
  
  return head;
}  

void Print(Node* head){
  printf("List is: ");
  while(head != NULL){
    printf("%d ", head -> data);
  }
  print("\n");
}

int main(){
  Node* head = NULL;
  int n, i, x;
  printf("How many numbers?: ");
  scanf("%d", &n);
  
  for(i = 0; i < n; i++){
    printf("Input the numbers: ");
    scanf("%d", &x);
    head = Insert(head, x);
    Print(head);
  }
}//main
 
