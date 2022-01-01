#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int acc_count=1;
struct account
{
    int dob;
    long long int acc_num, aadhar_num;
    float balance;
    char name[100];
};
void init(struct account *accs)
{
    accs->dob=0;
    accs->acc_num=1010101010101010;
    accs->aadhar_num=0;
    accs->balance=10000000;
    strcpy(accs->name,"Bank");
}
void display()
{
    printf("Enter your choice of operation\n");
    printf("1. Open new account\n");
    printf("2. Make transaction\n");
    printf("3. Close existing account\n");
    printf("4. Modify account details\n");
    printf("5. Exit\n");
    printf("Choose your operation 1 to 5\n");
}
void menu()
{
    
    while(1)
    {
        int choice;
        display();
        scanf("%d",&choice);
        if(choice<1 || choice>5)
        {
            printf("Invalid choice\n");
        }
        else
        {
            /*switch(choice)
            {
                case 1:
                case 2:
                case 3:
                case 4:
                case 5:
            }*/
            break;
        }
    }
}
int main()
{
    struct account *accs;
    accs = (struct account *)calloc(acc_count, sizeof(struct account));
    init(accs);
    menu();
    return 0;
}
