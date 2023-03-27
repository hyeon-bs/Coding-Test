<u>깔끔한 배열</u>
MAP = [list(map(int, input().split())) for _ in range(int(input()))] 

<u>N에 첫번째 값을 넣고 그 뒤는 list(* 사용)</u>
N, *arr = map(int, input().split())

<u>문자열을 한글자씩 배열에 저장</u>
arr = [list(input()) for _ in range(N)]

