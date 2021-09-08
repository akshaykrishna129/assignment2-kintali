# Akshay Krishna Kintali
---
>*Interesting facts about myself
>>I am from India .I have done my under graduation in Computer science and Engineering course .My interests are  watching movies and listening music and also i love exploring myself by visiting to different places.

![Mypicture](akshaykrishnaa.jpg)

---

# This table includes the food items that everyone should try.It tastes very good and also healthy.
---
| Item | Location | Price |
| ---| ---| ---: |
| Biryani | Godavari | $10 |
| Burger | Burger king | $14 |
| Haleem |  Pista House | $17 |
| Samosa | Swagat | $7 |

---

>"Always remember that you are absolutely unique. Just like everyone else." - *Margaret Mead*
>
>"Do not go where the path may lead, go instead where there is no path and leave a trail." - *Ralph Waldo Emerson*

---

# Area of simple polygon

>In geometry, the area is defined as the region occupied inside the boundary of a two-dimensional figure. Therefore, the area of a polygon is the total space or region bound by the sides of a polygon.[Area of simple polygon](https://www.storyofmathematics.com/area-of-polygon)

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}

```
[code source](https://cp-algorithms.com/geometry/area-of-simple-polygon.html)












