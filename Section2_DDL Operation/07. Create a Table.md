# Create a Table

## Tables

![image-7-01](/images/image-7-01.png)

Go to IPSF 15 DB2 V10 operation menu.

![image-7-02](/images/image-7-02.png)

Use the option "1 SPUFI" to create SQL statements

![image-7-03](/images/image-7-03.png)

Here, we need to specify the INPUT DATA SET NAME and OUTPUT DATA SET NAME

![image-7-04](/images/image-7-04.png)

Go to ISPF 3.4 to chck the DB2 INPUT/OUOTPUT DATA SET NAME.

![image-7-05](/images/image-7-05.png)

Check the data set information of MATEKS.DB2.ISPUFI (Record format: **FB**)

![image-7-06](/images/image-7-06.png)

Output data set MATEKS.DB2.OSPUFI (Record format: **VB**)

![image-7-07](/images/image-7-07.png)

Replace the correct INPUT/OUTPUT DATA SET NAME

![image-7-08](/images/image-7-08.png)

Click *Enter*, then we can start to edit our SQL statements.

![image-7-09](/images/image-7-09.png)

![image-7-10](/images/image-7-10.png)

Code ";;;;" to exist and run the SQL statements

![image-7-11](/images/image-7-11.png)

Something wrong. We need to specify which database name and table space name to create our tables.(**DBMAT1.TSMATEKS**)

![image-7-12](/images/image-7-12.png)

The execution result.

![image-7-13](/images/image-7-13.png)

Then, we can comment out the statements that have already been executed. (comment out: --)

![image-7-14](/images/image-7-14.png)
