# CSS와 애니메이션  
## transform - 회전, 이동 웹 요소 변형  
### 2차원  
- translate(tx,ty) : 지정한 크기만큼 x축과 y축으로 이동  
- translateX(tx) : 지정한 크기만큼 x축으로 이동
- translateY(ty) : 지정한 크기만큼 y축으로 이동  
- scale(sx,sy) : 지정한 크기만큼 x,y축으로 확대/축소  
- scaleX(sx) : 지정한 크기만큼 x축으로 확대/축소  
- scaleY(sy) : 지정한 크기만큼 y축으로 확대/축소  
- rotate(각도) : 지정한 각도만큼 회전  
- skew(ax,ay) : 지정한 각도만큼 x,y축으로 왜곡  
- skewX(ax) : 지정한 각도만큼 x축으로 왜곡  
- skewY(ay) : 지정한 각도만큼 y축으로 왜곡  
### 3차원
- matrix3d(n,[,n]) : 4*4행렬을 이용해 이동과 확대/축소 회전 등의 변환을 저장  
- translate3d(tx, ty, tz) : 지정한 크기만큼 x,y,z축으로 이동  
- translateZ(tz) : 지정한 크기만큼 z축으로 이동  
- scale3d(sx, sy, sz) : 지정한 크기만큼 x,y,z축으로 확대/축소  
- scaleZ(sz) : 지정한 크기만큼 z축으로 확대/축소  
- rotate3d(rx, ry, rz, 각도) : 지정한 크기만큼 회전  
- rotateX(각도) : 지정한 크기만큼 x축으로 회전  
- rotateY(각도) : 지정한 크기만큼 y축으로 회전  
- rotateZ(각도) : 지정한 크기만큼 z축으로 회전  
- perspective(길이) : 입체적으로 보일 수 있는 깊이 값을 지정 
## transition - 전환 효과 만들기  
- transition-property : 대상 설정  
- transition-duration : 진행시간 설정  
- transition-timing-function : 속도 곡선 설정  
    - linear : 처음부터 끝까지 같은 속도로
    - ease : 처음에 천천히 점점빨라지고 마지막에 천천히끝남
    - ease-in : 시작을 느리게
    - ease-out : 느리게 끝남
    - ease-in-out : 느리게 시작하고 느리게 끝남
    - cubic-bezier(n,n,n,n) : 베지에 함수를 직접 정의해 사용 n에서 사용할 수 있는 값은 0~1  
- transition-delay : 지연시간 설정  
- transition : 모든 속성 한번에 정의  
## animation - CSS로 애니메이션 만들기  
- @keyframes - 중간지점 만들기 바꾸는 시점 설정  
- animation-delay : 지연시간 설정  
- animation-direction : 처음부터 시작할지 역방향으로 진행할지  
- animation-duration : 실행시간 설정  
- animation-fill-mode : 종료되었거나 지연되어 애니메이션이 실행되지 않는 상태일때 요소의 스타일 지정  
- animation-iteration-count : 반복횟수 지정  
- animation-name : @keyframes로 설정해 놓은 중간 상태의 이름을 지정  
- animation-play-state : 멈추거나 다시 시작  
- animation-timing-function : 속도 곡선 지정  
- animation : 위에 것들 한번에 정의  
## viewport  
> 뷰포트를 지정하면 접속한 기기 화면에 맞추어 확대하거나 축소해 표시할 수 있습니다.  
### 속성  
- width : 뷰포트 너비  
- height : 뷰포트 높이  
- user-scalable : 확대/축소 가능 여부  
- initial-scale : 초기 확대/축소 값  
- minimum-scale : 최소 확대/축소 값  
- maximum-scale : 최대 확대/축소 값  