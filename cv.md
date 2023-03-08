# CV Yergozha Kairzhan
***
___Name:___ Kairzhan
___Surname:___ Yergozha
***
___Email:___ kairjan11111@mail.ru
___Phone_Number:___ +87082992593
___Telegram:___ @Banapushyou
*** 
```Начинающий фронтэнд разработчик, на данный момент обучаюсь на 2 курсе по специальности Вычислительная техника и программное обеспечение, в прошлом году проходил стажировку на позиции верстальщика```
***
___Knowledges___
_C++_
_Java_
_JS_
_HTML_
_CSS_
***
```
#include<iostream> #include<string> using namespace std;

struct Book { string title; int price; string type; int sold; };

int main() { int n; cin >> n; Book* book = new Book[n];

for (int i = 0; i < n; i++) {    cin >> book[i].title >> book[i].price >> book[i].type >> book[i].sold; } int sum3 = 0; for (int i = 0; i < n; i++) {    if (book[i].type == "Classical") {      book[i].price = book[i].price * 0.8;    }

  if (book[i].sold > 50) {      book[i].price += 50 * book[i].price;            book[i].price *= 1.2;            book[i].price += (book[i].sold - 50) * book[i].price;    }    else {            book[i].price += book[i].sold * book[i].price;    sum3 += book[i].price;

  cout << book[i].title << " " << book[i].price << endl; } cout << "Total " <<sum3; } }
```
***
__Work experience__
Стажировка на позиции верстальщика
***
__Education__
Algoritmika python
IITU
***
__English lvl__
B2
