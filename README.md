1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a GitHub action that runs whenever code is pushed. Because we're gonna get instant feedback after we try to do a pr, to know whether 
Our code has a bug or low quality before merging it into the main.

2. Would you use an end-to-end test to check if a function is returning the correct output?

No, because a unit test is better to use to check if the function is returning the correct output.
Sometimes it could be hard to tell if an end-to-end test fails, and what exactly the reason for it to fail is

3. What is the difference between navigation and snapshot mode?

| Navigation Mode          | Snapshot Mode                  | 
|-------------------------|------------------------------|
|Reload the page and run Lighthouse          | Do not reload the page and only run Lighthouse on the current state of the website|
|When to use: simulate user first visit to the site with cold load with metrics(FCP, LCP, TBT, CLS), measuring how the site the perform to first time user vs user comming back (cache vs no cache)   | when to use: when I want to check a new feature that is being used on the page, say a drop down filter with 3 boxes checked|
4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

   - Add a meta viewport to allow the web to be easier to read and interact with on smaller screens like phones.
   - Resize image to the size it will be rendered, so user don't have to fetch so much bytes that won't improve their shopping experience.
   - SEO by including a meta description so that the shopping site will be more relevant and can be include in the search result, This will increase traffic.
