
## Checklist
HTML 표준의 역사는 어떻게 될까요?
>1990년대 '팀 버너스 리'가 처음으로 설명을 공개했다. 초기에는 18개의 태그만 존재 하였고, 이후로 쭉쭉 발전하였다.

HTML 표준을 지키는 것은 왜 중요할까요?
>어떤 브라우저를 사용하던, 누가 개발을 하던 상관없이 문제의 발생을 최소화 하기 위해서 이다.

XHTML 2.0은 왜 세상에 나오지 못하게 되었을까요?
>XHTML2.0은 하위 호환이 되지 않았고, HTML5는 하위 호환이 가능했기 때문이다.

HTML5 표준은 어떤 과정을 통해 정해질까요?
>W3C의 정기적인 컨소시엄을 통해 지난 10년간 80여개의 W3C 권고안을 발표하였다. 또한 열린 포럼, 심포지엄을 통해 사용자의 불편을 수용하고 차기 표준안에 반영할 수 있도록 지속적인 활동을 수행한다.

브라우저의 역사는 어떻게 될까요?
>Internet Explorer가 2008년 까지는 70%였으나 현재는 크롬이 제일 높다.

Internet Explorer가 브라우저 시장을 독점하면서 어떤 문제가 일어났고, 이 문제는 어떻게 해결되었을까요?
>기능 개선이 거의 이루어지지 않았고, HTML웹 표준을 이용하지 않았으며, Active X로 기능확장을 하여 호환성이 떨어졌다. 새로운 브라우저의 등장으로 해소되었다.

현재 시점에 브라우저별 점유율은 어떻게 될까요? 이 브라우저별 점유율을 알아보는 것은 왜 중요할까요?
>크롬이 가장 높고 엣지 등이 높은 점유율을 차지하고 있다.<br>
크로스 브라우징을 대비하기 위해서

브라우저 엔진(렌더링 엔진)이란 무엇일까요? 어떤 브라우저들이 어떤 엔진을 쓸까요?
>렌더링이란 브라우저 화면에 내용을 그리는 것<br>

|브라우저|엔진|
|:--|:--|
|Internet Explorer|Trident|
|FireFox|Gecko|
|Safari|Webkit|
|Chrome, Opera, Edge|Bilnk(a fork of Webkit)|

모바일 시대 이후, 최근에 출시된 브라우저들은 어떤 특징을 가지고 있을까요?
>모바일환경에 필요한 블루투스 컨트롤이나 자이로 센서 기능등 브라우저의 기능이 확장되었다.

HTML 문서는 어떤 구조로 이루어져 있나요?
>HTML 문서의 시작은 `<html>` 태그로 시작하고 `</html>` 태그로 끝납니다. · HTML 문서 내부는 `<head>` 태그와 `<body>`태그로 이루어져있습니다.

`<head>`에 자주 들어가는 엘리먼트들은 어떤 것이 있고, 어떤 역할을 할까요?
>* HTML의 메타 데이터가 포함
>* `<meta>`태그의 요소로 charactor인코딩, author, comment 추가가능
>* `<title>` 제목태그
>* `<link>` favioous 및 css 참조

시맨틱 태그는 무엇일까요?
>의미가 있는 태그, html의 태그에 보다 명확한 의미를 부여해준 태그를 의미한다.

시맨틱 엘리먼트를 사용하면 어떤 점이 좋을까요?
>검색엔진 최적화, 웹 접근성 등

`<section>`과 `<div>`, `<header>`, `<footer>`, `<article>` 엘리먼트의 차이점은 무엇인가요?
>* section : 논리적으로 관계 있는 문서 혹은 요소를 분리 할 때 사용한다. 서로 관련된 내용을 묶는데 쓴다고 볼 수 있다.
>* article : 내용이 독립적으로 존재할 수 있는 것들이다.
>* div : 논리적인 관계와 상관없이 그냥 분리하고 싶을 때 사용한다.

블록 레벨 엘리먼트와 인라인 엘리먼트는 어떤 차이가 있을까요?
>* 인라인 : text 크기만큼만 공간을 점유하고 줄바꿈을 하지 않는다.
>* 블록 : 무조건 한 줄을 점유하고 있고, 다음 태그는 무조건 줄바꿈이 적용된다.