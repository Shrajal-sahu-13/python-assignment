# python-assignment
for num in range(100, 1000):
  temp = num
  a = num // 100
  b = (num // 10) % 10
  c = num % 10
  if a == b or b == c or c == a:
    print(num)


1000--10000

for num in range(1000, 10000):
  temp = num
  a = num // 1000
  b = (num // 100) % 10
  c = (num // 10) % 10
  d = num % 10
  if a == b or a == c or a == d or b == c or b == d or c == d:
    print(num)
