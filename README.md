# EnrichBookCrossing
In this repository, we are working on enriching the Book-Crossing dataset with author information. 

Book-Crossing is a commonly used dataset for recommendation, created in 2004 by crawling the website of Book-Crossing for four weeks. Book-Crossing is an international book exchange community whose members can leave books anywhere in the world and indicate their location to other users. The users can then update their profile with the information that they read a new book, and also submit a rating from 1 to 10. 

The dataset consists of three subsets: book ratings, users, and items. In this repository, we are using external sources to enrich it with additional author information when publicly available. The following graph roughly depicts the process.
![FAccTRec drawio](https://user-images.githubusercontent.com/43424135/183620872-64a1ef40-2b38-4536-9cee-a6cf2b02dbc2.png)

The process of linking the dataset to external sources in order to enrich it with author information is performed in notebook A. 
The following data sources are used:

1. [Google Books](https://books.google.com/)
2. [VIAF](https://viaf.org)
3. [WikiData](https://wikidata.org)


In notebook B, we are analyzing the resulting dataset.


