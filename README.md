// Online C compiler to run C program online
#include <stdio.h>

int main() {
   
   
   int price[0];
     float gst;
     
     printf("enter q1");
     scanf("%d",&price[0]);
      
     
      if(price[0]>0&&price[0]<=10000){
              for(int i=0;i<3;i++){
 printf("price after adding tax %d  %f\n",price[i], price[i]+(0.10+price[i]));
     }
      }
      
     else if(price[0]>=10001&&price[0]<=20000){
              for(int i=0;i<3;i++){
 printf("price after adding tax %d  %f\n",price[i], price[i]+(0.18+price[i]));
     }
      }
      
    else  if(price[0]>=20001&&price[0]<=30000){
              for(int i=0;i<3;i++){
 printf("price after adding tax %d  %f\n",price[i], price[i]+(0.20+price[i]));
     }
      }
      
     else if(price[0]>=30001&&price[0]<=40000){
              for(int i=0;i<3;i++){
 printf("price after adding tax %d  %f\n",price[i], price[i]+(0.30+price[i]));
     }
      }
      
    else  if(price[0]>40001&&price[0]<50000){
              for(int i=0;i<3;i++){
 printf("price after adding tax %d  %f\n",price[i], price[i]+(0.50+price[i]));
     }
      }
      

    return 0;
}
