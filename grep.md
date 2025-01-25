it is useful in finding patterns. it is case sensitive

grep + pattern + filename


```grep -r 'happines' a.txt```
recursively find

```grep -icnw 'happines' a.txt```
count all patterns. i is for all relevant patterns
n is  for line number. all options can be given together
w-> single word

```grep 'happines' a.txt -iB2 -A3```
happiness k bad wali 3 lines and happines k phly 2 lines output mi ain 
