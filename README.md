# (Repo Description)


## Project Description.


## How to Study


## Commit Rule
Base Rule : [gitmoji](https://gitmoji.dev/) <br>
Other Rule : 개인적으로 규칙을 정의함.<br>
Coding Style : [Google-StyleGuid-Cpp](https://google.github.io/styleguide/cppguide.html)<br>
Other Style : Google Style Guid를 준수하되, 아직 파악하지 못 한 가이드는 개인 스타일로 코드를 작성함.<br>


### Gitmoji


<details>
<summary>Open/Close</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
🎉(tada): 프로젝트 시작<br>
✨(sparkles) : 새 기능 추가<br>
🚀(rocket) : 성능 개선<br>
🔧(wrench) : 구성 파일 추가 / 업데이트<br>
🔨(hammer) : 개발 스크립트 추가 / 업데이트<br>
🔥(fire) : 코드 / 파일 삭제<br>
💩(poop) : 안 좋은 코드(개선 필요)<br>
💡(bulb) : 주석 작성<br>
🩹(adhesive_bandage) : 간단한 수정(크리티컬 이슈X)<br>
🚚(truck) : 파일 / 경로 / 이름 변경<br>
⚰️(coffin) : 죽은 코드 삭제<br>
🐛(bug) : 버그 수정<br>
♻️(recycle) : 리팩토링<br>
📝(memo) : 문서 추가 / 업데이트<br>
💄(lipstick) : UI 개선<br>
📦(package) : 컴파일된 파일 추가<br>
</details>


### Commit Type

<details>
<summary>Open/Close</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
| Name | Description |
| :--- | :--- |
| Create | Create New file / Project|
| Add | Add New File |
| Feat | Create New Feature |
| Delete | Delete file / feature |
| Update | Improve feature / Make significant changes |
| Fix | Fix bug |
| Docs | Edit a document |
| Refactor |    Refactoryiing the code.
</details>


### Commit Message
변경된 사항에 대한 간략한 메시지를 남깁니다.<br>

### Commit Filep
to (FileName).c : 새로운 함수를 파일에 추가한 경우<br>
in (FileName).c : 특정 함수 내의 로직을 수정한 경우<br>


### Commit Format

(Gitmoji) (Commit Type): (Commit Message) (Commit File)

### Others

gitmoji를 우선으로 작성하고, Commit Title에 할당된 gitmoji는 달라도 됨.<br>
Example Case #1: Update Script -> 🔧 Update system in main.c<br>
