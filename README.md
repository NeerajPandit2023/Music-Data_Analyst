# Music-Data_Analyst
This SQL music project consists of several queries that analyze various aspects of a music database. Let's go through each query and provide a brief description:

Q1: Who is the senior most employee based on job title?
   - This query retrieves the employee record with the highest "levels" value, which represents seniority based on job title.

Q2: Which countries have the most invoices?
   - This query groups invoices by billing country and counts the number of invoices for each country, displaying the countries with the highest invoice counts.

Q3: What are the top 3 values of total invoice?
   - This query retrieves the top three values of the "total" column from the invoice table, ordered in descending order.

Q4: Which city has the best customers? 
   - This query calculates the total invoice amount for each billing city and returns the city with the highest sum of invoice totals.

Q5: Who is the best customer?
   - This query identifies the customer who has spent the most money by summing the total amount spent for each customer and returning the customer with the highest sum.

Moderate:

Q1: List email, first name, last name, and genre of all rock music listeners.
   - This query retrieves the distinct email, first name, and last name of customers who have purchased rock music, sorted alphabetically by email.

Q2: Top 10 rock music artists based on the number of songs they have written.
   - This query joins multiple tables to calculate the count of rock songs for each artist and returns the top 10 artists with the highest song counts.

Q3: Return track names and milliseconds of tracks longer than the average song length, sorted in descending order of song length.
   - This query compares the milliseconds of each track with the average track length and retrieves the track names and milliseconds of tracks that exceed the average, sorted in descending order of song length.

Advance:

Q1: Amount spent by each customer on the best-selling artist.
   - This query identifies the best-selling artist based on total sales and then calculates the amount spent by each customer on that artist. It returns the customer name, artist name, and total spent for each customer-artist combination.

Q2: Most popular music genre for each country.
   - This query determines the most popular genre for each country by counting the number of purchases for each genre and country. It returns the country along with the top genre, considering cases where the maximum number of purchases is shared.

Q3: Customer who has spent the most on music for each country.
   - This query identifies the customer who has spent the most on music for each country by summing the total amount spent for each customer and country. It returns the country, top customer, and the amount they spent, considering cases where the top amount spent is shared.

Each query contributes to the analysis of the music database, providing insights into employee seniority, invoice distribution, top customers, popular genres, and customer spending patterns.
