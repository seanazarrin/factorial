//factorial
#include <stdio.h>


int main(void) {
    
    int i;
    int n;
    unsigned long long fac = 1;
   
    
    printf("enter the factorial\n");
    
    scanf("%d",&n);
    
    if(n==0){
             printf("the value of the factorial is 1.");
    } else {
	        for(i=1; i<= n; i++){
	        fac*=i;
            }
      }
	printf("factorial is=%llu",fac);
	return 0;
}
