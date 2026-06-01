# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0
with open('story.txt','r') as file:
    contents = file.readlines()

    for i in contents:
        if i[0]=='T':
            count+=1
    file.close()
print("No of lines starting with T is:",count)

```
### story.txt
```
Riya loved watching the stars every night.

One evening, she noticed a bright light moving across the sky.

Curious, she followed it to a nearby hill.

There she found a tiny glowing bird trapped in a bush.

The bird spoke and thanked her for helping.

It explained that it came from a magical world above the clouds.

As a reward, it gave Riya a shining feather.

The feather could light up whenever someone needed help.

Riya used it to guide lost travelers and help her neighbors.

Soon, everyone in the village admired her kindness.

Years later, Riya realized that the bird's greatest gift was not the feather, but the lesson that helping others brings true happiness.

```
## Output
<img width="809" height="62" alt="image" src="https://github.com/user-attachments/assets/d72712b6-cdd7-4249-a926-3cee7054dadd" />

## Result
