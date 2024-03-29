# 메나모, Menamo
나와 모두를 위한 메모장이자 지식 데이터베이스

```text
■ 메나모

◎ 메나모란?
  - 메나모는 "메모, 나를 위한, 모두를 위한" 의 약자로 나와 모두를 위한 메모용 깃헙 저장소의 이름이자 메모 양식의 이름이다.
  - 이 메모는 메모 양식의 메나모를 설명하며 메나모로 쓰였고 쓰이고 있고 쓰일 것이다.

◎ 메나모의 목적
  - 메나모는 나의 메모를 작성하고 모두가 볼 메모를 작성하기 위해 만들어졌다. 따라서 메나모는 다음과 같은 목적을 추구한다.
  - 1. 메모장으로 작성하기 쉬울 것
  - 2. 메모장으로도 보기 쉬울 것
  - 3. 컴퓨터도 알아보기 쉬울 것

◎ 메나모의 기본 구조
  - 메나모는 줄 단위이다.
  - 메나모는 각 줄이 공백이거나 다음 구조를 가진다:  
    - [띄워쓰기 두칸 혹은 탭 문자의 연속] [머리글자] [띄워쓰기 한칸] [글]

    - 띄워쓰기 두칸 혹은 탭 문자의 연속: 문단의 계층구조를 나타낸다. 
    - 머리글자: 해당 줄의 유형을 나타낸다.
    - 띄워쓰기 한칸: 알아보기 쉽도록 추가되었다.
    - 글: 해당 줄의 내용을 나타낸다.

  - 만약 위 구조를 지키지 않는다면 해당 메모는 메나모가 아니다.
  - 만약 한 글이 다른 글을 포함한다면 그 하위글은 상위글보다 한 탭, 혹은 띄워쓰기 두칸이 더 들어간다.
  - 만약 문자나 글을 양식 검사에 포함하고 싶지 않다면 큰따옴표나 작은따옴표로 묶는다.
    - 주로 큰 따옴표는 복수의 문자를, 작은 따옴표는 단수의 문자를 감쌀 때 사용한다.
  - 메나모를 담은 파일은 확장자가 mie, mik, wik, mnm 중 하나여야 한다.
  - 메나모를 주장하나 양식 검사는 하지 않는 파일의 확장자는 메나모 확장자에서 m을 ps로 바꾼 것을 사용한다.
  - 메나모의 마지막은 빈 줄이야 한다.

◎ 메나모의 작성법
  - 글을 포함하는 기준은 "해당 글이 주변글과 같은 깊이의 정보를 가지고 있는지 아닌지" 이다.
  - 부분글이 너무 길어진다면 부분글을 나눈다. 만약 글이 너무 길어진다면 글을 파일로 나눈다. 파일이 너무 많아졌다면 디렉토리로 나눈다.
  - 한 주제로 메모를 만들 때 다음 방법을 권장한다.
    - 1. 수집: 주제와 관련된 모든 정보를 수집한다.
    - 2. 요약: 수집한 정보를 나름의 기준으로 분류할 범주를 만든다.
    - 3. 정리: 만든 범주에 따라 정보를 재기록하고 첨삭한다.
    - 수집과 요약은 숨긴 디렉토리(.menamo)에 기록하고 정리를 본 디렉토리에 기록한다.

◎ 줄의 유형
  - 주제: 메모의 주제을 나타낸다. 
    - 주로 메모지의 첫단에 쓰이며 글은 주로 파일의 제목이 된다.
    - 주제와 소주제는 그 어떤 것에도 포함되지 않는다.
  - 소주제: 각 문단의 주제를 나타낸다.
    - 주제와 소주제는 그 어떤 것에도 포함되지 않는다.
  - 내용: 주제, 소주제, 혹은 내용을 설명한다. 

◎ 머리글자
  - ■: 주제를 나타낸다.
  - ◎: 소주제를 나타낸다.
  - -: 내용을 나타낸다.
  - ->: 내용을 나타낸다. 주로 앞의 내용을 잇거나 결과를 나타낼 때 쓰인다.
 - ■, ◎ 와 같은 특수 문자는 각 운영체제에서 특수문자 입력하는 방법을 찾아본다.
  - 윈도우: 한글자음-한자
  - 리눅스: ctrl-shift 누르기 - u유니코드숫자 - ctrl-shift 떼기

◎ 글의 유형
  - 일반글: 일반적인 내용을 담은 글이다.
    - 조건: 나머지 유형의 조건에 포함되지 않는다.
  - 나열글: 나열할 때 쓰인다.
    - 조건: 문장의 첫 부분이 아래의 글자와 함께 ".(공백)", 혹은 ")(공백)"로 이루어져있다.
      - 아라비아 숫자 하나
      - 그리스 숫자 하나
      - 영어 알파벳 글자 하나 
      - 한글 알파벳 글자 하나
      - 기타 연속을 나타내는 알파벳 혹은 글자 하나
  - 예시글: 예시를 나타내는 글이다.
    - 조건: 예시글에 포함되거나 아래의 단어가 닫는 소괄호로 끝나거나 '.'와 공백문자로 끝난다.
      - 예, 예시
      - ex, i.e, e.g
      - 그 외 예시를 나타내는 약어
  - 제시글: 앞으로 나올 글의 주제를 미리 설명한다.
    - 조건: 대괄호로 줄이 감싸져있으며 각 내용은 ',', 혹은 "](공백)["으로 구분한다.
  - 표글: 표를 나타낼 때 쓰인다. 
    - 조건: 중괄호로 줄이 감싸져 있으며 각 셀의 내용은 ','로 구분한다.
  - 구분글: 글을 구분할 때 쓰인다.
    - 조건: 글이 "---"이랑 똑같다.
    - 표의 머리를 구분할 때도 쓰인다.
  - 확장글: 텍스트로 나타낼 수 없거나 나타내기 힘든 내용을 나타낼 때 쓰인다.
    - 조건: 글이 '<'로 시작해 '>'로만 끝나거나 '/>'로 끝난다. 만약 '>'로 끝난다면 꺽쇠괄호 사이의 내용을 '<'와 '/>'로 감싼 글이 나올 때까지 모든 양식 검사를 거치지 않는다.
    - 주로 쓰이는 태그는 다음과 같다.
      - link: 인터넷 링크를 나타낼 때 쓰인다. 
        - 링크는 path 속성으로 값은 url을 쓴다. 이름은 name 속성으로 나타낸다.
        - 간단한 설명은 comment 속성으로 나타낸다.
      - img: 이미지를 나타낼 때 쓰인다.
        - 경로는 path 속성으로 값은 상대경로, 혹은 url을 쓴다. 이름은 name 속성을 쓴다.
        - 간단한 설명은 comment 속성으로 나타낸다.
      - code: 코드를 나타낼 때 쓰인다.
        - 임의의 파일경로는 filename을, 이름은 name을, 유형은 type을 사용한다.
        - 간단한 내용은 contents를 사용하며 간단한 설명은 comment 속성으로 나타낸다.
      - file: 파일을 나타낼 때 쓰인다.
        - 경로는 path 속성으로 값은 상대경로, url을 쓴다. 간단한 설명은 comment 속성으로 나타낸다.

```
