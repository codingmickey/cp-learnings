# cp-learnings

## MISC

### Converting the string to lower/upper case in `c++`
```c++
// using transform() function and ::toupper in STL
transform(su.begin(), su.end(), su.begin(), ::toupper);

// using transform() function and ::tolower in STL
transform(sl.begin(), sl.end(), sl.begin(), ::tolower);
```
