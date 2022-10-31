## Google Keyword Generator

Currently I work for a company with Google ADS advertising, so, I need to explore a good range of keywords. 

I have had a lot of trouble finding keywords that are good, so, I search a project on DataCamp and created a Google Keyword Generator to automatize the work.

I would like to use this space to comment a little bit about the code.


To create a keyword, you will need, at leat, two words, because it is necessary to relate what you are selling with what you want your customers to see. Because of it, the first step was declare two list, só that e could create variations of the keyword.

So, let's suppose we want to make ads to a candy store, we have like:

words = ['Buy', 'Purchase', 'Sale Of', 'Good', 'Delicious']

and products = ['Candy', 'Sweet', 'Bubble Gum', 'Pie', 'Child Candy']

The firsts keywords generated would be "Buy Candy", "Buy Sweet", "Buy Bubble Gum", and so on...



Because of this structure, I need to creat two Python lists: one that work as a column,for me to organize the keywords generated, and, other that work as a appending combination, so that I could append the list "products" with the list "words".

With it done, I need to create a dataframe from a lista, so I used the pandas documentation to get the data format right and create a diversification of columns.

In Google ADS, we have different types of keywords, so, I created dataframes columns for organizing this, and appended each type of keyword in the respective dataframe column.

By the end, it was time to group the dataframe, and I did it, and created a excel file that looks like this, so that other bussiness areas could use and upload the keywords to Google ADS, manually or with the sheets 
automation



![Sem título2](https://user-images.githubusercontent.com/106437550/199117996-d8066735-e7e4-48a5-8f0f-20680e5656b6.png)



