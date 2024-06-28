# Timur Safin

## Contacts
* Telegram: @ukorp
* Discord: Укорп (@ukorp)

## About me

Moscow Aviation Institute (MAI) Computer Science 3rd year student

## Skills

C/C++

## Code example

LeetCode [`6. Zigzag Conversion`](https://leetcode.com/problems/zigzag-conversion/description/)

```
class Solution {
public:
    string convert(string s, int numRows) {
        std::string answer;
        int size = s.length();
        if (numRows == 1) return s; 
        for (int i = 0; i < numRows; ++i)
        {
            for (int j = i; j < size; j += 2 * (numRows - 1))
            {
                answer += s[j];
                if (i != 0 && i != numRows - 1)
                {
                    int index = j + 2 * (numRows - 1 - i);
                    if (index < size)
                        answer += s[index];
                }
            }
        } 
        return answer;
    }
};
```

## Expirience

-

## Education

* 3rd year Moscow Aviation Institute (MAI) Computer Science student
* Beijing Institute of Technology (BIT) exchange programme (1 semester)

## English level

B1
