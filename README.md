odd_seq = []

for i in range(101):
    if i % 2 != 0:
        odd_seq.append(i)

sum_square = 0
for num in odd_seq:
    sum_square += num ** 2

print(sum_square)
