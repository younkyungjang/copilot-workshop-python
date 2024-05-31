# GitHub Copilot Chat

## 1. Chatウィンドウでスラッシュコマンドを利用してみましょう

Workshop1のコードを利用します。

### Step 1-1. help
`/help`

### Step 1-2. explain
`explain`

コンテキスト追記してみましょう。
Referenceに注意してみましょう。ハイライトした場合はその部分をコンテキストにします。

### Step 1-3. fix
Workshop1の関数をわざと間違えたコードにして修正してみましょう。<br>
例
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

表示されたコードを挿入してみましょう。

### Step 1-4. test
Workshop1の関数のテストコードを作成しましょう。

`/tests`

表示されたコードを挿入するか、新規ファイルを作成して実行してみましょう。

## 2. インラインチャットを利用してみましょう

Workshop1のコードを利用します。

### Step 2-1. fix
Workshop1の関数をわざと間違えたコードにして修正してみましょう。

`/fix`

表示されたコードを挿入してみましょう。

### Step 2-2. fix
Workshop1の関数をわざと間違えたコードにして修正してみましょう。
キラキラアイコンから修正可能かどうかをみてみましょう。

## 3. コードの変更

### Step 3-1. 仕様変更
Workshop1の関数の仕様を変更してみましょう。
<br>例
```python
５桁の整数に変更したい
```

### Step 3-2. リファクタリング
Workshop1の関数の仕様を変更してみましょう。
<br>例
```python
forループを利用しないで同じロジックを実装
```
