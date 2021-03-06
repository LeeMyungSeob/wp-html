이번 강의에서는 html문서와 관련된 기본적인 태그를 배웠습니다. 우선 <h1~6>으로 글자크기를 다양하게 쓰는 방법을 배웠습니다. 그리고
<head>와<body>를 통해서 문서의 머릿말과 내용을 적는 방법을 배웠습니다. 글자와 관련된 태그로는 문단을 나타내는<p>와 줄바꿈을 해주는
<br>, 수평선을 긋는 <hr>이 있습니다. 페이지애에서 이동을 위해서는 <a href="">를 사용해야 합니다.
목록관련 태그로는 순서가 없는 목록을 만들어주는 <ul>, 순서가 있는 목록을 만들어주는 <ol>, ul또는 ol태그 내부에서 사용하며 목록의 아이템을 나타내는 <li>가 있습니다.
테이블을 만들기위해서는 <table>안에 태그를 써야합니다. 표의 제목은 <caption>을 사용하고, 표의 헤더는 <thead>를 사용하고, 표의 몸체를
만들기 위한 태그는 <tbody>, 표의 푸터를 만들기 위해서는 <tfoot>을 사용합니다. 표의 행을 생성하기 위해서는 <tr>을 사용하고, 표의 제목
cell을 생성하기 위해서는 <tr>안에서 <th>를 사용해야합니다. 표의 데이터 cell을 생성하기 위해서는 <td>를 사용합니다. 행의 크기를 지정
하기 위해서는 rowspan, colspan속성을 사용해서 셀병합을 사용합니다. 
공간 분할을 위해서는 block형시의 공간을 생성하면 <div>를 사용하고, inline형식의 공간을 만들기 위해서는 <span>태그를 사용합니다. 이지를 넣기 위해서는 <img>를 사용합니다. 속성으로는 이미지의 주소를 지정 해주는 src, 이미지를 로드할 수 없을 경우 나오는 alt, 이미지의 넓이와 높이를 지정하는 width height이 있습니다. 오디오 태그는 <audio>를 사용합니다. 속성으로는 음악의 경로를 지정하는 src, 음악을 재생하기 전에 모두 불러올지 지정하는 preload, 자동재생 여부를 결정하는 autoplay, 반복재생 여부를 지정하는 loop, 음악 재생 도구 출력 여부를 지정하는 controls가 있습니다. 비디오 태그는 <video>를 사용하고 속성은 오디오와 유사합니다. 오디오와 다르게 추가되는 속성은 동영상 준비 중일 때 나오는 이미지를 재생하는 poster, 동영상의 너비와 높이를 지정해주는 width와 height가 있습니다. 
입력 양식 태그는 <form>안에 태그를 넣어야만 합니다. <input>태그는 입력을 받기 위한 태그입니다. 그 속성으로는 입력 양식의 종류를 결정하는  type, 서버로 양식을 전송할 때 각 입력항목을 구분하기 위한 이름값을 설정하는 name, 사용자가 값을 입력하지 않았을 때 안내글을 작성하는 placeholder, 입력 양식을 비활성하는 disbled, 입력 양식의 값인 value 등이 있습니다. 
사용자에게서 여러 줄의 텍스트를 입력받기 위한 태그는 <textarea>입니다. <textarea>의 속성으로는 태그의 너비와 높이를 지정해주는 cols, rows가
있고, 대부분의 속성은 input에서 사용했던 속성들과 비슷합니다. 여러개의 목록에서 몇 가지를 선택하게 해주는 태그는 선택 양식을 생성해주는
<select>, 옵션을 그룹화해주는 <optgroup>, 선택할 수 잇는 옵션을 생성하는 <option>이 있습니다. 여러 옵션을 선택할 수 있게 해주는 multiple말고는 대부분 input의 속성과 비슷합니다. 