# Instructions

## State score metrics
Let's create a report showing the average score and maximum score earned by participants in each state.

Our quiz database contains two tables, `states` and `people`.

**Your task**: Write a query that returns the maximum and average scores for each state, along with the state's name, sorted from highest to lowest average score.

## Result
Your result should have three columns:
- `STATE`: the name of each state
- `MAXPOINTS`: the highest value of `quiz_points` for each state
- `AVGPOINTS`: the average number of `quiz_points` earned by participants in each state

Sort the results by `AVGPOINTS` from highest to lowest.
