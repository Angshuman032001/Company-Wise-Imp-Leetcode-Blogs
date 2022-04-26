https://medium.datadriveninvestor.com/curated-list-the-top-most-frequently-asked-coding-questions-you-should-practice-3f8b5ec42ca0

One of the amazon recruiters reached out to me on LinkedIn for the SDE 1 position for amazon's Global selling team. So, basically, they were hiring for a fulfillment platform for enabling cross-border commerce across multiple countries.

I shared my resume which happen to be the first screening round. Normally, the first round is a HackerRank online assessment(70 minutes coding round) but due to my decent LinkedIn profile, the recruiter reached out and gave me a referral.

Round 1 : Telephonic Interview (20-30 mins)

My resume got selected for the telephonic round and they asked me for the free time slot for conducting the first round. Within the next 2–3 days my interview was scheduled.

Questions:

First round was basically to check the core concepts of DSA and Computer Science Fundamentals.

The interviewer asked about graph traversal techniques mainly BFS and DFS. He wanted me to explain them in detail with their time and space complexity. Also, he wanted me to explain its implementation in recursive as well as iterative way.
What are Indexes in SQL?
What are heaps and their time complexity for various operations?
He asked me about the most interesting project on which I worked upon. What are the challenges I faced and how do I conquer them?
Key Takeaway : Round 1

Focus on DSA fundamentals, especially graph traversal techniques. I feel BFS and DFS are amazon's favorite topics. You will definitely find problems related to BFS or DFS in both online assessments as well as the coding interview round.
Round 2 : Interview Round 1 (60 mins)

This round basically involved 2 medium-level questions and last 10–15 mins for amazon leadership skill analysis. Amazon has its own platform for conducting coding rounds called AmazonChime. It's a code editor used for amazon hiring.

Questions :

Both questions where from leetcode only. Leetcode is undoubtedly the best platform for FAANG preparation.

Question 1 : https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/
Question 2 : https://leetcode.com/problems/maximum-sum-circular-subarray/

Amazon leadership question : Mention the most challenging technical use cases you faced in your organization and what steps you took to overcome them.

Conclusion :
For the coding questions, I started with a brute force solution and then talked about my solution's time and space complexity. Then finally jumped on to the optimal solution. And, for the leadership round, you must be familiar with amazon's 14 leadership principles. For SDE 1 roles you must know about these 14 principles if you are applying with some work experience.

The trick is to how you related your experience with these principles and explain them in an optimal and well-organized way. Normally try to break down your answer into Situation, Task, Action, and Result. This method is popularly known as the STAR method.

Key Takeaway : Round 2

The Interviewer was very helpful and he guided me a lot in situations where I got stuck. Try to explain your logic (think out loud) even though it's not the optimal solution because the interviewer kinda helps you to optimize your thought process.
Amazon leadership round is crucial to start preparing by making some scenarios on your own.
Round 3 : Interview round 2 (60 mins)

This round consist of 1 Hard question and there were 2 interviewers for this round. The round was conducted again on AmazonChime.

Question :

The first traversal starts from the top-left corner of the matrix and ends in the bottom-left corner, and the second traversal starts from the top-right corner and ends in the bottom-right corner. From any cell (i, j) in the matrix, we are allowed to move to cell (i+1, j+1) or (i+1, j-1) or (i+1, j). If both traversals pass through the same cell, only one can collect coins from that cell.

Input:  The given matrix is
 
[ 0 2 4 1 ]
[ 4 8 3 7 ]
[ 2 3 6 2 ]
[ 9 7 8 3 ]
[ 1 5 9 4 ]
 
Output: The maximum coins collected is 47.
I started with a brute force solution and explained time complexity and space complexity. Since the brute force complexity was exponential so I tried to come up with some other optimal solution. Finally, I realized that Dynamic Programming can optimize this problem. I took some good minutes to frame my logic so due to time constraints, the interviewer asked me to write the brute force solution. I wrote my exponential solution but I knew I missed this trick here and my chances for the next round are difficult.
After this they asked me about amazon leadership related question.

Solution : https://www.techiedelight.com/collect-maximum-value-coins-matrix/

Result : I didn't receive any mail regarding my result and that is pretty normal in the amazon hiring process. If you don't receive any mail then consider yourself rejected(pretty weird but can't complain considering the job application volume amazon receives).

[ Overall Experience and Few suggestions ]:

These days you can easily expect Leetcode questions directly asked in amazon hiring. So my suggestion is that never get excited that you have already solved this problem and directly jumped on to the optimal solution without talking about brute force solutions and explaining corner cases. I feel that defines a well-disguised plot for your answer. The Interviewer are more interested in how to keep optimizing the problem rather than the perfect answer directly.

You can follow the following template :

The first thing first discuss the constraints applied to the given problem.
Discuss the potential corner cases.
Explain your Brute Force Solution and explain time complexity as well as space complexity.
Finally, pitch your optimal solution with neat code.
Amazon Leadership questions are pretty underrated. I think most of us keep practicing DSA and never analyze how to deal with leadership questions. I believe including this as part of your plan for preparing for big companies is equally important. Just think of a case where you cleared all coding questions and messed up leadership questions which resulted in rejection. This situation is disheartening so better be prepared for this. Also, this is mainly for those with some experience but students who are applying for amazon can use this for explaining their projects. That will surely be an added bonus and will take you one step closure to your dream job.

I personally recommend to follow these resources.(for SDE 1 roles)

https://www.inc.com/peter-economy/the-14-amazon-leadership-principles-that-can-lead-you-your-business-to-tremendous-success.html
https://www.youtube.com/watch?v=lfN8RpA7kvA
https://zety.com/blog/star-method-interview
