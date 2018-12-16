# Exploring customer behavior on Amazon

[Data Story](https://epfl-ada-project-amazon.github.io/data-story/)

[Repo of the data story](https://github.com/epfl-ada-project-amazon/data-story)

# Abstract
Started 20 years ago, Amazon completely reshaped the online market.
Amazon has more than half a billion different products within very diversified categories (book, kitchen equipment, jewelry..).
This growth had an impact on how people sell and buy on the platform.
Because there are so many products, we might think that customer reviews have a crucial importance on the choices customer make before buying a product.
Because customer reviews are a form of social interaction within the online marketplace, we aim to find out in what way customer reviews are relevant, and what is their overall influence on the product success.

Our aim is to analyse efficiently customer's reviews and summaries, and try to detect when reviews and ratings are not coherent with each other. We will conduct a sentiment analysis and try to implement a model to predict the sentiment of the reviewer, and then explain the insights we find.

In short, our goal is to get valuable insights of the Amazon landscape using customer reviews and product metadata, and focus on customer behaviors on the online marketplace.

# Research questions

We will consider the following questions and address them within our project:
- Is there an impact of a customer review on the product success, depending on its content? 
- What is the impact of a first customer review (good/bad) on products? 
- Do reviews always give a clear idea about the experience of the customer?
- Can we predict the ratings from the reviews?



# Dataset
The main dataset that we are going to use is "Amazon product Data", which contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014. 
This dataset includes:
- reviews (i.e. ratings, text, helpfulness votes, customer id)
- information about products (i.e. images, description, price, category)
- relations between products (i.e. what products are often bought together)
We will explore the reviews and try to answer the question we mentioned above.
We might try and load metadata for further analysis and visualization (e.g. images of products).

# Contribution

- Youssef: Preliminary data analysis and text pre-processing; 
- Mohammed Amine: Plotting graphs conduct the sentiment analysis and searching for the good model to classify reviews;
- Benjamin: coding the classifier, making conclusions about analysis and creating the blog.
