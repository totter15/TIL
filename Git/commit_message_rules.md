# 좋은 커밋 메세지를 위한 규칙들

최근에서야 제대로 된 커밋를 남기는것의 중요성을 알게되어 습관을 들이는 중이다. (깃허브의 잔디가 코드의 수정양이 아니라 커밋의 갯수로 채워진다는 걸 이제야 알게되었다...^^)

커밋을 남기려니 어느정도의 단위로 커밋을 쪼개고 어떤 언어로 메세지를 남겨야 하는지를 잘 모르겠어서 공부해 보았다.

<br/>

## 커밋 메세지의 7가지 규칙

[How to Write a Git Commit Message](https://cbea.ms/git-commit/)

1. 제목과 본문을 빈행으로 구분한다.
2. 제목을 50글자 내로 제한한다.
3. 제목 첫글자는 대문자로 작성한다.
4. 제목 끝엔 마침표를 넣지 않는다.
5. 제목은 명령문을 사용하며 과거형을 사용하지 않는다.
6. 본문의 각행은 72글자 내로 제한한다.
7. 어떻게 보다는 무엇과 왜를 설명한다.

<br/>

## 커밋 메세지 포맷

[AngularJS Git Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#heading=h.uyo6cb12dt6w)

```
<type>(<scope>):<subject>   ---(헤더)
<BLANK LINE>
<body>                      ---(바디)
<BLANK LINE>
<footer>                    ---(푸터)
```

[커밋 메세지 예시](https://github.com/angular/angular/commits/master)

제목과 본문 사이에 한 줄 공백을 넣을 경우 `git log --oneline`일때 제목만 보이게 된다. 본문은 설명이 필요할때 추가하며, 설명이 꼭 필요하지 않을 경우 한줄로 요약해서 적었을때 더 효율적일 수 있다.

`<footer>`는 `close #123`과 같이 참조 정보를 포함한다.

tip. commit message를 작성할 때 특정 명령어(`close,fix,resolve...` )로 이슈를 닫을 수 있다.

[이슈 닫기 키워드](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)

</br>

### type의 종류

`<type>`은 해당 커밋의 성격을 나타낸다.

- feat : 새로운 기능에 대한 커밋
- fix : 버그 수정에 대한 커밋
- docs : 문서 수정에 대한 커밋
- style : 코드 스타일 혹은 포맷등에 관한 커밋
- refactor : 코드 리팩토링에 관한 커밋
- test : 테스트 코드 수정에 관한 커밋
- chore : 그 외 자잘한 수정에 대한 커밋

<br/>

#### 참고

[좋은 커밋 메세지 작성하기위한 규칙들](https://beomseok95.tistory.com/328)

[좋은 git 커밋 메시지를 작성하기 위한 7가지 약속](https://meetup.toast.com/posts/106)
