# Python 정리

## *별 출력하기*

### *1. 중첩루프 사용*

`````python
for i in range(5): # 바깥쪽 루프  #행에 해당 세로의 크기
  for j in range(5): # 안쪽 루프  #열에 해당 가로의 크기
    print('j:', j, sep = '' end = ' ')
	print('i:', i, '\\n', sep = '')   
`````



### *2. 사각형으로 별 출력하기*

````` python
*****
*****
*****
*****
*****

for i in range(5) : 
  for i in range(5):
    print('*', end = '') 
  print()  # 아무 것도 지정 안 해도 \n 출력
`````



### *3. 계단식으로 별 출력하기*

`````python
*
**
***
****
*****

for i in range(5):
  for j in range(5):
    if j <= i :           #별이 행에 따라서 증가하므로 i를 기준으로 작성
      print('*', end= '')
  print()    
`````

### *4. 대각선으로 별 출력하기*

`````python
*
 *
  *
   *
    *


for i in range(5):
    for j in range(5):
        if j == i:
            print('*', end='')
        else:   #행과 열이 같지 않을 땐 공백으로 두어야 함
            print(' ', end='')
    print()
`````

