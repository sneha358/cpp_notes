# cpp_notes
1. sorting 
```cpp
bool myfunction (int i,int j) { return (i<j); }

 // using default comparison (operator <):
  std::sort (myvector.begin(), myvector.end());           //(12 32 45 71)
  // using function as comp
  std::sort (myvector.begin(), myvector.end(), myfunction); // (26 33 53 80)
```
2. Add element at the end
Adds a new element at the end of the vector, after its current last element. The content of val is copied (or moved) to the new element.
```cpp
myvector.push_back (i);
```
