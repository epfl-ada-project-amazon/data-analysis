# Exploring customer behavior and the impact of product reviews on Amazon marketplace.

# Abstract
Started 20 years ago, Amazon completely reshaped the online market.
Amazon has more than half a billion different products within very diversified categories (book, kitchen equipment, jewelry..).
This growth had an impact on how people sell and buy on the platform.
Because there are so many products, we might think that customer reviews have a crucial importance on the choices customer make before buying a product.
Because customer reviews are a form of social interaction within the online marketplace, we aim to find out in what way customer reviews are relevant, and what is their overall influence on the product success.
Is a first bad review a red flag for customers?
A popular claim is that some people are paid (or offered a product for free), in exchange for a good review. Can we detect such cases if they exist?
We will study efficient ways to make visualization of products trends, and find relevant information about products, such as clusters of "often bought together" products.
In short, our goal is to get valuable insights of the Amazon landscape using customer reviews and product metadata, and focus on customer behaviors on the online marketplace.

# Research questions
We will consider the following questions and address them within our project:
- Is there an impact of a customer review on the product success, depending on its content?
- What is the impact of a first customer review (good/bad) on products?
- Can we distinguish categories of customers in term of interest and activity on amazon?
- Within specific categories (e.g. Books), can we detect trends and find a way to visualize them in a efficient manner?
- What is the success distribution among products within the different categories?

# Dataset
The main dataset that we are going to use is "Amazon product Data", which contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014. 
This dataset includes:
- reviews (i.e. ratings, text, helpfulness votes, customer id)
- information about products (i.e. images, description, price, category)
- relations between products (i.e. what products are often bought together)
We will explore the reviews and try to answer the question we mentioned above.
We might try and load metadata for further analysis and visualization (e.g. images of products).

# A list of internal milestones up until project milestone 2
1. 5-11 November
    1. Retrieve all the data we need.
    2. First draft of a data story we will tell.
    3. Clarify the questions we will address to fit a story.
    4. Decide what methods we will use to address the questions depending on the data we have
    5. Each of us 3 will chose to address some of these questions
2. 12-19 November
    1. Each of us: Prototype of our own data analysis task
    2. Each of us: cross validation of the **validity** of the work of the other two
    3. Merge our work into a single notebook
3. 20-25 November
    1. Extra time for debugging, reviewing, and ensuring what we provided is coherent
