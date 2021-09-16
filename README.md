# Tang
#include <stdio.h>
#include <cs50.h>

int main(void){
 int n;
 do
 {
     n = get_int ("Start size:");
 }
 while(n<9);

 int i;
 do
 {
     i = get_int ("End size:");
 }
 while(i<n);

 int x=(i-n)/((n/3)-(n/4));

 printf("years: %i", x);
}
