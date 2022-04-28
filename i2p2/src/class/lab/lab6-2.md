## Lab 6-2: Simple Complex Number Calculator (40%)

* 輸入：
  1. 以 `double` 格式輸入複數的實數及虛數部分，以空格分開，一行輸入一個複數
  2. 以 `char` 格式輸入複數的運算子，包含 `+`、`-`、`*`、`/`，一行輸入一個運算子
  3. 複數與運算子以交錯的方式輸入，一行輸入一個複數接著一個運算子，倒數一行為複數
  4. 輸入 <kbd>Ctrl</kbd>+<kbd>D</kbd> 結束程式
    * Windows 請輸入 <kbd>Ctrl</kbd>+<kbd>Z</kbd> (會在螢幕上顯示 `^Z`) 再輸入 <kbd>Enter</kbd> (Format 中的 `⏎`) 結束程式
* 輸出：
  1. 顯示運算複數的結果
    1. 複數的格式為 `(-)<real result> (+|-) (<imag result>i)`
    2. 若輸入運算子、需顯示之前運算的結果，如 [Example](#example) 的範例
* 檔名：`lab6-2_<學號>.cpp` (e.g. `lab6-2_106062802.cpp`)

注意事項：
* 程式不會輸出任何使用者提示，只會輸出程式結果或錯誤訊息
* 使用者不需要處理錯誤輸入
* 請使用 pseudo code 提供的 `main` 及 `Complex_Calc::set_input` 來處理輸入與輸出
* 程式需要於 10 秒內完成，所有的測資皆會保證於 10 秒內完成

### Format

``` text
<real 1> <imag 1>⏎
<result 1>
<op 1>⏎
<result 1>
<real 2> <imag 2>⏎
<result 2>
<op 2>⏎
<result 2>
...
<real n-1> <imag n-1>⏎
<result n-1>
<op n-1>⏎
<result n-1>
<real n> <imag n>⏎
<result n>
^Z⏎
```

### Example

```console
$ ./a.out
1.0 0.0⏎
1
^Z⏎
$ ./a.out
0.0 1.0⏎
0 + 1i⏎
^Z⏎
$ ./a.out
1.0 0.0⏎
1
+⏎
1
2.0 1.1⏎
3 + 1.1i
-⏎
3 + 1.1i
-3.0 -2.2⏎
6 + 3.3i
*⏎
6 + 3.3i
4.3 2.1⏎
18.87 + 26.79i
/⏎
18.87 + 26.79i
-1.2 -3.4⏎
-8.74846 + 2.46231i
^Z⏎
$ ./a.out
1.0 0.0⏎
1
+⏎
1
2.0 1.1⏎
3 + 1.1i
-⏎
3 + 1.1i
-3.0 -2.2⏎
6 + 3.3i
*⏎
6 + 3.3i
4.3 2.1⏎
18.87 + 26.79i
/⏎
18.87 + 26.79i
-1.2 3.4⏎
5.26477 - 7.40815i
^Z⏎
$
```

### Pseudo Code

```c++
{{#include lab6-2_pseudo.cpp}}
```

### Reference Code: 

#### 林恩佑(109021107)

```c++
{{#include lab6-2_109021107.cpp}}
```

#### TA
  
```c++
{{#include lab6-2_TA.cpp}}
```