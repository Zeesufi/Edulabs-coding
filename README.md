# Edulabs-coding
Write a code to check two accepted numbers are amicable or not.
public class amicable {
public static void main(String args[]){
Scanner in = new Scanner(System.in);
System.out.println("The first number");
int num1= in.nextInt();
System.out.println("The Second number");
int num2= in.nextInt();
int Sum_num1=0;
int Sum_num2=0;
 for (int i=1;i<=num1;i++){
if(num1 % i ==0)
{Sum_num1 +=i;}}
for(int i =1;i<=num2;i++){
if (num2 % i ==0){Sum_num2 +=i;}}
if(Sum_num1==Sum_num2){System.out.println("number are amicable");}
else{System.out.println("numberr are not ammicable");}}}



Write the queries for implementing the following functions

a) MAX
b) MIN
c) AVG
d) COUNT
e) SUM
SELECT MAX(COLUMB_NAME) FROM TABLE_NAME:
SELECT MIN(COLUMB_NAME) FROM TABLE_NAME:
SELECT AVG(COLUMB_NAME) FROM TABLE_NAME:
SELECT COUNT(COLUMB_NAME) FROM TABLE_NAME:
SELECT SUM(COLUMB_NAME) FROM TABLE_NAME;

que 8
Select * from Employee;
Select EMPNO,SALARY from Empolyee;
select avg(SALARY) from Employee;
select count(EMPNO) from Employee;
select count(EMPNO) from Employee  where distinct(DOJ) ;
select sum(SALARY),count(EMP_NAME) from Employee where group by EMP_NAME;
Select SALARY from Employee where SALARY>120000;
select EMP_NAME from Employee order by EMP_NAME desc;
select * from Employee where EMP_NAME=Amit and SALARY>50000;

Write code for reverse string
public class Dublicate
{ public static void main(String args[]){
String a = "altu";
int b = a.lenth();
for(int i=b-1;i>=0;i--){
System.out.print(a.charAt(i);}}}
