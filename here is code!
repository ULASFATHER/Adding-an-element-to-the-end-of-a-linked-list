#include <stdio.h>
#include <stdlib.h>


struct node{
    int data;
    struct node *next;
};

struct node* start = NULL;
struct node* temp = NULL;
struct node* q = NULL;

int addLast(int data1){
    
    struct node* eklenecekveri = (struct node*)malloc(sizeof(struct node));
    eklenecekveri-> data = data1;
    eklenecekveri->next = NULL;
    
    if(start == NULL)
    {
        start = eklenecekveri;
    }
    else
    {
        q = start;
        
        while(q->next !=NULL){
            q = q->next;
        }
        q->next = eklenecekveri;
    }
    
}

void print(){
    q = start;
    while(q->next !=NULL){
        printf("%d\n",q->data);
        q = q->next;
    }
    printf("%d",q->data);
}







int main(){
    
    while(1==1){
        int num;
        printf("          please type a number:");
        scanf("%d",&num);
        addLast(num);
        print();
        
    }
    
    
    
    return 0;
    
    
}
