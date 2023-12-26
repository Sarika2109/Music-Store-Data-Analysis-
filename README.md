# Music Store Data Aalysis

## Table of Contents-

- [Project Objective](#project-objective)
- [Project Overview](#project-overview)
- [Data sources](#data-sources)
- [Analysis](#analysis)
- [Results](#results)

### Project Objective-

To understand the business insights by using data analysis technique such as SQL queries and help the store to understand its business growth by answering questions. 

### Project Overview-

In this data analysis project we use music playlist database. To analyze and examine the music store database we have used  different SQL queries- to find out countries having most invoices, most popular genre of each country, the artist who written the most rock music, etc.It helps the store owner to understand its business insights.

### Data Sources-

Store Sales Data: The primary dataset used for this analysis is the "Sales_data.csv" file, containing detailed information about each sale made by the store. 

### Tools-

- Excel - Data Cleaning
- PostgreSQL - Data Analysis

 ### Data Cleaning/ Preparation-

In the initial data preparation phase, we performed following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.
 
 ### Exploratory Data Analysis-

  EDA involved exploring the sales data to answer key questions, such as-

- Who is the senior most employee based on job title?
- Which countries have the most Invoices? 
- What are top 3 values of total invoice? 
- Which city has the best customers? We would like to throw a promoƟonal Music Festival in the city we made the most money. Write a query that returns one city that has the highest sum of invoice totals. Return 
  both the city name & sum of all invoice totals.  
- Who is the best customer? The customer who has spent the most money will be declared the best customer. Write a query that returns the person who has spent the most money.
- Write query to return the email, ﬁrst name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A.  
- Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the top 10 rock bands. 
- Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed ﬁrst.
- Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent.  
- We want to ﬁnd out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. Write a query that returns each country along with the 
  top Genre. For countries where the maximum number of purchases is shared return all Genres.  
- Write a query that determines the customer that has spent the most on music for each country. Write a query that returns the country along with the top customer and how much they spent. For countries where the 
  top amount spent is shared, provide all customers who spent this amount.

### Data Analysis-

  Include some interesting codes-

  ```sql
  SELECT * FROM from employee

 ````

 ### Results- 

 The analysis results are summarized as follows:
 
  - Most invoice countries are: USA, Canada, Brazil
  - Prague city has best customer with high invoice total.
  - R.Madhav is the best customer with spent highest money, etc.
   

   

    

    

   

   - 
    
