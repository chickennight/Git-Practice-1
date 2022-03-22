<details>
<summary>첫 기여 테스트 다시보기</summary>
<div markdown="1">

# 첫 기여

어렵습니다. 무엇을 하든 누구나 처음에는 어렵게 느껴집니다. 특히 협업을 할 때 실수를 하기라도 하면 마음이 편치 않습니다. 그래서 저희는 새로운 오픈소스 기여자들이 첫 기여를 하고 그것을 익히는 과정을 단순화하고자 했습니다.

관련된 글을 읽거나 튜토리얼을 보는 것도 물론 도움이 되지만, 연습공간에서 직접 해보는 것보다 나은게 있을까요? 이 프로젝트의 목표는 초보자도 첫 오픈소스 기여를 할 수 있도록 단순한 방식으로 안내하는 것입니다. 첫 기여를 하고 싶으시다면 아래의 설명을 따라주세요.

가장 먼저, Git이 없으시다면 [설치](https://help.github.com/articles/set-up-git/)해주세요.


## 저장소 클론하기

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="이 저장소 복제하기" />

이제 이 저장소를 자신의 기기에 클론합니다. Clone or download 버튼을 클릭하고 클립보드로 복사 아이콘을 클릭합니다.

터미널을 열고 다음 Git 명령을 실행합니다:

```
git clone "방금 복사한 URL"
```

위에 (따옴표를 제외한) "방금 복사한 URL"는 이 저장소의 URL입니다. URL은 이전 단계에서 찾을 수 있습니다.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="URL 을 클립보드로 복사" />

예시:

```
git clone https://github.com/Network-Leader/gitTEST.git
```

예시의 `this-is-you`는 본인 깃헙 계정으로 바꾸어주세요. 이 명령어는
깃헙의 gitTEST 저장소의 내용을 로컬 컴퓨터에 복사합니다.

## 브랜치 생성하기

(아직 저장소 디렉토리가 아니라면) 아래의 명령어를 입력하여 좀전에 컴퓨터에 복사한 저장소 디렉토리로 이동합니다.

```
cd gitTEST
```

그리고 `git checkout` 명령어을 입력하여 브랜치를 생성합니다.

```
git checkout -b <add-your-name>
```

예시:

```
git checkout -b add-alonzo-church
```

(브랜치의 이름에 꼭 *add*가 들어가지 않아도 됩니다. 하지만 이 브랜치의 목적은 당신의 이름을 리스트에 추가하는 것이기 때문에 이름에 *add*를 포함하는 것이 합리적입니다.)

## 필요한 변경사항을 작성하고 커밋하기

이제 텍스트 편집기에서 `Contributors.md` 파일을 열고 본인의 이름을 추가해주세요. 이름을 추가할때는 줄바꿈으로 구분해주세요. 이때 마크다운 분법에 따라 이전 이름에 '   '(띄어쓰기 3번)을 해야 정상적인 줄바꿈이 됩니다. 그리고 파일을 저장하세요.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

프로젝트 디렉터리에서 `git status` 명령을 실행하면 변경사항을 볼 수 있습니다.

변경사항을 아래 `git add` 명령어를 입력하여 추가합니다.

```
git add Contributors.md
```

이제 아래 `git commit` 명령어로 변경사항을 커밋합니다.

```
git commit -m "Add <Your-name> to Contributors list"
```

`<Your-name>`을 본인 이름으로 바꾸세요.

## 변경사항을 깃헙에 푸시하기

`git push` 명령어로 변경사항을 푸시합니다.

```
git push origin <add-your-name>
```

위의 `<add-your-name>` 부분을 좀전에 생성한 브랜치 이름으로 바꾸세요.

## 검토를 위해 변경사항을 제출하기

이제 본인의 깃헙 저장소로 이동하면 `Compare & pull request` 버튼이 보일 것 입니다. 버튼을 클릭하세요.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="풀 요청
생성하기" />

이제 풀 요청(Pull Request)을 제출합니다.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="풀 요청 제출하기"
/>

이제 여러분의 변경사항을 담당자가 확인한 후에 마스터 브랜치에 머지 하게 되면 알림 메일을 받으실겁니다.

## 첫 기여, 그리고 그 후

축하합니다! 앞으로 기여자로써 자주 사용하게될 기본 워크플로우, _포크(fork) -> 클론(clone) -> 수정(edit) -> 풀 요청(pull request)_, 를 완수하셨습니다!!!

</div>
</details>

# 👨‍🌾 모코코 총공격!! -01

성공적으로 Contributors에 이름을 남긴 여러분들을 시기한 나쁜 모코코들이 Contributors.md 파일에 장난을 쳐버리고 말았습니다. Contributors 파일에 적힌 여러분들 이름을 바꾸는 장난들을요! 여러분들은 파일에 적힌 이름들을 바로잡아야 합니다.
![모코코콘1](https://user-images.githubusercontent.com/31841502/159016081-12f707ae-50a7-450a-b648-eb5e1a401974.png)  


## 여러분이 해야 할 일들
1. git pull을 통해 원격 레포지토리의 변경된 코드를 다운로드 합니다.
2. 하지만 변경된 코드와 여러분들의 로컬에 저장된 코드는 같은 파일의 한 줄에 다른 코드가 저장되어 있어 충돌이 나 있습니다.
3. 충돌을 해결하고 Contributors.md에 저장된 파일의 여러분들의 이름을 원래대로 돌려주세요.
4. 그 후 add,commit,push 하면 끝!