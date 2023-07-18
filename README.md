# spam-bots-detector

#About Dataset

#Context:
Fakes and spammers are a major problem on all social media platforms, including Instagram.
This is the subject of my final-year project in which I set out to find ways of detecting them using machine learning.
In this dataset fake and spammer are interchangeable terms.

#Content:
I have personally identified the spammer/fake accounts included in this dataset after carefully examining each instance and as such the dataset has high level of accuracy though there might be a couple of misidentified accounts in the spammers list as well.
The dataset has been collected using a crawler from 15-19, March 2019.

#Inspiration:
This dataset could be further improved in quantity and quality measures, but how much accuracy can it achieve?
Possible ways of using the models to tackle the problem?



#Features in the data set:

Profile pic: This feature indicates whether or not the user has a profile picture. Spam accounts are less likely to have profile pictures, as they are often created by bots or automated scripts.

Nums/length username: This feature calculates the ratio of the number of numerical characters in the username to its length. Spam accounts are more likely to have usernames with numerical characters, as this makes them easier to remember and type.

Fullname words: This feature splits the full name into word tokens. Spam accounts are less likely to have full names with multiple words, as this makes them more difficult to create and manage.

Nums/length fullname: This feature calculates the ratio of the number of numerical characters in the full name to its length. Spam accounts are more likely to have full names with numerical characters, as this makes them easier to remember and type.

Name==username: This feature checks if the username and full name are literally the same. Spam accounts are more likely to have the same username and full name, as this makes it easier for them to appear more legitimate.

Description length: This feature measures the length of the bio in characters. Spam accounts are less likely to have long bios, as this makes them more difficult to create and manage.

External URL: This feature indicates whether or not the user has an external URL in their bio. Spam accounts are more likely to have external URLs, as this allows them to direct users to their websites or landing pages.

Private: This feature indicates whether or not the account is private. Spam accounts are more likely to be private, as this prevents users from seeing their content without following them.

#posts: This feature counts the number of posts that the user has made. Spam accounts are less likely to have many posts, as they are often created to promote a product or service, rather than to share personal content.

#followers: This feature counts the number of followers that the user has. Spam accounts are more likely to have a high number of followers, as they are often used to artificially inflate the popularity of a product or service.

#follows: This feature counts the number of accounts that the user follows. Spam accounts are more likely to follow a large number of accounts, as this allows them to quickly increase their follower count.

Fake: This feature is the class label, which indicates whether the account is genuine (0) or a spammer (1).

These features can be used to train a machine learning model to classify Instagram accounts as spam or genuine. The model can be used to identify spam accounts and take appropriate action, such as blocking them or reporting them to Instagram
