# guess_no.c
 #include<stdio.h>
  int main()
  {

int a ;
char b,c ;
char d;
printf("Take any number in your mind(1 to 100)\n\n");



printf("Then multiply you number to same number you have chosen in your mind.  \n\n");
printf(" \nThen ans. give name (A) for example  you take number (11 then multiply 11*11=121 =A ) like this if you done just type Ok\n\n");
scanf("%c %c",&b ,&c);


printf("\nThen by subtracting 1 from the number held in mind or you chosen in your mind at starting.eg (11-1) like this  .\n\n" );
 

printf("Then multiply same number you get from subtracting 1 (for example you get 10 then 10*10 = 100 =B)like this and ans.give name (B) \n\n");
printf("then subtract the value of A-B the tell us remaining value for eg,( A-B = 121 -100) like this\n\n");


scanf ("%d", &a);
printf("the value is you chose in your mind we got  %d\n",a/2);

printf("we find your value in your mind the value  \n");

  return 0;
  }
