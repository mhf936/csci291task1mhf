#include<stdio.h>
int main(){
int x;
int y;
int d;
float z;
float e;
float valueneeded;
while(1){
printf("1. Purchase item  \n 2. admin mode \n 3. Exit");
printf("\nplease choose an option:");
scanf("%8d",&x);
if(x==1){
printf("\n value  product name  cost\n 1.  A  1.0dhs\n 2.  B  0.5dhs\n 3.  C  0.25dhs");
printf("please choose an option: ");
scanf("%8d",&y);
if (y==0){
continue;}
if (y==1){
printf("the item you are purchasing is A and the amount you need to enter is 1.0dhs are you sure of this purchase please confirm");
printf("if yes please input 1 if no please input 0: ");
scanf("%8d",&d);}
if (d==0);
continue;
if (d==1);
z=1;
printf("please pay a value of 1.0 dhs (pay one at a time please)");
printf("value inputted");
scanf("%f",&e);
do
valueneeded=z-e;
if (valueneeded==0);
if(y==2)
printf("the item you are purchasing is B and the amount you need to enter is 0.5 dhs are you sure of this purchase please confirm");
if(y==3)
printf("the item you are purchasing is C and the amount you need to enter is 0.25 dhs are you sure of this purchase please confirm");

   
}
    


if (x==3)

break;}

