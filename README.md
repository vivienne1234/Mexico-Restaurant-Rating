# Mexico-Restaurant-Rating

![Image](https://github.com/user-attachments/assets/116548c9-7f10-440c-9cd2-de9427e13061)



## Table of Content

- Introduction
- Data collection and extraction
- Data cleaning and Transformation
- Data modelling
- Business Questions and Analysis
- Dashboard
- Recommendations
  
  

## Introduction

This data set is called the restaurant rating dataset which contains information about restaurants in mexico. A customer survey was carried out in this city in 2012 to collate information about each restaurant, their cuisines, information about their consumers and the preferences of the consumers. 



## Data Collection and Extraction 

The dataset was provided  as a compressed ZIP folder containing embedded tables. After extracting the folder, the data was imported into Power BI through Power Query using the "Folder" data connector. Within Power Query, I removed unnecessary columns and extracted each table from the binary format it was embedded in. To access the table content, I added a custom column using the “Csv.Document” function, which allowed me to parse and transform the raw CSV files into readable tables. This setup enabled centralized, dynamic data loading into Power BI for further transformation and modeling.



## Data Cleaning and Transformation

After extracting the dataset, the main table was expanded and duplicated into five separate queries. Each of these queries was filtered and transformed into distinct tables, including customers, restaurants, and others. The columns were cleaned and standardized, data types were correctly set, age groups were categorized, and the overall restaurant ratings were grouped into three satisfaction categories: Unsatisfactory, Satisfactory, and Highly Satisfactory. Missing values in some of the columns of the consumer table was filled with the most common value. These steps ensured the data was ready for accurate analysis and modeling in Power BI.



## Data Modelling

After cleaning the tables, I moved into data modeling. Using Power BI’s data model view, I defined relationships between the fact and dimension tables using primary and secondary keys. 



## Business Questions and Analysis

- Question 1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings? 
- Question 2. What are the consumer demographics? Does this indicate a bias in the data sample? 
- Question 3. Are there any demand & supply gaps that you can exploit in the market? 
- Question 4. If you were to invest in a restaurant, which characteristics would you be looking for?



### Question 1

What can you learn from the highest rated restaurants? 

An analysis of the top four highest-rated restaurants — Tortas Locas Hipocampo, Cafetería y Restaurante El Pacífico, Puesto de Tacos, and La Cantina Restaurante , reveals a consistent pattern. Each of these establishments specializes in just one or two distinct cuisines. Interestingly, these cuisines, including Mexican, Bar, Cafeteria, Brewery, and Fast Food, also emerged as the most highly rated across the entire dataset. This suggests that restaurants focusing on a clear culinary identity tend to perform better in customer satisfaction.

<img width="145" height="249" alt="Image" src="https://github.com/user-attachments/assets/32e04bd7-0dd8-4cab-85c2-e24bba682f7b" />
<img width="634" height="265" alt="Image" src="https://github.com/user-attachments/assets/47a91f81-facf-41b5-bbca-a38fe9599d1e" />

Do consumer preferences have an effect on ratings?

Mexican cuisine stands out as the most preferred option, with 97 consumers selecting it, far surpassing all other cuisines. This is followed by American cuisine with 11 consumers, and then Cafeteria and Pizzeria with 9 preferences each. The dominance of Mexican cuisine reflects a strong local taste among the surveyed consumers, which may explain why top-rated restaurants, such as Tortas Locas Hipocampo, consistently offer this cuisine. This strong alignment between preference and satisfaction highlights the importance of cultural relevance in menu offerings.

<img width="819" height="245" alt="Image" src="https://github.com/user-attachments/assets/b4a7e79f-f321-4f2a-88e1-6f51dedf9095" />



### Question 2

What are the consumer demographics? Does this indicate a bias in the data sample? 

The dataset reveals that a significant portion of respondents are young adults between the ages of 18 and 27, with the majority being students and single. This suggests a possible demographic bias toward younger, single individuals in the sample. As a result, the findings, particularly in terms of cuisine preferences and restaurant ratings, may be more reflective of this group's tastes and experiences, potentially limiting the generalizability of the results to older or more diverse consumer segments.

<img width="821" height="225" alt="Image" src="https://github.com/user-attachments/assets/7e959396-0939-42b6-902b-abff6deb9078" />

### Question 3

Are there any demand & supply gaps that you can exploit in the market? 

The data highlights multiple opportunities where demand exceeds current supply. A significant portion of consumers prefer restaurants with no alcohol service (57.59%) and non-smoking environments (72.56%), yet only a portion of restaurants fully meet these preferences. This points to a gap for clean, family-friendly dining spaces that align with health-conscious and cultural expectations.

<img width="387" height="265" alt="Image" src="https://github.com/user-attachments/assets/51edd12e-4e3b-416d-b343-aaaa12f53259" />
<img width="409" height="234" alt="Image" src="https://github.com/user-attachments/assets/e5d83db7-76d6-4f13-b932-afbc2c0d7830" />

Additionally, Mexican cuisine shows consistent demand across all budget ranges, especially in the medium segment. However, affordable restaurants with high ratings  such as Tortas Locas Hipocampo and Puesto de Tacos, are relatively few. This indicates a strong market gap for high-quality, low-to-mid-priced dining options.
There is also modest but unmet demand for cuisines like American, Cafeteria, and Pizzeria, particularly in the mid-budget category, where consumer interest is visible, but the number of high-rated options is limited.

<img width="3848" height="1208" alt="Image" src="https://github.com/user-attachments/assets/ebafe9ab-97ea-4e22-ae69-8af3c7d5587a" />

Together, these findings suggest untapped opportunities in offering high-quality, culturally aligned, and affordable food experiences, especially in environments that prioritize health, ambiance, and service.



### Question 4

If you were to invest in a restaurant, which characteristics would you be looking for?

- Alcohol Service
  
Restaurants with a none alcohol bar tend to receive higher service ratings, suggesting that offering a non-alcoholic bar attract a broader clientele and enhance the overall dining experience.

- Smoking Policy
  
Investing in a non-smoking environment aligns with both majority consumer preferences (72.56%) and public health trends, making it a favorable and sustainable choice.

- Cuisine Type
  
Mexican cuisine shows the highest consumer preference across all budgets. However, restaurants can stand out by offering a modern twist on traditional recipes or emphasizing premium ingredients for added value.

- Price Point
  
The medium price range caters to the largest market segment and provides room for balancing affordability with profitability. High-rated, medium-priced restaurants like Tortas Locas Hipocampo demonstrate this opportunity clearly.
 
- Location Strategy
  
Targeting cities like San Luis Potosi  with higher overall restaurant ratings can improve the odds of success by leveraging existing consumer satisfaction trends and local demand.
 


### Conclusion
Focusing on these characteristics creates a data-driven blueprint for building a restaurant that resonates with consumer preferences, stands out in the market, and offers strong investment potential.





### Dashboard

<img width="608" height="341" alt="Image" src="https://github.com/user-attachments/assets/b17e5620-3ad5-4a5f-8c60-f9854cb4c908" />



### Recommendation

Based on the data analysis, consumer preferences, and market gaps identified from the chart insights, the following strategic recommendations are proposed to guide restaurant investment decisions and operational priorities.

#### Key Recommendations

- Focus on High-Demand Cuisines
 
Prioritize Mexican cuisine, which dominates consumer preferences and correlates strongly with high restaurant ratings. Consider adding a unique culinary twist to stand out in a competitive space.

- Target the Medium Price Range

Most top-rated restaurants operate within the medium pricing tier. This range offers the best balance between affordability for consumers and profitability for investors.
- Choose Non-Smoking, Non-Alcohol Friendly Environments

Restaurants that do not allow smoking and none alcohol services tend to receive higher service ratings. This combination appeals to health-conscious and experience-driven customers.








