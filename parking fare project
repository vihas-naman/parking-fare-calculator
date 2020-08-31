
#include<stdio.h>
int main()
{
int enthr,entmin,exhour,exmin,tothour,totmin,acthour,actmin;
float fare;
char type;
printf(“Enter type of vehicle c=car,b=bus,truck”);
scanf(“%c”,&type);
for(;;)
{
if(type=='t'|| type=='c'|| type=='b');
{
printf("please enter the correct value c=car,b=bus,truck");
scanf("%c",&type);
}
else
break;
}
printf("enter entry hour");
scanf("%d",&enthour);
for(;;)
{
if(enthour<24)
break;
else
{
printf("enter the correct hour");
scanf("%d",&enthour);
}
}
printf("enter entry minute")
scanf("%d",&entmin);
for(;;)
{
if(entmin<60)
break;
else
{
printf("enter the correct minute");
scanf("%d",&entmin);
}
}
printf("enter exit hour");
scanf("%d",&exhour);
for(;;)
{
if(exhour<24)
break;
else
{
printf("enter the correct hour");
scanf("%d",&exhour);
}
}
printf("enter exit minute")
scanf("%d",&exmin);
for(;;)
{
if(exmin<60)
break;
else
{
printf("enter the correct minute");
scanf("%d",&exmin);
}
}
if(exhour<enthour)
exhour+=24;
acthour=exhour-enthour;
acthour=tothour;
actmin=entmin-exmin;
if(totmin>0)
tothour=acthour+1;
else
tothour=acthour;
if(actmin<0)
{
acthour=acthour-1;
actmin=actmin+60;
}
printf("Type of vehicle:");
if(type=='c')
{
if(tothour<=3)
fare=0;
else
fare=(tothour-3)*1.5;
}
if(type=='b')
{
if(tothour<=2)
fare=tothour*1;
else
fare=((tothour-2)*2.3)+2;
}
else
{
if(tothour<=1)
fare=2
else
fare=((tothour-2)*3.7)+2;
}
printf("Type of vehicle");
if(type=='c')
printf("Car\n");
if(type=='b')
printf("Bus\n");
else
printf("Truck\n");
printf("TIME IN \t %d:%d\n",enthour,entmin);
printf("TIME OUT \t %d:%d\n",exhour,exmin);
printf("\t\t-------");
printf("PARKING TIME \t %d:%d\n",acthour,actmin);
printf("ROUNDED TOTAL \t %d",tothour);
printf("\t\t--------\n");
printf("TOTAL CHARGE \t $%f",fare);
}