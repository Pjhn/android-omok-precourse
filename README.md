# android-omok-precourse

### 오목게임

두 사람이 번갈아 돌을 놓아 가로나 세로 대각선으로 
다섯 개의 연속된 돌을 먼저 만들면 승리하는 게임

## 구현 기능

1. 돌 놓기
- 사용자가 터치한 위치에 돌을 놓기
- 돌이 겹치지 않도록 하기 (2차원 리스트로 체킹)

2. 플레이어 전환
- 흑돌과 백돌 차례를 번갈아가며 두기 (착수시, 게임결과 체크, 플레이어의 턴 변경)
- 현재 플레이어 표시 

3. 승리 조건 확인
- 5목이상 연속된 돌이 있을 때 승리 판정 (렌즈룰 고려 x)
- 착수 지점 기준으로 가로 세로 대각선 방향(4*2) 체크 

4. UI
- 현재 플레이어 표시
- 게임 결과 표시 (ex)"검정 승!" 화면에 표시)
- 게임 리셋( 다시하기 )

