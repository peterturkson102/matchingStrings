# matchingStrings
There is a collection of input strings and a collection of query strings. For each query string, determine how many times it occurs in the list of input strings. Return an array of the results.


Example



There are  instances of ',  of '' and  of ''. For each query, add an element to the return array, .

Function Description

Complete the function matchingStrings in the editor below. The function must return an array of integers representing the frequency of occurrence of each query string in strings.

matchingStrings has the following parameters:

string strings[n] - an array of strings to search
string queries[q] - an array of query strings
Returns

int[q]: an array of results for each query
Input Format

The first line contains and integer , the size of .
Each of the next  lines contains a string .
The next line contains , the size of .
Each of the next  lines contains a string .

Constraints



 .

Sample Input 1

CopyDownload
4
aba
baba
aba
xzxb
3
aba
xzxb
ab
Sample Output 1

2
1
0
![image](https://user-images.githubusercontent.com/43896389/214980955-2e34a3ef-7955-4c83-ada5-364c9764b040.png)

Sample Input 2

CopyDownload
3
def
de
fgh
3
de
lmn
fgh
Sample Output 2
![image](https://user-images.githubusercontent.com/43896389/214980983-6d279da7-20b6-4f88-b251-5b4f73fcdd21.png)

1
0
1

Sample Input 3

CopyDownload
13
abcde
sdaklfj
asdjf
na
basdn
sdaklfj
asdjf
na
asdjf
na
basdn
sdaklfj
asdjf
5
abcde
sdaklfj
asdjf
na
basdn
Sample Output 3

1
3
4
3
2
