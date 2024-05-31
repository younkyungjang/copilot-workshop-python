# GitHub Copilot Chat

## 1. Try using slash commands in the chat window

We will use the code from Workshop1.

### Step 1-1. help
`/help`

### Step 1-2. explain
`explain`

Let's try adding some context.
Pay attention to the reference. If you highlight it, that part will be used as the context.

### Step 1-3. fix
Let's intentionally make a mistake in the function of Workshop1 and try to fix it.<br>

Example  
```python
def generate_locker_matrix(N, M):
    locker_matrix = []
    for i in range(N):
        locker_matrix.append([])
        for j in range(N):
            locker_matrix[i].append(random.randint(1000, 9999))
    return locker_matrix
```

`/fix`

Try inserting the code that appears.

### Step 1-4. test
Let's create a test code for the function of Workshop1.

`/tests`

Try inserting the code that appears, or create a new file and run it.

## 2. Try using inline chat
We will use the code from Workshop1.

### Step 2-1. fix
Let's intentionally make a mistake in the function of Workshop1 and try to fix it.

`/fix`

Try inserting the code that appears.

### Step 2-2. fix
Let's intentionally make a mistake in the function of Workshop1. Let's see if it can be fixed from the sparkle icon.

## 3. Code changes
### Step 3-1. Specification change
Let's change the specification of the function of Workshop1.

Example  
```
I want to change it to a five-digit integer
```

### Step 3-2. Refactoring
Let's change the specification of the function of Workshop1. Example

Example  
```
Implement the same logic without using a for loop
```
