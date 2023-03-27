<u>깔끔한 배열</u><br>
'''
MAP = [list(map(int, input().split())) for _ in range(int(input()))]
'''
<u>N에 첫번째 값을 넣고 그 뒤는 list(* 사용)</u><br>
'''
N, *arr = map(int, input().split())
'''
<u>문자열을 한글자씩 배열에 저장
<span style="color:mint">list(input())</span>
</u><br>
'''
arr = [list(input()) for _ in range(N)]
'''
<u>배열을 하나로 출력
<span style="color:mint">"",join</span>
</u><br>
'''
arr = [1,2,3,4]
print("".join(map(str,arr)))
'''
