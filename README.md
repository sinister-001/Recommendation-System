# Recommendation-System

In this repository we are going to create a **Recommendation System for Academic Research** i.e., given a database or folder of files with different extensions <i>(.pdf, .csv, .ppt, .doc, .xlsx, etc.,)</i> which are research papers, publications regarding technologies like Artificial Intelligence, Machine Learning, Generative Adversial Networks, etc,.. the system will recommend some files from the database based on the key-word given by the user for his research purpose.'

I have done this project as a part of my **NLP (Natural Language Processing)** course. This was really an interesting one which uses lot of important *APIs* or *Special Python Libraries* to make this successful. It is not all my own hard work, I used some help and suggestions from the Internet, some experts in Data Science Field and with support of my professor.

Here the interesting and first challenging part is to pre-process all kinds of file extensions to a single string which holds the meaningful data of that particular file and vectorizing them (simply say converting into numerical data) and then training the system to make the files understandable.

The second challenging and most important step is the evaluation metric and recommendation part of the files. The first stage of recommendation is done by the **cosine similarity** which is basically calculating the cosine value of two vectors (one - data vector and other - input vector). The second stage is the most important one the **Eigen Vector Centrality** which is a variant of *Page Rank Theory*.

It involves graph creation, eigen vector calculations and some complex mathematical part but it's really an interesting math to learn. Based on these two recommendations the final weights of the files will be calculated and the best recommendations will be given to the user.

The complete details on the project and theory will be in the report that I am uploading here. Please go through them and even if you still have any doubt feel free to reach me or even you can go through Internet.
