# Contoso Sales Analysis 


## Summary

Contoso is a fictional global manufacturing company created by Microsoft which has a lot of sample data to which they use to demonstrate various aspects of their product like Microsft 365 and PowerBi.

This dashboard aims to summarize profit, revenue, COGS, and profit margin from year 2007- 2009 from different channels. The dashboard aims to give brief insight to managment regarding the sales for the current year (which ever is filtered), while also comparing to previuous years data. 

# Database

The database I have used here was downloaded from https://www.microsoft.com/en-us/download/details.aspx?id=18279.

# Loading Contoso Database

## Restoring to SQL Sever Management Studio

After downloading and extracting the ContosoRetailsDW.bak file, I restored the database in Microsoft SQL Server Management Studio (SSQL). . I then directly loaded the Database in PowerBI through SQL server. 

Take note of the Server where you created your database, you'll need it later when you're loading in PowerBi.

![Servername](https://github.com/user-attachments/assets/5e9091c8-8ac8-47e1-b85a-f70e1ef3c11d)

![SSMS](https://github.com/user-attachments/assets/fdfa8759-3a64-437e-b8ba-962358d0d13e)

## Restoring in PostgreSQL

I then loaded it to PostgreSQL, this is for future activities in case I want to play around more using PostgreSQL.

Create your Database in PostgreSQL then restore the .bak file inside the database you created.

![PostgreSQL](https://github.com/user-attachments/assets/ab97fc4f-b40f-4009-9a0a-e76077a3ab8c)


## Get data in PowerBi through SQL Server

Click Get data through SQL Server, type in your SQL Server that you took note before, and type in the name of your database. Use your credentials, the same one you are using on your SQL Server. 

Once you get throught, select all the tables that you want to use.

Once you loaded your table, then you can start exploring the data. 

![PowerBI](https://github.com/user-attachments/assets/97acb545-3c99-4c26-aaec-f0644973287e)


# Appendix

# Appenxid A - Dashboard Snapshot

For visualizing the Dashboard without downloading the file

![image](https://github.com/user-attachments/assets/65460385-925b-4b16-bd29-6159dfe16806)

# Appenxid B - Resources 

Below are some links that I used to start and reffered to complete this project:

1. https://data-goblins.com/power-bi/sql-dataset
2. https://www.youtube.com/watch?v=1eOYUZynxt8&t=644s
3. https://www.youtube.com/watch?v=v6fP8gyCLLc&t=619s
4. https://www.youtube.com/watch?v=e5mvoKuV3xs
5. https://youtu.be/iE04kCdkOaw?si=gL1p6rKYY3hc5xuq
6. https://www.bairesdev.com/tools/ai-colors

