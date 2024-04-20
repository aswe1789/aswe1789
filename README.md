 #include<stdio.h>
 int park()
{static int sum=3625;
sum=sum+1;
printf("进入一辆车，此时车位剩:%d个\n",sum);
}
int main()
park ();
park ();
park ();
park ();
park ();
