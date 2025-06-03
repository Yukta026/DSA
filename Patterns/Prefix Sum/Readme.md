Prefix Sum Pattern Learnings- 

1) Prefix sum either stored in an array or if indices needed to be stored use hashmap
2) Special focus on assigning 0 index before using array or hashmap
   For example -
   Array - int[] prefixSum = new int[arr.length+1];
   HashMap - map.put(0,1);
4) Good for query sum of elements in sub-array
   
