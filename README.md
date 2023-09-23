k = input()
digits = " "
alphabets = " "
for i in range (len(k)):
  if k[i].isalpha():
    alphabets+= k[i]
  elif k[i].isdigit():
    digits+= k[i]

print(f"Digits are :- {digits}")
print(f"Alphabets are :- {alphabets}")
