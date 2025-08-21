# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```
n = int(input("Enter number of participants: ")) 
scores = list(map(int, input("Enter the scores: ").split())) 
unique_scores = list(set(scores)) 
unique_scores.sort()  
print("Runner-up score is:", unique_scores[-2])
```
## OUTPUT
![image](https://github.com/user-attachments/assets/0fbd6b00-84d7-4db7-94dc-201cb67ccda3)


## RESULT
```
Thus, the output is verified successfully
```
