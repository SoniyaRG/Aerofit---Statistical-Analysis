# Aerofit EDA
![aerofit](https://github.com/user-attachments/assets/6ec6909c-ed8d-4052-8c60-44a37abb4db3)

<br>

## Table Contents:<br>
* [Introduction to Aerofit]
* [About Dataset](https://github.com/SoniyaRG/Netflix_EDA/edit/main/README.md#about-dataset)
* [Python Libraries Used](https://github.com/SoniyaRG/Netflix_EDA/edit/main/README.md#python-libraries-used)
* [Project Workflow](https://github.com/SoniyaRG/Netflix_EDA/edit/main/README.md#project-workflow)
* [Insights and Recommendations](https://github.com/SoniyaRG/Netflix_EDA/edit/main/README.md#insights-and-recommendations)

### Introduction to Aerofit
Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product
range including machines such as treadmills, exercise bikes, gym equipment, and
fitness accessories to cater to the needs of all categories of people
### About Dataset
● Product: Product Purchased KP281, KP481, or KP781<br>
● Age: In years<br>
● Gender: Male/Female<br>
● Education: in years<br>
● MaritalStatus: single or partnered<br>
● Usage: average number of times the customer plans to use the treadmill each week<br>
● Income: annual income (in $)<br>
● Fitness: self-rated fitness on a 1-to-5 scale, where 1 is poor shape and 5 is the
excellent shape.<br>
● Miles: average number of miles the customer expects to walk/run each week<br><br>
Product Portfolio:<br>
● The KP281 is an entry-level treadmill that sells for $1,500.<br>
● The KP481 is for mid-level runners that sell for $1,750.<br>
● The KP781 treadmill has advanced features that sell for $2,500. <br>

### Python Libraries Used
* Pandas <br>
* NumPy  <br>
* Matplotlib.Pyplot  <br>
* Seaborn <br>

### Project Workflow
1.Importing Libraries <br>
2.Loading the Dataset <br>
3.Explore Dataset <br>
4.Data Cleaning and manipulate  <br>
5.Handling Outliers  <br>
6.Data Visualization <br>

### Insights and Recommendations
**Insights**
* Most of the customers are Male. The most sold product is KP281 ,which is typically entry-level treadmill  while KP781 is least sold product which is have advanced features.
* Most of the customer are between age range of 24 -33 . The minimum age of customer is 18 while maximum is 50.
* Most of the customer have 16 years of Education.
* For Age , Education , Usage ,  Fitness outliers are very few , While for Income and miles outliers are more than the rest.
* Same number of Males , Females buy the KP281 product while very few Female buy KP781 product . Average male , female buys KP481 product.
* Overall , most of the Partnered customer are interested in the products than the Single.
* For Usage, the average number of the customer plans to use the treadmill KP781 each week.
* If the customer expects to walk/run greater than 120 Miles per week, it is more likely that the customer will buy KP781 product.
* `KP281` has an even gender distribution, appealing equally to both males and females. `KP481` is slightly favored by males, with 51.7% male and 48.3% female customers. In contrast, `KP781` is mostly preferred by males, with 82.5% male and only 17.5% female customers. This means `KP781` is strongly liked by men, while `KP281` and `KP481` have a more balanced or slightly male-leaning audience.
* For `KP281`, customers are evenly split between genders and have an average age of around 28.5 years. Their income averages $46,418, indicating a broad, moderate-income range.
* For `KP481`, customers are slightly more male and have an average age of about 28.9 years with a higher average income of  $48,974. 
* For `KP781`, the customer base is predominantly male, with an average age of 29.1 years and a much higher average income of  $75,442, reflecting a premium product appeal.

**Recommendations** <br>
1.Target Marketing: Continue promoting KP281 as an entry-level option with broad appeal, highlighting its balanced gender distribution and moderate price. Position KP481 as a slightly premium choice appealing to both genders, while KP781 should be marketed as a high-end product targeting males with advanced features and high-mileage needs.
2.Customer Targeting: Focus on customers aged 24-33 with 16 years of education and offer special promotions for partnered customers, who show greater interest in purchasing. Address high-income and high-mileage users by offering tailored solutions or premium options to meet their specific needs.
