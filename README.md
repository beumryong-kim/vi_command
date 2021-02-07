# vi_command
explain vi command

## vi 명령어 모음


#### 명령모드
|단축키|명령어 설명|
|:--:|:--|
|a|명령모드에서 누르면 뒤로 1칸 가진 뒤 insert mode|
|i|명령모드에서 누르면 뒤로 현재 위치에서 insert mode|
|shift + a|명령모드에서 누르면 맨 뒤로 이동 후 insert mode|
|shift + i|명령모드에서 누르면 맨 앞으로 이동 후 insert mode|
|cw|단어를 제거 후 insert mode|
|h j k l|좌 아래 위 오른쪽|
|shift + $|커서 맨 끝으로 이동|
|shift + ^|커서 맨 앞으로 이동|
|shift + v|visual line 으로 변경|
|d|1줄 삭제|
|x|1단어 삭제|
|yy|복사|
|p|붙여넣기|
|ctrl + f|다음 화면으로 이동|
|ctrl + b|이전 화면으로 이동|
|shift + j|다음줄 현재줄로 올리기|
|shift + d|현재 커서부터 지우기|
|visual line + =|라인 정렬|
|'{' or '}' + = + %|라인 정렬|
|shift + 8|같은 단어를 찾기|
|u|undo|
|ctrl + r|redo|

#### 입력모드
|단축키|명령어 설명|
|:--:|:--|
|:set paste|붙여넣기 모드로 변경|
|:set nopaste|붙여넣기 모드 취소|
|:%s/찾을문자열/변경할내용/|찾은 문자열 변경|
|:r + 파일명|해당 파일 내용 가져오기|
|:q|그냥 나가기|
|:q!|그냥 나가기(강제)|
|:wq|저장하고 나가기|
|:! + 명령어|명령어 실행|
