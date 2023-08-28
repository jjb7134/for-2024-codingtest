# 알고리즘

```python
# 10950
t = int(input()) #횟수 입력

for _ in range(t): #횟수만큼 반복
  a,b = map(int, input().split())
  print(a,b)

#25304 영수증

# 가격입력받기
p = int(input())
# 갯수 입력받기
m = int(input())
# 총 금액 초기화
total=0

# 반복문 돌리자
for i in range(m):
    a,b = map(int,input().split())
    total+=a*b

# 금액 일치하는지 확인해주기
if total==p:
    print('Yes')
else:
    print('No')
```