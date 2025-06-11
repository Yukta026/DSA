Merged Intervals Pattern learnings- 

1) Usually 2-D arrays are given so sort them when required using -
Arrays.sort((a,b) -> Integer.compare(a[0),b[0)))

2) ArrayList provides great flexibility in storing the intermediate results and then answer can be returned in 2-d using -
return ans.toArray(new int[ans.size()][])
