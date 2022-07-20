# 박스 모델
* width: 200px;
* height: 100px;
* boarder: 4px dotted blue;(테두리 선)
* boarder-radius: 10px;(모서리 둥글게 깍기)
* margin: 20px;(요소 외부 여백)
* padding: 20px;(요소 내부 여백)
* box-sizing: border-box;(지정한 width와 height 유지하면서 내부 여백과 테두리 선이 들어감)
* box-shadow: 10px 20px 10px rgba(0,0,0,.3);(그림자)
* opacity: 0.5;(불투명도)

# 글꼴(font), 문자(text)
* lineheight(줄의 높이): 2(글자 크기의 2배);
* color: yellowgreen;
* font-size: 20px(기본 16px);
* font-style: italic;
* font-weight: bold;
* text-align: center;
* text-decoration: underline;

# 배경
* background-color: orange;
* background-image: url("이미지 주소");
* background-size: 80px; # 이미지 크기 조절
* background-repeat: no-repeat;(기본 repeat)
* background-position: center right; # 왼쪽에서의 거리와 위쪽에서의 거리로도 이미지 위치 조절 가능(20px 50px)

# 배치
* position: absolute;(absolute는 부모요소 기준으로 배치된다는 뜻이며 기준이 되는 부모요소의 position은 relative여야 된다)
* left: 40px;
* bottom: 100px;

# 플렉스(수평정렬)
* display: flex;(수평 구조로 만들고 싶은 아이템의 부모 요소에 입력)(자식에만 영향을 준다)
* justify-content: flex-end;(수평정렬)(기본값인 flex-start는 왼쪽, flex-end는 오르쪽에서 정렬, center는 가운데 정렬)
* align-items: center;(수직정렬)

# 전환(요소의 전 상태와 후 상태를 자연스럽게 만들어준다)
* transition: 1s;

# 변환
* transform: rotate(45deg) scale(2);(2차원 변환)
* transform: perspective(300px) rotateX(45deg);(원근법 적용 후 x축을 기준으로 3차원 변환)

# 띄움
# 애니메이션
# 그리드
# 다단
# 필터
