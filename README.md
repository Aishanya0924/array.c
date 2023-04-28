# array.c
#include <stdio.h>
#include <string.h>
int main(){
        int i=0;
        char str[20][10];
        char name[10];
        printf("Please enter 10 names \n");
        for(i=0; i<10;i++){
                printf("Enter name of person %d\n", i );
                scanf("%s",str[i]);
//              strcpy( str[i], name);
        }
        for (i=0; i< 10; i++ ){
                printf ("%s\n", str[i]);
        }

}
![image](https://user-images.githubusercontent.com/132048421/235104111-88a34d56-a5b1-4d3b-826f-ed3c6fb98fd6.png)
