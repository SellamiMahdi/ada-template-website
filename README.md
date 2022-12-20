# ADA Template Website
![Labyrinth](https://github.com/SellamiMahdi/ada-template-website/blob/master/assets/img/labyrinth.jpg)
## Wikispeedia
Wikispeedia is an online game created using a subset of articles from wikipedia. It is a graph containing 4598 articles represented by nodes and 119754 links represented by edges. The game is played by users starting from a given article chosen randomly and trying to reach a given target article by clicking on the links found on every article.
## Motivation
We would like to understand how humans look for information on the internet and how we can make it easier to find this information. In this sense, Wikispeedia can be considered a good model of the web, as the users don’t know how the entire graph is connected and they have to find a way to navigate through it. 
By analyzing the different behaviors of the users we can determine not only how the users think about this problem but also how we can make it easier for them to find the information that they need.

##Initial analysis
In order to understand how users navigate through this graph,we decided to create 2 distinct graphs and compare them.
First we use the paths found by the users to create the common sense graph, this will give each link a different weight depending on the number of times it has been clicked by a user and this will show us any tendency that the users might have while making their choices.

Then we create the truth graph which contains the actual way in which all the articles are connected.
While the truth graph contains all the articles and links, we find that in the common sense graph all the articles have been found (4598) while only 57558 out of 119754 of links have been found.
