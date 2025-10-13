# Summer Chores (Callback Practice)

This JavaScript project demonstrates how to use **callbacks** and **asynchronous functions** (`setTimeout`) to simulate a sequence of summer chores, complete with success and failure outcomes.

## Description
Each function represents a chore (like mowing the yard or watering the garden).  
Each task runs asynchronously using `setTimeout`, and calls a **callback** to signal when it’s finished or failed.

If all chores succeed, the script logs: "(name) finished all their chores!"

If any chore fails, it stops early and logs a message like, "(name) fell asleep choppoing wood."

## Chores Included
- `mowYard()` – 2000 ms delay  
- `weedEat()` – 1500 ms delay  
- `trimHedges()` – 1000 ms delay  
- `collectWood()` – 2500 ms delay  
- `waterGarden()` – 500 ms delay  

## How to Run
1. Install **Node.js** if it isn't already.

2. Clone this repository.

3. Navigate into the folder summer-chores.

4. Run the file with node summerChores.js.
