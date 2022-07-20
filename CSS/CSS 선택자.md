# CSS 기본문법
* 선택자{
    속성: 값;
  }

# CSS 선택자
* 전체(*) 선택자
* 태그 선택자
* (.)클래스 선택자
* (#)아이디 선택자

# 복합 선택자
* 오른쪽에서 왼쪽으로 해석
* 일치 선택자(ABCXYZ): 동시에 만족
* 자식 선택자(ABC>XYZ): 선택자 ABC의 자식요소 XYZ 선택 
* 하위 선택자(ABC XYZ): 선택자 ABC의 하위요소 XYZ 선택
* 인접 형제 선택자(ABC+XYZ): 선택자 ABC의 다음 형제요소 XYZ 하나를 선택
* 일반 형제 선택자(ABC~XYZ): 선택자 ABC의 다음 형제요소 XYZ 모두를 선택

# 가상 클래스 선택자
* HOVER(ABC:hover): 선택자 ABC에 마우스 커서가 올라가 있는 동안 선택
* ACTIVE(ABC:active): 선택자 ABC에 마우스를 클릭하고 있는 동안 선택
* FOCUS(ABC:focus): 선택자 ABC가 포커스되면 선택
* FIRST CHILD(ABC:first-child): 선택자 ABC가 형제 요소 중 첫째라면 선택
* LAST CHILD(ABC:last-child): 선택자 ABC가 형제 요소 중 막내라면 선택
* NTH CHILD(ABC:nth-child(n)): 선택자 ABC가 형제 요소 중 (n)째라면 선택(n에 숫자가 아닌 n(0,1,2,..)을 넣을 수도)

# 가상 (인라인)요소 선택자
* BEFORE(ABC::before): 선택자 ABC의 내부 앞에 내용(content)을 삽입
* AFTER(ABC::after): 선택자 ABC의 내부 뒤에 내용(content)을 삽입

# 속성 선택자
* ATTR([ABC]): 속성(attribute) ABC를 포함한 요소 선택
* ATTR=VALUE([ABC="XYZ"]): 속성 ABC를 포함하고 값이 XYZ인 요소 선택
