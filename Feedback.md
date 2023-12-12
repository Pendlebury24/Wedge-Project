## Feedback 

Nice work on this project, you can consider it complete except for parts of Task 3.. I'm going to read your files in order and give you feedback
as I move through them, from Task 1 to Task 3. Your point about relying on GPT too much is a good one. 

### Task 1

* It's a little weird to have these other Task 1 files floating around. (You could put the ones I don't need to look at in a folder.) 
* The baseline file looks good and efficient.
* It'd be nice to remove lines like this `print(df.head())` from your final submission so that it's easier to read.
* Otherwise, the upload, which <ahem> isn't in the file named "upload" and that's a little weird, looks good. 

### Task 2

* Nice job on this task.
* I'm surprised that 80 owners were enough to get to 250 MB.
* It'd be worth thinking through how you'd do this the reproducible way. That'd involve selecting distinct card numbers, pulling them down to python, calling `random.sample` and then building a query that could use them all. Let me know if it's not clear how you'd do that. 


### Task 3

Queries 2 and 3 are incorrect. In Query 1, we have this in our `WHERE` clause: 

```
  department NOT IN (0,
    15)
  AND (trans_status IS NULL
    OR trans_status IN ("V",
      "R",
      " "))
```

Reflect on why we have that. And notice how you are reporting zero sales for every year and month.

When you get this corrected, just send me a teams message and we'll sign it off. 
