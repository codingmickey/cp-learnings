# cp-learnings

## Strings

### Converting the string to lower/upper case in `c++`
```c++
// using transform() function and ::toupper in STL
transform(su.begin(), su.end(), su.begin(), ::toupper);

// using transform() function and ::tolower in STL
transform(sl.begin(), sl.end(), sl.begin(), ::tolower);
```

### Replace all
```c++
std::replace( s.begin(), s.end(), 'x', 'y'); // replace all 'x' to 'y'
```

### Check if the character is present
```c++
std::string s = "Hello";
if (s.find('e') != std::string::npos)
    cout << "Found";
else
    cout << "Not Found"; 
```

### Inserting string in a string
```c++
// Inserts str2 in str1 starting 
// from 6th index of str1
str1.insert(6, str2);
```

### Split a string based on delimiter
```c++
// Splits str[] according to given delimiters.
// and returns next token. It needs to be called
// in a loop to get all tokens. It returns NULL
// when there are no more tokens.
char * strtok(char str[], const char *delims);
```
