# difference-btwn-time
struct time{
int s;
int m;
int h;
};
void diff(struct time t1,time t2, struct time *d);
int main()
{
struct time t1,t2,d;
scanf("%d %d %d,&t1.hours,&t1.min,t1.sec);
scanf("%d %d %d\n,&t2.hours,&t2.min,t2.sec);
diff(t1,t2,&d);
printf("%d:%d:%d",d.hours,d.min,d.sec);
}
diff(struct time t1,time t2, struct time *di)
{
if(t2.sec>t1.sec)
{
--ti.min;
t1.sec+=60;
}
di->sec=t1.sec-t2.sec;
if(t2.min>t1.min)
{
--t1.hours\
t1.min+=60;
}
di->min=t1.min-t2.min;
di->hours=t1.hours-t2.hours;
}
