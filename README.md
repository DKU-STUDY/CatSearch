원본 저장소 링크는 가능하면 보지 마세요. 어려울 경우 다른 구성원의 저장소를 보거나
자신의 저장소 issue 에다가 질문해주세요.

제가 미션을 내드릴건데. 꼭 좋은 미션은 아니에요. 
더 좋은 방법이 있다면 개선해보세요.

공부할 내용들은 꼭 자신의 저장소의 wiki 혹은 readme.md 파일로 정리하여 올려주세요.
그리고 저에게 답은 없으니, 마음껏 연구해보세요.

각자 개인의 진도를 나갑니다. 스스로 하고싶은 만큼 공부하세요.

## github 저장소 [:link:](https://github.com/DKU-STUDY/CatSearch)

## Pull Request
- 제목 : `step번호` 
- 하나의 스텝이 끝나면 merge 를 합니다.

## 커밋 규칙
1. 작업은 `stepXX` branch 를 새로 생성하여 작업합니다.
1. 커밋을 하고 원격 저장소의 stepXX branch 에 push 합니다.
1. stepXX -> 'github ID' 브랜치 에 대한 pull request 를 작성합니다. asignee 에 'eyabc'를 등록합니다.
1. 제가 리뷰해 드립니다.

### 커밋 이름 규칙
커밋을 잘 쪼개서 사용하는 습관을 들여야 되기 때문에
제가 초기에는 단계를 나누어 드립니다. 인텔리제이를 잘활용해보세요.

feat: 단계 이름

예시) feat: 파일을 로컬에 생성

만약에 수정하였을 경우

예시) fix : 오타 수정  
이런식으로 작성합니다. 

## step01
한 레파지토리에 자신의 이름의 브랜치를 만든다음   
자신의 브랜치에서 step 가지를 생성하는 방법을 시도해 보는것도 좋은것 같아 방법을 바꾸게 되었습니다  
브랜치 여러개 쓰다보면 실수도 할 수 있는데, 실전에서, 브랜치 실수에 대한 대응력을 키워보는 효과도 있다고 생각합니다.  
자신의 로컬 터미널에 

```shell script
git init;
git remote add origin https://github.com/DKU-STUDY/CatSearch
git pull origin master;
git checkout -b "github ID"
git checkout -b "stepXX"
```

- step01 branch 를 새로 생성합니다.
- step01 브랜치로 checkout 하여 작업하기
1. 파일을 로컬에 생성
    - index.html 생성
    - src 폴더 생성
    - src/App.js
    - src/main.js

- step01 -> githubID 브랜치로 PR 하기
