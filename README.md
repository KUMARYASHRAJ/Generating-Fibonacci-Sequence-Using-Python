# Generating-Fibonacci-Sequence-Using-Python

fib(num):
  a = 0
  b = 1
  if num<0:
    print("Enter a valid Number!")
  elif num==1:
    print(a)
  else:
    for i in range(2, num):
      c = a + b
      a = b 
      b = c
      if c<=num:
        print(c)
      else:
        break

fib(100)










