#include<stdio.h>
#include<string.h>
int main(){
    char password[]="1";
    char input[100];
    while(1){
    printf("Enter password:\n");
    fgets(input, sizeof(input), stdin);
    input[strcspn(input, "\n")] = 0;
     if(strcmp(password,input)==0){
        printf("Access granted!\n");
         break;
     }
     else if(strcmp(input, "-1")==0){
         printf("Exiting the Application.\n");
         break;
     }
     else{
         printf("Access denied.\n");
         printf("**To exit enter -1.**\n\n");
     }
     }
    return 0;
}
