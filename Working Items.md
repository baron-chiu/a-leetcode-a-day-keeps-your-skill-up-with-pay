# Working Items

### 2021-11-23 
* CPP pointer v.s reference
* assignee: #Jordan 

#### Difference 
* reference is syntax suger
	* compiler will apply `*` automatically.
	* can't point to null object
	* A pointer can be re-assigned:
	```cpp
	int x = 5;
	int y = 6;
	int *p;
	p = &x;
	p = &y;
	*p = 10;
	assert(x == 5);
	assert(y == 10);
	```
	* A reference cannot be re-bound, and must be bound at initialization:

	```cpp
	int x = 5;
	int y = 6;
	int &q; // error
	int &r = x;
	```
#### Ref
*[What are the differences between a pointer variable and a reference variable in C++?](https://stackoverflow.com/questions/57483/what-are-the-differences-between-a-pointer-variable-and-a-reference-variable-in)

### 2021-11-24

- [ ] ![[What's the usage of `mid = l * (r-l)`]]
- [ ] ![[Why can Sliding Window get all the longest substrings?]]

### 2021-11-27

- [ ] ![[What is segment tree?]]
- [ ] ![[Implement Bisect]]
- [ ] ![[What is tree traversal order]]