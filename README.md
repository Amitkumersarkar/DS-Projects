🧠 Explanation (Simple):
Queue stores all jobs in the order they come (FIFO).

Stack stores latest job for easy cancelation (LIFO).

When cancel is called:

Remove the top job from the stack.

Find and remove it from the queue.

When processing:

Print all jobs still in the queue.
