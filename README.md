### Hi there 👋

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
# assignment02-pitchala

## Tirumala Swathi Pitchala
###### PARIS
#### PARIS Trocadéro at **sunrise**,__sunrises__ is a big open area, right in front of the Eiffel Tower, across the Seine river.The second point that makes it a good choice for Paris sunrise location is the fact that sunrise is the only time of day where this spot is empty. During the day, it gets absolutely crowded.
---
## Vacation
1. Direction from Marryville city to Colrado
   1. By car we should drive from marryville to kansa city about 2hours.
   2. from there started drive for next 9hours to denver.
   3. stayed overnight and started to coloradfo for about 2hours to reach destination.
2. Favouriate places to visit in Colrado
   1. Garden of Gods
   2. Rocky Mountains
   3. Pikes peak

* Badminton
* Balls
   * vollyball
   * throwball

[AboutMe](https://github.com/s545402/assignment02-pitchala/blob/main/AboutMe.md)

---
# Recommend Food/Drinks 
The below table provides the list of Recommend food/drinks to try.

| **Food/Drinks**       |**Location** | **Price($)**|
| :-------------:| :------------: | :------: |
| oreo milkshake | guntur | 5|
|hyderabad briyani | hyderabad | 11|
|momos | hyderabad | 7 |
|noodles | guntur | 5 |
----
# Quotes :
> Love all, trust a few, do wrong to none. - *Shakespear*

> “Time is money” – *Benjamin Franklin* 
----
# Algorithm Choice

>A ternary search algorithm is a technique in computer science for finding the minimum or maximum of a unimodal function. A ternary search is an example of a divide and conquer algorithm (see search algorithm).

[ternary search] <https://en.wikipedia.org/wiki/Ternary_search>

```
def ternary_search(f, left, right, absolute_precision) -> float:
    """Left and right are the current bounds;
    the maximum is between them.
    """
    if abs(right - left) < absolute_precision:
        return (left + right) / 2

    left_third = (2*left + right) / 3
    right_third = (left + 2*right) / 3

    if f(left_third) < f(right_third):
        return ternary_search(f, left_third, right, absolute_precision)
    else:
        return ternary_search(f, left, right_third, absolute_precision)
```
<https://en.wikipedia.org/wiki/Ternary_search>


