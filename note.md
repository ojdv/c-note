# C++筆記
## 指標
指標的宣告：
```cpp=
指標型態 * 變數名稱
```
num存數字， 宣告一個指標叫 ptr，把 ptr 設為 num 的記憶體位置
**宣告時： ```int *ptr```代表這是一個指標變數**
**使用時： ```*ptr``` 代表提領，也就是去那個地址看裡面住誰**
要取得某個變數的記憶體位置時，前面會加 '&'
**&num就代表變數num的記憶體位置**
```cpp=
#include <bits/stdc++.h>
using namespace std;
int main(){
    int num=100; 
    int *ptr;
    ptr=&num;
    cout << *ptr;
}
``` 
### Null 空指標
代表宣告了一個空的地址
```cpp=
#include <bits/stdc++.h>
using namespace std;
int main(){
    int *ptr=nullptr;
    cout << "Ptr is " <<*ptr;
}
```
## 二元樹
