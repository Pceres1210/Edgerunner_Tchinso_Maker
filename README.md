# Edgerunner_Tchinso_Maker
사이버펑크 엣지러너 2의 동인 활동을 위한 자기소개표 생성기
# 사이버펑크 엣지러너 2 트친소표 메이커
> CD PROJEKT와 무관한 팬메이드 비공식 툴입니다.


## 기능

- 닉네임, 아이디, 한 줄 소개, 프로필 사진 입력
- 작성목적 선택: 자기소개 / 트친소 (표 오른쪽 위에 표시)
- 항목마다 **태그만 / 글만 / 태그+글** 중에서 형식 선택
- 태그 추가·삭제, 눌러서 켜고 끄기
- 항목 추가·삭제, ⠿ 핸들을 끌어서 순서 변경 (키보드 위아래 화살표도 가능)
- 마무리 문구 입력 (줄바꿈 가능, 비워 두면 아래 여백이 자동으로 조절됨)
- **이미지로 저장**: 1200px 폭 PNG로 다운로드
- 작성 중인 내용은 브라우저에 남아서 다시 열어도 이어서 쓸 수 있음


## 이용 조건

이 리포지토리의 코드는 아래 조건으로 공개합니다. 상업적 이용을 제한하므로 OSI 정의상의 '오픈소스'가 아니라 **비영리 목적의 소스 공개**입니다.

1. **이용·수정·재배포 가능**: 누구나 이 코드를 사용하고, 고치고, 원본 그대로 또는 고친 형태로 다시 배포할 수 있습니다.
2. **출처 표기 불필요**: 재가공하거나 재배포할 때 원작자나 이 저장소를 표기하지 않아도 됩니다.
3. **비영리 목적만 허용**: 영리 목적으로는 이용할 수 없습니다. 예를 들어 다음과 같은 이용은 허용하지 않습니다.
   - 이 코드나 이를 수정한 결과물을 판매하는 것
   - 유료 서비스, 유료 회원 전용 기능, 커미션 등 대가를 받는 일에 사용하는 것
   - 광고 수익을 얻는 사이트·앱에 넣는 것
4. **보증 없음**: 이 코드는 있는 그대로 제공되며, 사용으로 생긴 문제에 대해 작성자는 책임지지 않습니다.
5. **제외 항목**: 아래 [라이선스에서 제외되는 항목](#라이선스에서-제외되는-항목)은 이 조건이 적용되지 않습니다.


## 라이선스에서 제외되는 항목

아래 항목은 저장소 작성자가 권리를 가진 것이 아니므로, **위 이용 조건에 포함되지 않습니다.** 재배포할 때는 직접 확인하거나 다른 이미지로 바꿔서 쓰세요.

| 항목 | 코드 안 위치 | 권리자 | 제외 사유 |
|---|---|---|---|
| 카드 배경 이미지 3장 (상단·중간·하단, 'Cyberpunk Edgerunners' 로고 포함) | `index.html`의 `CARD_FRAME` | CD PROJEKT | 로고와 디자인이 CD PROJEKT의 상표·저작물입니다. 비영리 팬 콘텐츠로만 사용하며, 이용 범위는 CD PROJEKT의 팬 콘텐츠 가이드라인을 따릅니다. |
| 기본 프로필 예시 이미지 | `index.html`의 `DEFAULT_AVATAR` | [いらすとや (irasutoya)](https://www.irasutoya.com/) | いらすとや에서 받은 일러스트로, 저작권은 いらすとや에 있습니다. 이용과 재배포는 いらすとや의 이용 규정을 따릅니다. |
| 'Cyberpunk', 'Cyberpunk Edgerunners' 등의 명칭 | 페이지 제목과 문구 | CD PROJEKT | CD PROJEKT의 상표입니다. |

이미지는 모두 `index.html` 안에 base64 데이터로 들어 있습니다. 재배포할 때 이미지를 바꾸려면 위 표의 상수 값을 다른 이미지 데이터로 교체하면 됩니다.

## 사용한 외부 리소스

아래 리소스는 저장소에 포함되어 있지 않고, 페이지가 열릴 때 CDN에서 불러옵니다. 해당 리소스는 제작자가 직접 제작하였습니다.

| 리소스 | 용도 | 라이선스 |
|---|---|---|
| [html2canvas](https://html2canvas.hertzen.com/) 1.4.1 | 표를 PNG 이미지로 변환 | MIT |
| [Orbitron](https://fonts.google.com/specimen/Orbitron), [Chakra Petch](https://fonts.google.com/specimen/Chakra+Petch), [Black Han Sans](https://fonts.google.com/specimen/Black+Han+Sans), [Noto Sans KR](https://fonts.google.com/noto/specimen/Noto+Sans+KR), [IBM Plex Sans KR](https://fonts.google.com/specimen/IBM+Plex+Sans+KR) (Google Fonts) | 글꼴 | SIL Open Font License 1.1 |

## 면책

이 프로젝트는 CD PROJEKT와 무관한 팬메이드 비공식 도구입니다. Cyberpunk, Cyberpunk Edgerunners 및 관련 로고는 CD PROJEKT S.A.의 상표이며, 모든 권리는 각 권리자에게 있습니다.
