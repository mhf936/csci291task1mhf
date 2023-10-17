#include<stdio.h>;
int main(){
    int x;
    int y;
    int d;
float valueneeded;
float e;
float change;
int z;
    while(1){
       printf("\n1. purchase item\n2. admin mode\n3. Exit");
       printf("\nplease choose an option: ");
       scanf("%8d",&x);
       if(x==1){printf("\n value  product name    cost\n 1.  A  1.0dhs\n 2.  B  0.5dhs\n 3.  C  0.25dhs");
printf("\nplease choose an option: ");
scanf("%8d",&y);
if(y==0){
continue;}
else if(y==1){
printf("\nthe item you are purchasing is A and the amount you need to enter is 1.0dhs are you sure of this purchase please confirm");
printf("\nif yes please input 1 if no please input 0: ");
scanf("%8d",&d);
if (d==1);{
valueneeded=1.0;
printf("please pay a value of 1.0 dhs (pay one at a time please 1.0dhs or 0.5dhs or 0.25dhs)");
printf("value inputted: ");
scanf("%8f",&e);
if(e==1.0 || e==0.5 || e==0.25){
do{
    valueneeded=valueneeded-e;
}while(valueneeded>0);
if (valueneeded<=0){
change=-valueneeded;
printf("the change is %8f",change);
    break;
}}
else
{
printf("you have inserted the wrong coin would you like to cancel this purchase? if so please press 1 if not please press 0");
scanf("%8d",&z);
if(z==1){
printf("please insert the right coin");
y==1;
}

else if(z==0){
x=1;}
}
}}
else if(y==2){
printf("\nthe item you are purchasing is B and the amount you need to enter is 0.5dhs are you sure of this purchase please confirm");
printf("\nif yes please input 1 if no please input 0: ");
scanf("%8d",&d);
if (d==1);{
valueneeded=0.5;
printf("please pay a value of 1.0 dhs (pay one at a time please 1.0dhs or 0.5dhs or 0.25dhs)");
printf("value inputted: ");
scanf("%8f",&e);
if(e==1.0 || e==0.5 || e==0.25){
do{
    valueneeded=valueneeded-e;
}while(valueneeded>0);
if (valueneeded<=0){
change=-valueneeded;
printf("the change is %8f",change);
    break;
}}
else
{
printf("you have inserted the wrong coin would you like to cancel this purchase? if so please press 1 if not please press 0");
scanf("%8d",&z);
if(z==1){
printf("please insert the right coin");
y==1;
}

else if(z==0){
x==1;}
}
}}
else if(y==3){
printf("\nthe item you are purchasing is C and the amount you need to enter is 0.25dhs are you sure of this purchase please confirm");
printf("\nif yes please input 1 if no please input 0: ");
scanf("%8d",&d);
if (d==1);{
valueneeded=0.25;
printf("please pay a value of 0.25 dhs (pay one at a time please 1.0dhs or 0.5dhs or 0.25dhs)");
printf("value inputted: ");
scanf("%8f",&e);
if(e==1.0 || e==0.5 || e==0.25){
do{
    valueneeded=valueneeded-e;
}while(valueneeded>0);
if (valueneeded<=0){
change=-valueneeded;
printf("the change is %8f",change);
    break;
}}
else
{
printf("you have inserted the wrong coin would you like to cancel this purchase? if so please press 1 if not please press 0");
scanf("%8d",&z);
if(z==1){
printf("please insert the right coin");
y==1;
}

else if(z==0){
x==1;}
}
}}
}}
 return 0;
}
