# Data Analytics Project: Book Sales Analysis

### Overview:
This data analytics project aims to analyze book sales data from various perspectives using multiple datasets encompassing awards, checkout records, editions, publishers, ratings, series, and quarterly sales information. The project will delve into understanding book sales trends, popular genres, publisher performance, and the impact of awards and ratings on sales.

### Datasets:
1. Award Dataset: Contains information about awards received by books, including the award name and the year won.
2. Checkout Dataset: Provides data on book checkouts, including the book ID, checkout month, and the number of checkouts.
3. Edition Dataset: Includes details about book editions such as ISBN, format, publication date, pages, print run size, and price.
4. Publisher Dataset: Encompasses publisher information like ID, publishing house, location, year established, and marketing spend.
5. Rating Dataset: Consists of book ratings provided by reviewers along with reviewer and review IDs.
6. Series Dataset: Contains data about book series, including series ID, name, planned volumes, and book tour events.
7. Sales Q1-Q4 Datasets: Quarterly sales data comprising sale date, ISBN, discount, item ID, and order ID.

### Objectives:

1. Sales Trend Analysis: Analyze quarterly sales data to identify trends, seasonality, and overall sales performance.
2. Genre and Format Analysis: Determine popular book genres and formats based on sales and checkout patterns.
3. Publisher Performance: Evaluate publisher performance based on sales, marketing spend, and the number of editions published.
4. Impact of Awards and Ratings: Assess the impact of awards and ratings on book sales and popularity.
5. Series Analysis: Explore the success and reception of book series based on sales, planned volumes, and book tour events.

### Award Dataset

**Title:** Award Dataset
**Features:**
- **Award Name:** Name of the award received by the entity.
- **Year Won:** Year in which the award was won.

### Checkout Dataset

**Title:** Checkout Dataset
**Features:**
- **BookID:** Unique identifier for the book.
- **CheckoutMonth:** Month in which the book was checked out.
- **Number of Checkouts:** Total number of times the book was checked out.

### Edition Dataset
**Title:** Edition Dataset
**Features:**
- **ISBN:** International Standard Book Number for the book edition.
- **BookID:** Unique identifier for the book.
- **Format:** Format of the book (e.g., paperback, hardcover).
- **PubID:** Publisher ID associated with the edition.
- **Publication Date:** Date of publication.
- **Pages:** Number of pages in the book.
- **Print Run Size (k):** Print run size in thousands.
- **Price:** Price of the book.

### Publisher Dataset
**Title:** Publisher Dataset
**Features:**
- **PubID:** Publisher ID.
- **Publishing House:** Name of the publishing house.
- **City:** City where the publishing house is located.
- **State:** State where the publishing house is located.
- **Country:** Country where the publishing house is located.
- **Year Established:** Year the publishing house was established.
- **Marketing Spend:** Amount spent on marketing by the publishing house.

### Rating Dataset
**Title:** Rating Dataset
**Features:**
- **BookID:** Unique identifier for the book.
- **Rating:** Rating given to the book.
- **ReviewerID:** Unique identifier for the reviewer.
- **ReviewID:** Unique identifier for the review.

### Series Dataset
**Title:** Series Dataset
**Features:**
**SeriesID:** Unique identifier for the series.
**Series Name:** Name of the book series.
**Planned Volumes:** Number of volumes planned for the series.
**Book Tour Events:** Number of book tour events associated with the series.

### Sales Q1-Q4 Datasets
**Title:** Sales Dataset (Quarterly)
**Features:**
- **Sale Date:** Date of the sale.
- **ISBN:** International Standard Book Number for the sold book.
- **Discount:** Discount applied to the sale.
- **ItemID:** Unique identifier for the item sold.
- **OrderID:** Unique identifier for the order.
