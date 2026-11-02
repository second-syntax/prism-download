# 작업 지침

- 이 저장소는 SECOND SYNTAX org 규칙(비공개 Catalog 저장소의 `docs/ORG_RULES.md`)을 따른다: 바꾸면 그 세션 안에서 선별 커밋, Catalog `inbox/`에 인계 메모, push는 사용자 요청 시만.
- Prism 설치 파일을 내려받는 **공개** 저장소다. 소스는 두지 않고 안내 `README.md`와 Releases만 둔다. Prism 소스 저장소는 계속 비공개다.
- 릴리스 하나에 팩 하나다. 태그는 `simple-v<x.y.z>`·`extended-v<x.y.z>`·`ai-v<x.y.z>`이고, 첨부는 Setup.exe와 `SHA256SUMS.txt`다. 앱의 업데이트 알림은 이 태그의 릴리스만 읽는다.
- 팩이 아닌 릴리스(예: `office-engine-v26.2.6`)는 Latest로 표시하지 않는다(`gh release create … --latest=false`). 함께 담은 외부 구성 요소의 라이선스 고지와 원본 소스 주소를 릴리스 설명에 둔다.
- 올리는 절차와 조건은 Prism 저장소 `docs/SETUP_PACKAGE.md`를 따른다. README·릴리스 변경은 Prism 세션 몫이고, 게시는 사용자 확인 뒤에 한다.
- 공개물이다. 비밀 값·개인 연락처·비공개 체험 빌드를 올리지 않는다. 연락처는 README의 조직 공식 주소만 쓴다.
