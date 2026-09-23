# Python-Test-Coding

1)
Write a Python program which accepts a sequence of comma separated 4 digit
binary numbers as its input and then check whether they are divisible by 5 or not.
The numbers that are divisible by 5 are to be printed in a comma separated
sequence.
Example:
0100,0011,1010,1001
Then the output should be:
1010

### Code
```
a=input().split(",");
for i in a:
  b=int(i,2);
  if(b%5==0):
    print(i);
```

### Output
<img width="840" height="297" alt="image" src="https://github.com/user-attachments/assets/9c8d6515-7832-4c08-ab49-537fb39a7a7c" />

2)
Write a Python program that accepts a sentence and calculate the number of
letters and digits.
Suppose the following input is supplied to the program:
hello world! 123
Then, the output should be:
LETTERS 10
DIGITS 3

### Code 
```
str=input();
letter=0;
number=0;
a=len(str)
for i in range(a):
  if str[i].isalpha():
    letter+=1
  else:
    number+=1;
print("LETTERS ",letter);
print("DIGITS ",number);
```
### Output
<img width="812" height="267" alt="image" src="https://github.com/user-attachments/assets/f6153fa3-5700-4f6a-8c13-96e779ad0df6" />

3)
Write a program which can compute the factorial of a given numbers.The
results should be printed in a comma-separated sequence on a single
line.Suppose the following input is supplied to the program:8
Then, the output should be:40320

### Code
```
num=int(input());
fact=1;
for i in range(1,num+1):
  fact=fact*i;

print(fact);
```
### Output
<img width="756" height="223" alt="image" src="https://github.com/user-attachments/assets/e59942a1-c9f4-4ec2-8b29-4abed79aa30f" />
