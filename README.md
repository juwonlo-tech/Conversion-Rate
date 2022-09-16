# Conversion-Rate
The project is aimed at helping an organization increase the number of people that make purchases (convert) after visiting their website
Using the Logistic Regression algorithm, a system was developed to predict whether a new user will convert or not and provide the current conversion rate. 
Recommendations were also made based on the results of exploratory analysis on how to increase the conversion rate and increase the performance of the website/organization.

### The Data
The data contains 316200 data points, 5 features and 1 label. 
The features are: country (based on the IP address), age,	new_user (binary classification to indicate if the user is visiting for the first time or is a return user), 
source (how they got into the website, through a search engine, advert click, or directly), and total_pages_visited (an indication of how long they spent on the website),	
with the label being: converted (a binary classification indicating whether they purchased a product or not).

### The Analysis
The notebook covers statistical and visual exploratory analysis of the data using the python pandas library, matplotlib, and seaborn.

During the analysis, some interesting correlations were observed.
In the plot below for instance, it was obsserved that the more time users spend on the website, the higher the chances on them converting.

<img width="997" alt="Screen Shot 2022-09-15 at 6 14 37 PM" src="https://user-images.githubusercontent.com/77176412/190524571-cc759cb9-0fe4-4089-8ad4-27125f60d2d5.png">

The plot below displaying the number of users that converted by country shows that the website is actually getting clicks and hits, 
there is just an incommensurate conversion proportion.

<img width="997" alt="Screen Shot 2022-09-15 at 6 44 50 PM" src="https://user-images.githubusercontent.com/77176412/190527428-703f9292-9c21-4bc2-943d-b2562cf7c1af.png">

### The Model
A prediction system was developed using the logistic regression algorithm. The system is 98.46% accurate in predicting conversion based on the given features.
The result for the conversion rate based on the number of people that converted and the time spent on the website is 0.0066.
It was also discivered that the number of pages visited is the most important feature in determining whether a person will convert or not.

#### Recommendations 
The most important feature in whether or not a user will convert is the number of pages visited. 
The marketing team can look into how to keep users glued to the website such as a captivating landing page. 
Targeted adverts should be sent to existing users (that have not converted) on flash sales or just inviting them to check out new products. 
Things like 'treasure hunts' will also increase the number of users and the length of time spent, and consequently, the conversion rate. From the exploration and model, the market in Germany is almost non-existent. 
Resources can be channeled into improving patronage from that region. Resources should also be channeled to other North American and Asian countries since the organization has a huge presence in major countries on these continents.

Also, a large population of users are visiting via SEO. More resources can be directed towards more publicity via SEOs.
