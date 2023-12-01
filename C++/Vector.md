# Vector
### v.erase()
> v.erase(v.begin() + index)
- Erases index-th element.
> v.erase(v.begin(), v.begin() + index);
- Erases index elements from the beginning.

#### Combine with remove() in Algorithm
> v.erase(remove(v.begin(), v.end(), val), v.end())
- Erases all 'val' elements and reduces the size of the vector.
- remove() doesn't reduce the size of the vector but replaces it.
