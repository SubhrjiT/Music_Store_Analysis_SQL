Here's an updated README reflecting the use of **PostgreSQL** and **PgAdmin4**:

---

# Music Store Analysis with SQL

Welcome to the **Music Store Analysis** project! This project leverages PostgreSQL and PgAdmin4 to analyze a fictional music store's dataset. The analysis is focused on understanding customer behavior, identifying top genres and artists, and exploring sales trends to assist in strategic business decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Key Questions Answered](#key-questions-answered)
- [Tech Stack](#tech-stack)
- [Analysis](#analysis)
- [How to Use](#how-to-use)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project involves analyzing a music store's database using SQL queries within PostgreSQL, managed through the PgAdmin4 interface. The goal is to extract insights regarding customers, purchases, music genres, and artists, organized into three levels of difficulty: Easy, Moderate, and Advanced.

## Dataset Description

The dataset consists of several tables, including:

- **customers**: Information about customers.
- **invoices**: Details of customer invoices.
- **tracks**: List of tracks available in the store.
- **albums**: Albums containing the tracks.
- **artists**: Artists of the albums.
- **genres**: Different music genres available in the store.

The data provides a thorough overview of purchase patterns, sales data, and customer preferences.

## Key Questions Answered

### Question Set 1 - Easy
1. Who is the senior-most employee based on job title?
2. Which countries have the most invoices?
3. What are the top 3 values of total invoice amounts?
4. Which city has the best customers? Identify the city with the highest sum of invoice totals, suitable for a promotional music festival.
5. Who is the best customer in terms of total spending?

### Question Set 2 - Moderate
1. Identify all Rock Music listeners, including their email, first name, last name, and genre.
2. List the top 10 artists who have written the most rock music.
3. Find tracks that are longer than the average song length and list them by name and duration.

### Question Set 3 - Advanced
1. Determine how much each customer has spent on specific artists.
2. Identify the most popular music genre in each country based on purchases.
3. Find the top customer in each country based on spending.


## Tech Stack

- **SQL**: Utilized for data analysis and manipulation.
- **PostgreSQL**: Database system for hosting the music store dataset.
- **PgAdmin4**: A GUI tool used for interacting with the PostgreSQL database.

- Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)

## Analysis

The analysis is performed using SQL queries within PostgreSQL, managed through PgAdmin4. Each query answers a specific business question, categorized by difficulty level. The query scripts are organized in the `queries` folder.

## How to Use

1. Clone the repository:
   
   ```bash
   git clone https://github.com/SubhrjiT/Music_Store_Analysis_SQL.git
   ```
   
2. Navigate to the project folder:
   
   ```bash
   cd Music_Store_Analysis_SQL
   ```
   
3. Load the dataset into PostgreSQL using PgAdmin4:
   
   - Open PgAdmin4 and create a new database for the music store data.
   - Use the SQL scripts in the `setup` folder to create tables and import data.

4. Execute the SQL scripts in the `queries` folder through PgAdmin4 to perform the analysis.

## Insights

Below are some key insights derived from the analysis:

- **Top Customers**: Identification of top spenders and their favorite genres.
- **Genre Trends**: Popular music genres by country and region.
- **Artist Performance**: Highlighting top artists based on track popularity and sales.
- **Sales Patterns**: Understanding purchasing trends and customer behavior.

For detailed findings, refer to the `analysis_report.md` file in the repository.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or improvements, feel free to submit an issue or create a pull request. 

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [SubhrjiT](https://github.com/SubhrjiT)
- **Portfolio**: [subhrjit.github.io](https://subhrjit.github.io/Portfolio-Website/)

---

Feel free to tweak any details or add specific instructions based on your setup!
