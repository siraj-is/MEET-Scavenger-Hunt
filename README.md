# 🗝️ 404: Key Not Found
![404-error](https://github.com/user-attachments/assets/c702f2c2-4263-4fc5-b2b0-f5680f5e3be4)

Lill has lost her room key somewhere in Neve Shalom, and it’s up to you to find it.

All we know is this:
The last time Lill remembers having the key was in the cafeteria. So naturally, that’s where the search begins.

After a careful sweep under the tables, behind the coffee machine, even near the suspiciously loud microwave you come up empty-handed. The key is definitely not here.

But just as you're about to leave, someone calls out to you.

Well… not someone.
Something.

A burnt piece of toast sitting on a plate turns toward you and says:

“Psst. I saw a TA take the key. But I’m not telling you who it was…
not until you fix my code.”

It wiggles slightly, as if pointing toward the strange snippet of broken code below.

Your mission begins here.
To move forward in the hunt and learn which TA took Lill’s key, you must debug the toast’s code.

Good luck, and welcome to Step 1.

## Step 1: Fix the Toast’s Code

To learn which TA took the key, you must debug the code provided.
Solve the challenge, identify the TA, and unlock the next step.

```python
# Debug and fix this code so it reveals the TA's name!

# This list includes the TA's name, it might be ciphered...
TA_Name_List = ['!', 38, 101, 97, 'e', 35, 114, 37, 71, 36]

# Step 1: Convert every number to a character
# Hint: remember the ASCII table?
converted = ""
for char in TA_Name_List:
    converted += chr(char)
print("After converting numbers:", converted) # Try running the code here, does it work?

# Step 2: Remove all 'e's in the list.
e_removed = converted.replace("e", "")
print("After removing 'e':", e_removed)

# Step 3: Replace all 'r's with 'b's.
step3 = e_removed.replace("b", "r")
print("After replacing the 'r's:", step3)

# Step 4: The letter 'i' is upside down… flip it back?
step4 = ""
# Make sure to print to can see if it works

# Step 5: Remove all remaining symbols (&, #, $, etc...)
try:
    clean = ""
    for ch in step4:
        if ch.isalpha(step4):
            clean += ch
    print("After removing symbols:", clean)
except:
    print("Whoops something wrong happened")

# Uncomment the lines below to see the name of the TA

# # Step 6: The letters might be out of order...let's arrange them properly!
# final_name = "".join(sorted(clean))
# print("The TA is..." + final_name + "!!!")
```

## Step 2: Find the TA

Once you know which TA has the key, go find them in Neve Shalom and ask for it.
However the TA might have a request.
If you complete their request, they might give you the next clue.

### Lambda Minilab
```python
students = [
    {"name": "Razi",  "score": 88},
    {"name": "Eitan", "score": 73},
    {"name": "Roni",  "score": 95},
    {"name": "Ram",   "score": 60},
    {"name": "Amal",  "score": 82}
]
```
Using lambda functions with Python’s built-in tools (sorted, filter, map), complete the following tasks:
   1. Sort the students by score
   2. Filter students who scored above 75
   3. Create a new list of uppercase names


## Step 3: Solve the Crossword Cipher

There’s a hidden word inside the crossword puzzle. Decode it using the pattern:

A2[0] D3[4] D1[3] A5[2] D4[6]

`Hint: What might the A and D stand for in the puzzle?`


Once you uncover the hidden code you are ready to put it on the great decoding machine found in the first floor of the library
