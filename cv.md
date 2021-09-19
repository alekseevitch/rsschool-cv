# ANDREI NAGORNYI #

### Contact ###
* Location: Rechitsa, Belarus
* Phone: +375(44)7753008
* Email: <a.a.nagornyj@gmail.com>
* [Telegram](https://t.me/alekseevitch)
* [GitHub](https://github.com/alekseevitch)
***
### Education ###
* 2019-until now: third year student at Information Systems an Technologies in university GSTU, Gomel.
* 2020: Self-education: Courses HTML, CSS, JavaScript on Sololearn.
***
### Experience ###
I do not have really experience in developement, but i wantit to get it.
***
### Skills ###
In process of education in university I am studying this technologies:
* C
* C#, ASP.NET
* SQL
* HTML, CSS, JS
***
### Code Examples ###

``` C++
   float simpson (float (*F_x)(float), float a, float b, float n)
{
   float h = (b - a) / n;
   float res;
   cout << "\nAccuracy h="<< h << "\n" << endl;
   float sum1 = 0.0;
   float sum2 = 0.0;
   int i;
   for(i = 0;i < n;i++)
      sum1 += F_x(a + h * i + h / 2.0);
   for(i = 1; i < n; i++)
      sum2 += F_x(a + h * i);
      res = h / 6.0 * (F_x(a) + F_x(b) + 4.0 * sum1 + 2.0 * sum2);
   return res;
}
```

```javascript
function usdcny(usd) {
  let cny = 6.75 * usd;
  return (`${cny.toFixed(2)} Chinese Yuan`);
}
```
***