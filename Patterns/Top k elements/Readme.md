Top k elements pattern learnings - 

1) While using priority queue always the set the priority appropriately
   for example - PriorityQueue<Integer> queue = new PriorityQueue<>((a,b) -> (a.get(0) + a.get(1) - (b.get(0) + b.get(1))));
   can be used when we need to sort by sum
2) In order to convert queue to integer array, first convert it to object array using toArray() and then convert object array to integer array.
   for example - queue.stream().mapToInt(i->i).toArray()
