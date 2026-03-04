# 💻 Programming Ability & Logic Building - I (PALB)
---

## 📅 Week 1: 19/01/26 to 25/01/26
*Focus: Basic Array Operations*

### 1. Reverse an Array
* **Source:** GeeksforGeeks 
* **Problem:** Reverse a given array in-place.
* **Link:** https://www.geeksforgeeks.org/problems/reverse-an-array/1
* **Solution:**
```python
class Solution:
    def reverseArray(self, arr):
        i, j = 0, len(arr) - 1
        while i < j:
            arr[i], arr[j] = arr[j], arr[i]
            i += 1
            j -= 1
        return arr
```
<img width="1884" height="716" alt="image" src="https://github.com/user-attachments/assets/e179eaaa-2dcc-4c16-8f04-1a671de9359d" />


### 2. Kth Smallest Element
* **Source:** GeeksforGeeks 
* **Problem:** Given an array arr[] and an integer k, return the kth smallest element in the given array.
* **Link:** https://www.geeksforgeeks.org/problems/kth-smallest-element5635/1
* **Solution:**
```python
class Solution:
    def kthSmallest(self, arr, k):
        
        arr.sort()
        return arr[k-1]
```
<img width="1877" height="713" alt="image" src="https://github.com/user-attachments/assets/ddfd2c16-1707-4b38-b136-6d00224c9938" />


### 3. Union of Two Arrays
* **Source:** GeeksforGeeks 
* **Problem:** You are given two arrays a[] and b[], return the Union of both arrays in any order.
* **Link:** https://www.geeksforgeeks.org/problems/union-of-two-arrays3538/1
* **Solution:**
```python
class Solution:    
    def findUnion(self, a, b):
        
        c= set(a+b)
        return list(c)
```
<img width="1871" height="710" alt="image" src="https://github.com/user-attachments/assets/6c6d8764-072d-4f2a-9bfd-6f69a19e2c56" />

