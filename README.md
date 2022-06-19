# Bowl Builder API
Send in meals, retrieve updated daily nutrition stats. Also get suggested meals based on remaining daily nutrition requirements.

## Plan
### Get updated daily nutrition requirements based on meals
1. Get meals (lists of food and their quantities)
2. Retrieve the meal's nutrition info by tallying up each ingredient's nutrition content
3. Get individual ingredient nutrition content (including macro & micro nutrients) from some database
### Get meals recommended based on remaining daily nutrition requirements
1. Somehow be able to get the most nutritionally dense foods from the database
2. Choose among those foods to satisfy the inputed remaining daily nutrition requirement
3. Somehow also select items based on taste meshing well with the other ingredients