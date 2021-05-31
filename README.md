# Basic_Emp_Detailes

  The Requirement is I have to Enroll the Employee Details like their name,age,sal,designation 
  and if any one want to view the deails of the emploees i have to mention display option and 
  if the management wants to increase the salary i have to increse the sal by 10% so that i have to give choice like RaiseSalary , 
  and finally exit
  
  CODE: 
  First i created a class 
        class EmpDetails{  
  we have to get the details from the user so that i used SCANNER class
        
        Scanner s = new Scanner(System.in);
   Later i used while loop for the continution process
        while{
   Then after i took if condition where if any want to exit it will to exit from the program 
      
      if(choices ==4)
       break;
   then i used SWITCH condition for to choices in 
       case 1 : i gave update the employee details 
       case 2 : i gave the choice of DISPLAY where u will get the updated employee details
       case 3 : i gave RAISESALARY where the management able to increse the salary 
      
      
   WORKING :  
   
   
   In this Program u allowed To Select among 4 choices like 1.create 2.display 3.Raise salary 4 .exit
   If u select 1 it will ask u to enter the details of the employee like 
       a . Enter Name 
       b.  Enter age
       c.  Enter salary 
       d.  Enter Designation 
   If u Select 2 it will display the details which u entered in the choice 1 
   If u select 3 it will 100 to the salary which u gave in choice 1
   If u select 4 it will exits to out 
   
   
   # StarTraingle.java
    
   The Requirement is that i have to print a STARTRIANGLE with the Help of user input

The first loop is for the number of Horizontal lines i.e

  for(int i=0;i<n;i++)
where as i used inner for loop to get spaces regarding the input number i.e

for(int j=0;j<n-i-1;j++)
{
	System.out.print(" ");
}
and then to print * i used another for loop

    for(int k=0;k<2*i+1;k++)
    {
	System.out.print("*");
}
this will continue in a line to break that line i used

 System.out.println();
 
 
 
  # Pyramid.java
  
My requirement is to print the Hollow Pyramid . so , that i took outer for loop to print the number of rows requires

    for(int i=0;i<n;i++)
    
 i have to print spaces(" ") in the traingle so that i took nested for loop
 
     for(int j=0;j<n-i-1;j++)
	{
		System.out.print(" ");
	}

i have to print hollow shape * pattern so that i used another nested for loop 

    for(int k=0;k<2*i+1;k++)
	{
		if((i==0)||(i==n-1))
		System.out.print("*");
		
		else
		{
			if((k==0)||(k==2*i))
			{
				System.out.print("*");
			}
			else
			System.out.print(" ");

		}
