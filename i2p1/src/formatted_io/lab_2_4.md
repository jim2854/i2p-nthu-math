## Lab 2-4: 大正實數加法 (10%)

* 輸入：兩正實數的整數部分、正實數的小數部分 (1/1,000,000,000,000,000,000)，整數及小數各不超過 18 位數字
* 輸出：兩正實數數值、兩正實數的和，整數及小數各不超過 18 位數字，小數部分固定顯示 18 位。
* 檔名：lab2_4_<學號>.cpp (e.g. lab2_4_106062802.cpp)

程式需提示使用者輸入兩正實數的整數部分、正實數的小數部分，程式需輸出兩正實數數值、兩正實數的和。

```text
Input real number (a), before decimal point: <(a) before decimal point>
Input real number (a), after decimal point: <(a) after decimal point>
The real number is: <real number (a)>
Input real number (b), before decimal point: <(b) before decimal point>
Input real number (b), after decimal point: <(b) after decimal point>
The real number is: <real number (b)>
(a) + (b) = <real number (a) + (b)>
```

Example:

```console
$ ./a.out
Input real number (a), before decimal point: 123456789012345678
Input real number (a), after decimal point: 123456789012345678
The real number (a) is: 123456789012345678.123456789012345678
Input real number (b), before decimal point: 987654321098765432
Input real number (b), after decimal point: 987654321098765432
The real number (b) is: 987654321098765432.987654321098765432
(a) + (b) = 1111111110111111111.11111111011111111
```

Reference:
* [Big Number Calculator](https://www.calculator.net/big-number-calculator.html)