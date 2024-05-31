# GitHub Copilot 채팅

## 1. 채팅 창에서 슬래시 명령어 사용해 보기

Workshop1의 코드를 사용할 것입니다.

### Step 1-1. 도움말
`/help`

### Step 1-2. 설명
`explain`

일부 컨텍스트를 추가해 보세요.
참조에 주의하세요. 강조 표시하면 해당 부분이 컨텍스트로 사용됩니다.

### Step 1-3. 수정
Workshop1의 함수에서 고의적으로 오류를 만들어 보고 수정해 봅시다.<br>
예시
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

### Step 1-4. 테스트
Workshop1의 함수에 대한 테스트 코드를 만들어 봅시다.

`/tests`

나타나는 코드를 삽입하거나 새 파일을 만들어 실행해 보세요.

## 2. 인라인 채팅 사용해 보기
Workshop1의 코드를 사용할 것입니다.

### Step 2-1. 수정
Workshop1의 함수에서 고의적으로 오류를 만들어 보고 수정해 봅시다.

`/fix`

나타나는 코드를 삽입해 보세요.

### Step 2-2. 수정
Workshop1의 함수에서 고의적으로 오류를 만들어 봅시다. 반짝이는 아이콘에서 수정할 수 있는지 확인해 보세요.

## 3. 코드 변경
### Step 3-1. 사양 변경
Workshop1의 함수의 사양을 변경해 봅시다.

예시  
```
다섯 자리 정수로 변경하고 싶습니다
```

### Step 3-2. 리팩토링
Workshop1의 함수의 사양을 변경해 봅시다.

예시  
```
for 루프를 사용하지 않고 같은 로직을 구현합니다
```
