This is a project done by my friends and me based on an existing project on Github:
https://github.com/KidQuant/Analyzing-News-Articles-With-Python

Part 1 and part 2 we did almost the same as what KidQuant has done, the codes were modified so they would work and fit our target. 
(these parts' comments are in Vietnamese so if you want to understand the codes further, you'll need to translate them into your languages, I'll try to update the English comments later)
The first two parts was done by my teammates (Nguyen Dinh Dai Nhon and Pham Tran Son Bao). 

The 3rd part was done on my own. 
The idea of this part is to create a feature that can allow users on All Sides can search for the articles that are related to some images they read on social media (Facebook, Instagram,...).
What led to this idead was that I realised people are spending more time reading news on them because the time people use them tend to increase.
And there can be real and fake news. 
The idea of using content-based image search (a technique that allows users to search for images using visual features or content rather than text-based queries. Instead of relying on keywords or metadata, content-based image search analyzes the actual visual information in the images to find similar or related images.)
is to create a feature that can help people checking the news from All Sides (a site that collects news from mainstream newspapers) so that people can find and read more about the news they've read with just an image that they captured/saved. And from that, the ratio of being intimidated by fake news will (hopefully) decreased.
Another important thing in part 3 is about sentiment analysis (texts and images). There is nothing to say about texts sentimental analysis.
About images sentiment analysis (this idea was suggested by my lecturer), using Deep Learning to analyze the feelings in an image (positive/negative/neutral) and compare it to the texts' results in order to check if the images really reflect part of the texts' sentiment.
Theoretically, this part should have been done by this order:
- 1st, I have to train the model on a part of the dataset
- Then, I have to check for its performance (the model's accuracy)
- Finally, compare the sentiment analysis of texts and images.

But at that time, we didn't have enough time to did all the steps (we only had about 2 days to finish our projects. Of course, the 1st, 2nd, and part of my part was done before that) so for the image sentiment analysis part, I decided to use a pre-trained model.
Because of that, the project isn't done perfectly at that time.
I'll try to finish my part using a model trained on our dataset for a better result.
