1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. Becuase we gonna get instant feedback after we try to do a pr, to know whether 
our code has bug or low quality before mering it into main.

2. Would you use an end to end test to check if a function is returning the correct output?
No because unit test is better to use for checking if function is returning the correct output.
Sometime it could be hard to tell if a end-to-end test fail, where exactly is the reason for it to fail
3. What is the difference between navigation and snapshot mode?
| Navigation Mode          | Snapshot Mode                  |     
|                          |                               |
|-------------------------|------------------------------|
|Reload the page and run lighthouse          | Do not reload the page and only run lighthouse on the current state of the website|
|When to use: simulate user first visit to the site with cold load with metrics(FCP, LCP, TBT, CLS), measuring how the site the perform to first time user vs user comming back (cache vs no cache)   | when to use: when I want to check a new feature that is being used on the page, say a drop down filter with 3 boxes checked|
4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   - Add meta viewport to allow web to be easier to read and interact on smaller screen like phones.
   - Resize image to the size it will be rendered, so user don't have to fetch so much bytes that won't improve their shopping experience.
   - SEO by including a meta description so that the shopping site will be more relevant and can be include in the search result, This will increase traffic.