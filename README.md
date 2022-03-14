# stock-analysis
Overview:
The purpose of this analysis was to determine the performance of about 11 different stocks over the course of 2017 and 2018, in order to see which stocks are most likely to be the best peforming over a longer period of time. We are also comparing how the original code that combed through a few stocks compares to this refactored one.

Results:
![image](https://user-images.githubusercontent.com/94264746/158092732-2db9070d-ca46-46de-a853-a96b472e6662.png)
For 2017, overall the returns were positive with only TERP producing a negative return. Run time with the refactored code was less than a half second. 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/94264746/158093286-82aa0392-4f80-43ee-a1f2-8867df9f76c1.png)


![image](https://user-images.githubusercontent.com/94264746/158092829-6fe14358-ec52-43a2-b28f-fc65ecd4b14a.png)

However for 2018, the only stocks that performed well were ENPH and RUN. Run time for the refactored code was even less than 2017:
![VBA_Challenge_2018](https://user-images.githubusercontent.com/94264746/158093410-6d2dd48b-7979-42a3-b0f2-159888aaa83b.png)

Summary: 
The only disadvantage of refactoring code that I can see, is that you're spending more time to edit code that already works. However, making code more efficient is in my opinion, well worth the effort. In this case, the original code would really have only worked for a smaller dataset. It takes far too long to display results with it so it makes sense to refactor it so it's not only more efficient, but it takes up less memory and is more effective for larger datasets.
