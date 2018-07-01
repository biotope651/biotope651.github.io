---
layout: post
title: "github 포스트 작성"
featured-img: what-is-github
categories: [practice, post]
---

##### 바로가기
[clone repository](#cloneRepo)
[문서작성](#writeDoc)
[github에 올리기](#commitGithub)

<a name="cloneRepo"/>
## clone repository

```no-highligt
git clone https://github.com/biotope651/biotope651.github.io

-> github 저장소를 다운로드 한다.
```

<a name="writeDoc"/>
## markdown 문서 작성

```no-highligt
POST 작성시 Markdown 문법에 맞게 작성을 해아한다.

ex) 샘플문서의 시작은 아래와 같은 규칙으로 문서작성을 시작하고 있다.
---
layout: post
title: "github 포스트 작성"
featured-img: what-is-github
categories: [practice, post]
---
```

<a name="commitGithub"/>
## 작성한 문서 github에 올리기

```no-highligt
1) 로컬 git 저장소 폴더로 이동한다.

2)git status
파일의 상태를 확인합니다. 새로 만들어진 파일이 있거나 수정된 파일이 있거나 삭제된 파일이 있을 경우 하단에 붉은색 글자로 그 파일의 상태를 보여줍니다.

3) git add *
새로만들어진 파일을 커밋할 수 있게 바꿔줍니다.

4) git status
다시 상태를 확인해 봤습니다. 새로 만들어진 파일이 있고 그 파일이 커밋될 수 있다는 의미로 초록색으로 표시된걸 확인했습니다.

5) git commit -m "커밋메시지"
커밋 을 하고 커밋 메시지를 입력합니다.

6) git status
현재 수정되거나 삭제되거나 새로 만들어진 파일이 있는지 없는지 확인해 봅니다.

7) git remote -v
현재 리모트 저장소를 확인하기 위해 명령어를 입력해봤습니다. 정확히 제 깃허브 저장소를 가르키고 있네요.

8) git push
이 명령어를 입력하면 이제 깃허브 블로그에 작성했던 글이 보이게 됩니다. 깃허브 저장소에 커밋된 파일들을 밀어넣습니다.
```