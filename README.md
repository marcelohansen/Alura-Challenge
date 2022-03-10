# Alura Challenge BI

[Alura](https://www.alura.com.br/) has a challenge modality, the Alura Challenge, which encourages the development of skills in case studies similar to those existing in the job market. In its second edition, the Business Intelligence challenge is carried out in four weeks and three projects with different levels of complexity are created. For the resolution, BI concepts and techniques are applied to develop dashboards to assist the decision making of fictitious companies.

- [Week 1](https://github.com/marcelohansen/Alura-Challenge-BI#clapper-week-1-alura-films): Alura Films needs to analyze IMDb data for a new production
- [Week 2](https://github.com/marcelohansen/Alura-Challenge-BI/#plate_with_cutlery-week-2-alura-foods): Alura Foods wants to analyze Indian restaurant market
- [Week 3](https://github.com/marcelohansen/Alura-Challenge-BI/#icecream-week-3-alura-skimo): Alura Skimo needs to analyze its sales metrics.

&nbsp;
&nbsp;
   
## 🎬 Week 1: Alura Films
In this challenge, Alura Films wants to make a new production. There was analyzed data from Genre, Gross, Stars and Directors and Rating (IMDb and Metacritic).

Take a look at this dashboard created in Power BI: https://bit.ly/3JJcfLP

&nbsp;
&nbsp;

🟢 Here we can take a look at the top rated movie and appearances by the star and director. Also, gross revenue information (total and average per year) and most common genres. At the top, there are buttons for navigating through the dashboard pages.

![image](https://user-images.githubusercontent.com/98857817/156354623-38ead1e4-1bd8-432c-8cd0-b18b0624be57.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🟢🟢 The second page shows more metrics about the movies, such as Top Voted and Top Rated on IMDb, releases by year and gross revenue by genre. There are also some filters to refine the selection.

![image](https://user-images.githubusercontent.com/98857817/156372678-fda7b2f8-b5d7-4748-9c1f-7dd87c6bad65.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🟢🟢🟢 On this page there is information about the Stars and the Movies Directors. There is search and filter tools to choose a Star and/or Director by name or in a list.

![image](https://user-images.githubusercontent.com/98857817/156376444-ee444ac7-7291-43ba-bf88-23e9189fc7f5.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🟢🟢🟢🟢 The last page allows to make some combinations of filters and searches. Results are displayed on cards with important information and a table.

![image](https://user-images.githubusercontent.com/98857817/156377654-63a666a6-39e4-49b8-bc96-8361a975a262.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🔶 Each visual about movies shows a custom tooltip with information from the movie. The IMDb and Metacritic rating are dynamic and can be displayed in three colors according to their value 🟩 🟧 🟥. The cover images of the films were inserted with the visual "Image Grid".

![image](https://user-images.githubusercontent.com/98857817/156380188-ee46debf-d033-41ef-bc33-e8e81d1c1bbe.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🔶 Two .csv files were used to import the data. The entire ETL process was done in Power Query using the main functions such as: renaming columns, splitting columns by delimiter, changing column types, merging columns and replacing values. Auxiliary queries were created to process Star and Gender information.

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## 🍽️ Week 2: Alura Foods

In this week, Alura Foods is looking for an opportunity to expand its restaurant business to India. Location and operation data of the restaurants were analyzed, such as country, city, coordinates, type of cuisine, price, rating, delivery and table booking.

The Power BI dashboard is available at: https://bit.ly/AlFoods

&nbsp;
&nbsp;

🟡 At the beginning, you can see the general numbers of restaurants in India. Quantity of restaurants, restaurants by city, average rating and cost (in four currencies), map with location, percentage with delivery and type of cuisine are displayed on this screen. On the left side there are buttons for navigating the dashboard pages.

![image](https://user-images.githubusercontent.com/98857817/156609939-711cdf2c-857c-46a7-9e7e-440727f8236d.png)


&nbsp;
&nbsp;
&nbsp;
&nbsp;

🟡🟡 In this part it's possible to see more information about the restaurants. On the right side are some filters to refine the parameters and improve the analysis. The results are shown by the best restaurants and cuisines. There are two donut charts to represent the rating and price range distribution.

![image](https://user-images.githubusercontent.com/98857817/156610020-82cab32f-dab3-491a-8b60-8b79b13c6538.png)


&nbsp;
&nbsp;
&nbsp;
&nbsp;

🟡🟡🟡 The last page allows to make some combinations of filters and searches. Results are displayed on cards with important information and a table.

![image](https://user-images.githubusercontent.com/98857817/156610369-95d647ba-851b-4198-8e5b-0b5b7e9598ee.png)


&nbsp;
&nbsp;
&nbsp;
&nbsp;

🔷 Each restaurant visual has a custom tooltip with more information about the place. The visual "Image Grid" was used to insert the illustrations of the restaurants.

![image](https://user-images.githubusercontent.com/98857817/156641736-95f510b2-54e1-45fd-be3f-1ff3eaf0abfc.png)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

🔷 The database was divided into five .json files. All files were connected by folder and the exchange rate is collected by an API. The ETL process was done in Power Query by expanding columns, changing column types, replacing values and deleting useless data. Two auxiliary queries were created to organize the data and work with the categories of cuisine.

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## 🍦 Week 3: Alura Skimo
Under construction

link: https://bit.ly/AluraSkimo

