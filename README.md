# Yonsei-University-Thesis-Template
연세대학교 기계공학과 국문 석사학위논문 작성 템플릿입니다. 기계공학과에서 따로 사용하는 양식은 없으며 [일반대학원에서 안내하는 양식](https://graduate.yonsei.ac.kr/graduate/academic/notice_haksa.do?mode=view&articleNo=28347&article.offset=20&articleLimit=10)을 따르는 것을 권고하고 있습니다. (2021.07. 기준)


## 문서 빌드
[Overleaf](https://www.overleaf.com/)에서만 테스트하였습니다. TeXLive와 같은 Stand alone 프로그램에서는 빌드 테스트를 해보지 않았습니다. Overleaf 프로젝트에 파일들을 임포트하여 사용하시길 권장드립니다.

## 파일 설명
```
contents/             // 본문 작성 파일 관리
  abs-english.tex     // 영문 초록
  abs-korean.tex      // 국문 초록
  ack.tex             // 감사의 말
  acronyms.tex        // 약호
  ch1-intro.tex       // 본문 1
  ch2-related.tex     // 본문 2
  ch3-system.tex      // 본문 3
  ch4-result.tex      // 본문 4
  ch5-conclusion.tex  // 본문 5
figures/              // 이미지 파일 관리
approval.pdf          // 인준서 스캔 이미지
main.tex              // tex 메인 파일
reference.bib         // 참고문헌
yonseiThesis.sty      // 학위논문 템플릿 정의
```

## 사용법
### `main.tex` 파일 134번 째 줄 부터 나오는 메타데이터를 입력합니다.
```
\titleEng             // 영문 제목
\titleKr              // 국문 제목
\authorNameEng        // 영문 이름
\authorNameKr         // 한글 이름
\affilDeptNameEng     // 학과 영문 이름
\affilDeptNameKr      // 학과 한글 이름
\affilSchoolNameEng   // 학교(School) 영문 이름
\affilSchoolNameKr    // 학교(School) 한글 이름
\affilUnivNameEng     // 학교(University) 영문 이름
\affilUnivNameKr      // 학교(University) 한글 이름
\advisor              // 지도교수님 성함. 2개까지 적을 수 있음
\submitDate           // 논문 제출일

\approvalFile         // 인준서 스캔 파일 경로. 교수님께 인준 받은 후 스캔본을 입력. 파일을 입력하지 않으면 비어있는 인준서가 생성되므로 이를 출력하고 서명 받은 후 파일을 입력하시면 됩니다.
\approvalDate         // 인준 날짜

\keywordsKr           // 국문 초록 키워드
\keywordsEng          // 영문 초록 키워드
```

### 메타데이터 입력 후 본문 작성
`main.tex` 파일 166번 째 줄 부터 나오는 본문 챕터 구성을 입력합니다. `contents` 폴더 내의 초록, 감사의말, 약호, 본문 내용을 입력합니다. 약호는 본문에서 언급하지 않으면 약호표에 나타나지 않습니다.

