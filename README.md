## ALGORITHM
Code
```python
arr = [5,7,8,4,3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2== 1:
        indexOfOdd.append(i)
print(indexOfOdd)
```
Ouput `ybaB olleH`

## Presidential Speech Reversal Program
Code
```python
text ="Hello Baby"

reverseText = ""
for index in range (1,len(text) + 1):
    reverseText += text[-index]
print(reverseText)
```
Ouput: `ybaB olleH`
## Average of number in list
Code
```python
arr = [5,7,8,4,3]
average = 0
sum = 0
for value in arr:
    sum += value 
average = sum / len(arr)
print(average)
```
Output `5.4`
## Simple Array Dictionary — President Version
Code
```python
arr = [
    {'name': 'bopha', 'age': 18},
    {'name': 'thida', 'age': 12},
    {'name': 'kanha', 'age': 16}
    ]
for dics in arr:
    print(dics['name'])
```
Output: `bopha thida kanha`
## Sum numbers in array
Code
```python
arr = [5,7,8,4,3]
sum = 0
for value in arr :
    sum += value 
print(sum)
```
Output:`27`
## find sum value of array
Code
```python
arr = [5,7,8,4,3]
for value in arr:
    if value % 2 == 0:
print(value)
```
Output: ` 8 4 `
## Minimum numbers of array
Code
```python
arr = [10, 40, 20, 4, 3]
min = arr [0]
for value in arr:
    if value < min :
        min = value
print(min)
```
Output: `3`

## Move one step to right
Code
```python 
arr = [0,0,1,0,0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i + 1]=1
        isFound = True
print(arr)
```
Output: `[0,0,0,1,0]`

## Move one step to right
Code
```python 
arr = [0,0,1,0,0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i - 1]=1
        isFound = True
print(arr)
```
Output: `[0,1,0,0,0]`
## Maximun number of array
Code
```python
arr = [10, 40, 20, 4, 3]
max = arr[0]
for value in arr:
    if value > max:
        max = value
print(max)
```
> Output: `40`
## Sum value in row
Code
```python
arr2D = [
    [1,2,3],
    [4,5,6],
    [7,8,9],
]
sum = 0
arr = []
for row in range(len(arr2D)):
    for col in range(len(arr2D[row])):
        sum += arr2D[row][col]
    arr.append(sum)
    sum = 0
print(arr)
```
Output: `[6,15,24]`