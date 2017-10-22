# SQL Project: Instant Runoff Voting

## Intro

For this project, your task will be to simulate an Instant-runoff election.

From Wikipedia: 
>Instant-runoff voting (IRV), also known as the alternative vote (AV) or transferable vote, is a voting method used in single-seat elections when there are more than two candidates. (It is also sometimes referred to as "ranked-choice voting" (RCV) and "preferential voting", although there are other preferential voting methods that use ranked-choice ballots.) 
>Instead of voting only for a single candidate, voters in IRV elections can rank the candidates in order of preference. Ballots are initially counted for each elector's top choice. If a candidate secures more than half of these votes, that candidate wins. Otherwise, the candidate in last place is eliminated and removed from consideration. The top remaining choices on all the ballots are then counted again. This process repeats until one candidate is the top remaining choice of a majority of the voters. When the field is reduced to two, it has become an "instant runoff" that allows a comparison of the top two candidates head-to-head.

Instructions

You are given a table called “votes” where each row represents one person’s vote. The column “X1” is that person’s first choice, “X2” is the second choice and so on. Your task is to simulate an IRV election and output the results in the format of the table below. Note that the correct answer to the results of the election are shown in the table below. However, we expect your query/queries to output the correct IRV election results when executed on another dataset (e.g. some other table "votes" with the same columns).


Winner	Margin
Tim	6 votes


Getting Started

To begin, download the sql file here, and import it into SqliteStudio. Happy coding!

Cheating

This project must be completed individually. You may discuss with other students approaches to simulating the election, but you may not share code in any way. Do not show any of your SQL code to any other student. You may not look at another individual's code. We use very sophisticated software to detect cheating. Keep in mind that I will also be reading through every single submitted file in it's entirety, so you might fool the software but you won't fool me. If we determine that you have cheated, you will receive a score of 0 for the project, a grade of "Not Passed" for the class. You will also be referred to the Office of Student Conduct. Don't cheat.

Submission

Please submit your final assignment through bcourses. Your submission should be in the form of one SQL file (with an extension of .sql). 

Rubric

The following is the point breakdown for this project: 


SELECT * FROM rubric

Both the winner and margin of error are calculated correctly, code is well put together.	28 - 31 points (extra credit will be given for exemplary submissions)
Both the winner and margin of error are calculated correctly, code is not well put together.	24 - 27 points
Winner and/or margin of error not calculated correctly, but the code is a decent attempt at calculating the right answer	18 - 23 points
Submitted something, obvious lack of effort	1 - 17 points


Other Notes / Updates:


The project is due on Saturday, October 22, 2017. Don't wait until the last minute to get started.
We will be holding project office hours during the following times:
Thursday, October 12, 8-10pm. Soda 283E
Wednesday, October 18, 8-10pm. 110ME Kresge.
You may create as many tables as you like. No points will be deducted for creating a table and not deleting it after your query/queries finish.
Remember that to run multiple queries in Sqlite Studio, you need to select (highlight) all of them and then press Run.
You must be signed into your Berkeley account to download the file.
Something I didn't teach but might be very useful for you is the Sqlite CASE command. 