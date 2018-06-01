# hw9
1) Чтобы удалить пустые строки я использовала регулярное выражение ^\n    
![alt-текст](https://github.com/chukalina/hw9/blob/master/1.PNG?raw=true)  
Этого оказалось недостаточно, поэтому я использовала регулярное выражение ^\s  
![alt-текст](https://github.com/chukalina/hw9/blob/master/1.2.png?raw=true)  
2) Чтобы найти все имена собственные, заканчивавшиеся на -слав, я использовала регулярное выражение:  
[А-Я][а-яѣ]+слав[а-яѣ]+  
Всего упоминаний 564  
![alt-текст](https://github.com/chukalina/hw9/blob/master/2.png?raw=true)  
3) Я использовал регулярное выражение: Нов.город+[^.?!;:-]
Всего упоминаний Новгорода нашела: 58
![alt-текст](https://github.com/chukalina/hw9/blob/master/3.png?raw=true)
