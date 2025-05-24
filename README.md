🧠 Explanation (Simple):
Queue stores all jobs in the order they come (FIFO).

Stack stores latest job for easy cancelation (LIFO).

When cancel is called:

Remove the top job from the stack.

Find and remove it from the queue.

When processing:

Print all jobs still in the queue.

🧠 Key Concepts:
Queue (FIFO): First In First Out – used to manage the print jobs.

Stack (LIFO): Last In First Out – used to cancel the most recent job.

