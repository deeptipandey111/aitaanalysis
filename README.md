# What happens on r/aita?
Data Analysis of the subreddit aita: https://www.reddit.com/r/AmItheAsshole/ 

<img width="1788" alt="Screen Shot 2021-09-09 at 6 00 30 PM" src="https://user-images.githubusercontent.com/11023465/132768343-5439503a-4481-4501-ae94-981f84319654.png">


AITA is one of my most favorite subreddits. I think it provides interesting insights into personal situations where individuals are most conflicted. I would imagine that when people write these posts asking strangers whether they were the a$$hole in the said situation, they already believe that they did was correct. But then someone who's opinion matters suggests otherwise, and now they are conflicted enough to ask the internet. Also, I would imagine that they refer to people or situations most crucial to them. So typically the topics that I saw show up the most are parents, partners, weddings, etc. I also wanted to see how do people primarily describe the action that is the topic of their a$$holes-ness. So my two big questions are: 
1. What were the most common actions OPs(Original Posters) refer to?(e.g. "Am I the a$$hole for *thinking*, *believing*, *refusing*...."?)
2. What were the most talked about topics?(Based on film scenes depicting therapy, I would expect that parents are the most talked about people)

To analyse this, I scraped the top 64000 posts on aita, and after some basic data cleaning, tokenization and lemmatization, separated the tokens into action words(using parts of speech tagging) and subject words, sorted them by frequency and plotted the top 10 of each. here are the results: 

Most common topics: 
green: ![Frame 20 (1)](https://user-images.githubusercontent.com/11023465/132768158-17075962-becf-44be-8baa-c6feca15b8d8.png)

Most common actions: 
red: ![Frame 20](https://user-images.githubusercontent.com/11023465/132768014-43f7a509-2117-4ccb-ba27-3588d4e32254.png)

While *friend* won over family members as being subjects(would have expected *mom* + *dad*), the most common actions that people discussed was *wanting*. I find it so interesting that when posters come to fellow redditors looking for judgement on whether they were the a$$hole in the situation, they are conflicted on whether they are the a$$hole for *wanting* something. The top personal conflict is not even about something that they *did*. It's about something they *want* to do/be/feel. 
