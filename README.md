# Instagram-BioLookup-Engine
## Background
Instagram is a photo and video-sharing social networking service launched in October 2010 and
currently owned by Facebook, Inc. In September 2017, Instagram had 800 million monthly
active users. Currently Instagram only allows the finding of users whose username contains
your query as a substring.

## Technology
For the implementation, Python will be used on Apache Spark(PySpark) and Cloudera will be
used as the virtual machine. Python Version 2.7 will be used to write the script. Jupyter
Notebook will be used to scrape, clean and wrangle the data using various unofficial Python
packages. For building the Inverted Index we will be using a scalable and distributed framework.

## Importance
Being frequent Instagram users, we had various problems while using this Top rated social
application on IOS and Android stores. Instagram only allows its users to find others on the
basis of just the username and no other information. This made it difficult to make social
connections with others on the basis of similar behavior/ hobbies. Thus, we decided to build a 
fast and scalable search engine that matches the search query of a user with the biographic
information of other users.

## Dataset
The data will comprise of different users with a non-null biographic information. There are
privacy issues on Instagram and therefore we will develop a Python Script using unofficial APIs
to scrape the data. The data set will have private key, username, and user's biographic
information in text form. For demonstration of this project, we will be using several of
thousands of users out of the million users on Instagram.
