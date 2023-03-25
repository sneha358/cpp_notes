# cpp_notes
1. sorting 
```cpp
bool myfunction (int i,int j) { return (i<j); }

 // using default comparison (operator <):
  std::sort (myvector.begin(), myvector.end());           //(12 32 45 71)
  // using function as comp
  std::sort (myvector.begin(), myvector.end(), myfunction); // (26 33 53 80)
```
