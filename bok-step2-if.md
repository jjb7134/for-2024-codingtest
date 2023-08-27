오븐기

시간 계산한 부분을 앞으로도 참고해보자

```jsx
hour,min = map(int,input().split())
timer= int(input())

hour += timer // 60
min += timer % 60

if min>=60:
    hour+=1
    min-=60
if hour>23:
    hour-=24

print(hour,min)
```

2480 주사위 세개

```jsx
a,b,c = map(int, input().split())

if a == b == c:
    print(10000+a*1000)
elif a==b:
    print(1000+a*100)
elif b==c:
    print(1000+b*100)
elif a==c:
    print(1000+a*100)
else:
    print(max(a,b,c)*100)
```

회고 : 간단하게 생각해야되는데 잘 안되니 문제를 많이 풀어보는걸로….
