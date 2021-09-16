# Tang
#include <stdio.h>
#include <cs50.h>

//起始n個駱駝
//最後i個駱駝
//數量變化：每年增加n/3隻 減少n/4隻
//n需大於等於9 i需大於等於n
//求需幾年到達終點值

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
