# prime-number-identifier-
int main()
{
int x,i ;
printf("enter x : ");
scanf("%d", &x);
if (x<=1){
    printf("not prime");
    return 0;
}
for (i=2;i<=x-1;i++){
 if (x%i==0){
    printf("not prime");
    break;
    return 0;
 }
 else{
     printf("prime");
     break;
 }
}
  return 0;
} 
