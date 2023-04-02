# FizzBuzz in one python expression | py-fizzbuzz-one-line

```py
print(str([((('','Fizz')[x%3==0],str(x))[('','Fizz')[x%3==0]==''],('','Fizz')[x%3==0]+'Buzz')[x%5==0] for x in range(1,100)])[1:-1].replace('\'','').replace(',', '\n\b'))
```