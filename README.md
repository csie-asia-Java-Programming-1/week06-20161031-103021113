# week06-20161031

#### 課堂練習題目:  

1. 寫一函數 square(n,c)，以 c 字元，印出邊長為 n 之實心正方形。Ex：square(3,'@') 將印出如下形狀
<pre>
@@@
@@@
@@@
</pre>
2. 使用者輸入兩個整數，透過函數呼叫輸出排列組合函數 C(m,n)。公式: C(m,n) = m!/n!(m-n)!
3. 輸入一串數字，寫出一數字拆解函數 decomp(n)，將其個別數字用空白分開。例如:輸入128917178, 則輸出 <pre>1 2 8 9 1 7 1 7 8 </pre>
4. 撰寫一函數void square(arr)，在呼叫square(arr) 函數後，一維陣列arr 裡的每一個元素皆會被平方。例如:輸入1 3 5 7, 則輸出<pre>1	9	25	49</pre>
5. 使用者輸入一個大正整數值，請設計一個函數fun1(n)可以計算該大數字裡的數字總合。例如:輸入: 4832 則輸出<pre>17</pre>


#### 作業:

1. 請設計一個函數fun(v1, type)，讓使用者輸入一個溫度值及計算方式
 - type為1時華氏->攝氏；type為2時攝氏->華氏
 - 函數算出結果後要回傳至主程式再印出結果。(F=C*9/5+32), (C = (F-32) * (5/9)例如:
 <pre>輸入 100 1 則輸出37.77778<br>輸入 37.77778 2 時則輸出 100.0</pre>
2. 讓使用者輸入性別與身高，透過函數呼叫，依據男女不同, 幫她(他)計算並輸出其標準體重
 - ((1)男：(身高-170)*0.6+62 , (2)女：(身高-158)*0.5+52)。
 - 函數算出結果後要回傳至主程式再印出結果。例如:<pre>輸入 1 170 則輸出 62.0<br>輸入 2 165 則輸出 55.5</pre>
