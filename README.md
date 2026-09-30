# inMente 릴리스

논문 · 일정 · 실험 · 행정을 한곳에서 관리하는 연구용 앱 inMente 의 배포 저장소입니다.

## 최신 버전 · 0.9.2

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.9.2/inMente-Setup-0.9.2.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.9.2/inMente-0.9.2.apk)

## 릴리스 기록

<!-- INMENTE_RELEASES_START -->
<!-- INMENTE_RELEASE:0.9.2:START -->
### inMente 0.9.2

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.9.2/inMente-Setup-0.9.2.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.9.2/inMente-0.9.2.apk)

- **vault 목록** — 설정 → vault의 '최근 vault'(5개) 대신 이 기기에서 쓴 vault가 모두 보여요. 누르면 그 vault로 바꾸고, [목록에서 빼기]를 누르면 앱이 그 폴더를 vault로 알아보지 않아요(폴더와 파일은 그대로).
- **새 vault로 무엇을 가져올지 골라요** — 새 폴더를 vault로 만들면, 앞에서 쓰던 vault에서 전부 · 골라서(파일탐색기 노트 · 내 일정 · 실험 · 주간 보고 · 행정) · 가져오지 않기(빈 vault) 중에 골라요. 복사만 하고 원래 vault는 그대로예요. 새 vault에 같은 이름이 있으면 덮지 않아요.
- **vault마다 서버 자리** — 동기화할 때 vault마다 서버에 따로 자리를 써서 다른 vault의 글과 섞이지 않아요(전에는 새 vault를 열면 앞 vault의 글이 서버에서 모두 내려왔어요). 지금 쓰던 vault는 원래 자리를 그대로 써요. PC에서 새로 만든 vault는 새 자리를 저절로 받아요.
- 설정 → 동기화 → '이 vault의 서버 자리'에서 자리를 보고 바꿔요. 폰이나 예전 vault는 여기서 '서버의 자리 보기 → 이 자리와 맞추기'로 PC의 그 vault와 맞춰요.
- 할 일 목록은 어느 vault든 같아요(할 일 서버는 계정에 하나).
<!-- INMENTE_RELEASE:0.9.2:END -->

<!-- INMENTE_RELEASE:0.9.1:START -->
### inMente 0.9.1

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.9.1/inMente-Setup-0.9.1.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.9.1/inMente-0.9.1.apk)

- **파일탐색기에는 파일탐색기의 것만** — 다른 페이지가 쓰는 폴더(행정 admin · 일정 inLista · schedule · 실험 experiments · samples · templates · 주간 보고 weeklyupdate)는 파일탐색기 목록에 보이지 않아요. 그 페이지에서 봐요.
- 논문 메모 · 자료 메모 폴더와 직접 만든 노트 · 폴더는 그대로 보여요. 숨긴 폴더의 파일도 그대로 있고, 노트 안의 링크 · 그림은 그대로 열려요.
- **\ 뒤의 기호는 글자 그대로** — \*별표\* → *별표*, \$ → $, \~ → ~ (inLoco 5.6.3과 같게). \alpha처럼 글자 앞의 \와 코드 · 수식 안의 \는 그대로예요.
- **물결 하나 취소선** — ~이렇게~ 써도 취소선이에요(10~20처럼 짝이 없거나 빈칸으로 떨어지면 글자 그대로).
- 문법 도움말에 '기호 그대로'와 물결 하나 취소선을 더했어요.
<!-- INMENTE_RELEASE:0.9.1:END -->

<!-- INMENTE_RELEASE:0.9.0:START -->
### inMente 0.9.0

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.9.0/inMente-Setup-0.9.0.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.9.0/inMente-0.9.0.apk)

- **출장 건** — 행정에 [+ 출장 건]이 생겼어요. 국내 · 국외, 학회 참석, 출장 전에 카드로 먼저 결제할 것(학회 등록 · 항공 · 숙소), 날짜에 답하면 해야 할 단계와 서류가 순서도로 나와요.
- 청구 방식(출장 전 청구 · 다녀와서 한 번에)이 저절로 정해지고, 먼저 결제했으면 '다음 달 15일 지출 처리' 마감이 보여요.
- 학회 등록 · 항공(여정안내서) · 숙소(1박 기준 · USD 결제) · 환율 증빙(신청일 · 출장 첫날) · 학회 뱃지 사진 · 귀국 보고(귀국보고서 · 출입국사실증명원 · 명찰) · 식대 빼기 · 자가용 유류비까지 가이드 순서대로 나와요. 단계마다 가이드의 그 절을 바로 열어 볼 수 있어요.
- **출장 서류 폴더** — 행정 설정에서 결제 서류 폴더와 따로 골라요(예: Purchasing\출장). 출장 건에서 [폴더 만들기]를 누르면 '출장_연.월.일_이름' 폴더와 그 안에 학회 등록 · 교통(국외는 항공) · 숙소 폴더를 같이 만들어요. 넣은 파일로 서류 체크를 제안해요.
- 행정 목록에서 출장 건은 하늘색 칸(국내 출장 · 국외 출장)으로 보여요.
- 행정 묶음을 마쳐서 가운데 번호를 올렸어요(0.8 → 0.9).
<!-- INMENTE_RELEASE:0.9.0:END -->

<!-- INMENTE_RELEASE:0.8.8:START -->
### inMente 0.8.8

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.8/inMente-Setup-0.8.8.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.8/inMente-0.8.8.apk)

- **새 페이지 [주간 보고]** — 왼쪽 메뉴에 생겼어요. 노션처럼 연도 → 달 → 주를 눌러 접었다 펴고, 주를 펴면 그 자리에 내용이 보여요. [고치기]로 바로 고쳐요.
- **노션 파일을 주마다 나누기** — 주간 보고 폴더(weeklyupdate)에 노션에서 내보낸 파일이 있으면 [주마다 나누기]가 떠요. 한 번 묻고, 원래 파일은 그대로 둔 채 주마다 파일 하나(weeklyupdate/연도/연.월/)로 복사해요. 그림도 그대로 보여요.
- **[이번 주 보고]** — 이번 주 금요일 이름(예: 261002 (260925~261001))으로 새 보고를 만들어 열어요. 지난 보고의 큰 항목을 틀로 쓰고, 지난주 '다음주 목표'는 이번 주 '이번주 목표'로 옮겨 와요. 이미 있으면 그것을 열어요.
- **[+ 메모]** — 회의 메모 · 발표 피드백을 날짜와 이름으로 그 달에 만들어요.
- **매주 '주간 보고 쓰기' 할 일** — 주간 보고 설정(⚙)에서 켜면 매주 고른 요일(기본 목요일)에 할 일 목록에 하나 넣어요. 이름과 분류도 고를 수 있어요. 이번 주만 빼려면 주간 보고 페이지 위의 [이번 주 건너뛰기]를 눌러요. PC와 폰이 한 주에 한 번만 넣어요.
- 주간 보고 설정에 휴지통도 있어요(지운 주간 보고 · 회의 메모).
<!-- INMENTE_RELEASE:0.8.8:END -->

<!-- INMENTE_RELEASE:0.8.7:START -->
### inMente 0.8.7

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.7/inMente-Setup-0.8.7.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.7/inMente-0.8.7.apk)

- **노트에 문법 도움말** — 파일탐색기에서 노트를 열면 위쪽에 ? 버튼이 있어요. 누르면 옆에 [단축키 · 문법] 창이 열려요(inLoco처럼).
- 제목 · 강조 · 색 · 목록 · 체크박스 · 접었다 펴는 제목 · 표와 칸 너비 · 수식 · 코드 · 링크 · PDF 쪽 링크 · 그림 크기 · 알림 칸 · 숨김 메모 · 단축키를 찾아볼 수 있어요. 예: 'toggle', '표 너비'.
- 항목마다 예제 글과 **읽기 화면에 보이는 모양**을 함께 보여 줘요. 복사 버튼으로 예제를 복사해 노트에 붙여 넣으면 돼요.
<!-- INMENTE_RELEASE:0.8.7:END -->

<!-- INMENTE_RELEASE:0.8.6:START -->
### inMente 0.8.6

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.6/inMente-Setup-0.8.6.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.6/inMente-0.8.6.apk)

- **새 앱 아이콘** — 비커 안에 이름을 넣은 새 로고로 바꿔서 아이콘이 꽉 차 보여요(전에는 그림 아래 이름까지 넣어 작아 보였어요). 설정 → 앱 정보의 로고도 새로 다듬은 모양이에요.
- **행정 · 실험에도 ⚙ 설정 버튼** — 행정은 '행정' 제목 옆, 실험은 [기록 · 샘플] 전환 오른쪽에 있어요. 누르면 그 페이지의 설정(행정: 결제 서류 폴더 · 휴지통 / 실험: 휴지통)으로 가요.
- **결제 서류 폴더를 그림으로** — 행정 설정과 서류 폴더 칸에 ① 결제 서류 폴더(모든 건 폴더가 들어 있는 위 폴더, 예: 결제) → ② 그 바로 아래 폴더(예: 0. 견적 요청 · 0. 카드결제) → ③ 건 폴더가 그려져요. 고른 폴더가 있으면 그 이름으로 그려요.
- 건 폴더 하나를 결제 서류 폴더로 잘못 고르면 알려요 — 고른 폴더 안에 폴더가 없을 때, 그리고 결제 서류 폴더 자체를 건 폴더로 연결하려 할 때.
- **분류 폴더 안의 건 폴더도 연결** — 결제 서류 폴더 안이면 몇 단계 아래든(5단계까지) 이어요(예: 결제\0. 견적 요청\MTI Korea_2026.07.27_Blade saw).
- **[폴더 만들기]에서 만들 자리를 골라요** — 결제 서류 폴더 바로 아래의 폴더가 '어디에 만들까요'에 나와요. 과제 이름이 든 폴더, 아니면 결제 방식(카드 → 카드결제 · 계좌이체 → 견적 요청)으로 먼저 골라 두고, 바꿀 수 있어요.
- 새 폴더 이름의 날짜를 실제로 쓰는 모양(2026.07.27)으로 지어요.
- 연결한 폴더를 다른 분류 폴더로 옮겨도, 결제 서류 폴더 안에서 같은 이름을 찾아 다시 이어요(같은 이름이 둘 이상이면 고르지 않고 알려요).
- **큰 가이드 그림도** — 그림 하나의 상한을 10MB에서 20MB로 올렸어요. 출장 가이드의 학회 뱃지 사진(17MB)이 빠졌던 까닭이에요. 같은 가이드를 다시 가져오면 빠진 그림만 채워져요.
<!-- INMENTE_RELEASE:0.8.6:END -->

<!-- INMENTE_RELEASE:0.8.4:START -->
### inMente 0.8.4

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.4/inMente-Setup-0.8.4.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.4/inMente-0.8.4.apk)

- **구매 방식이 저절로** — 재원 · 단가 · 총액을 넣으면 산단 중앙구매 기준표(가이드 3.2의 표 · 부가세 별도)대로 재량구매 · 견적구매 · 공개입찰 · 수의계약이 정해져요(민간 · 교내 과제 예외 포함). 총액이 2천만 원을 넘으면 수의계약 사유가 있는지만 물어요. 질문 칸 아래에 '구매 방식'이 보여요.
- **새 기본 규칙으로 바꾸기** — 행정 화면에 '새 기본 규칙이 있어요'가 뜨면 [새 기본 규칙으로 바꾸기]를 눌러요. 지금 규칙은 보관본으로 남고, 진행 중인 건은 그 판으로 계속 보이다가 건마다 바꿀지 물어요.
- **결제 서류 폴더** — 행정 설정(⚙)에서 드롭박스에 올리기 전의 로컬 폴더를 한 번 골라요. 구매 건 화면에서 [폴더 만들기]를 누르면 가이드 방식 이름(업체이름_연.월.일_구매품요약 · 장비는 _장비 안)으로 폴더가 생기고, 들어간 파일 목록과 [폴더 열기]가 보여요. 파일 이름을 보고 '폴더에 있는 것 같아요: 견적서.pdf [체크]'로 서류 체크를 제안해요(체크는 직접). 파일은 읽기만 해요.
- **가이드 그림도 같이** — [가이드 가져오기]가 원문이 가리키는 그림(attachments 등)도 같이 가져와요. 전에 그림 없이 가져온 가이드는 같은 파일을 다시 가져오면 그림만 채워져요. (그림은 아직 폰으로 동기화되지 않아 PC에서만 보여요.)
- 순서도의 묶음 제목(규정 확인 · 사전 작업 · 구매 · 수령 · 정산)을 번호와 띠로 크게 보여요.
<!-- INMENTE_RELEASE:0.8.4:END -->

<!-- INMENTE_RELEASE:0.8.3:START -->
### inMente 0.8.3

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.3/inMente-Setup-0.8.3.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.3/inMente-0.8.3.apk)

- **행정 → 구매 건** — [+ 구매 건]을 만들고 과제 · 재원 유형 · 비목 · 금액 · 결제 방식 · 해외 구매에 답하면, 거쳐야 할 단계가 세로 순서도로 나와요(규정 확인 → 사전 작업 → 구매 → 수령 · 정산). 지금 할 단계가 강조되고, 단계마다 판단(예: 재량구매 가능) · 챙길 서류(체크) · 마감(예: 카드 결제 → 다음 달 15일 지출결의) · 가이드의 해당 절이 있어요.
- 모든 건 화면 위에 '처음 해 보는 절차는 가이드를 먼저 읽고, 실행 전에 꼭 경험자와 확인'을 둬요. 앱은 행정 판단을 대신하지 않아요.
- **규칙은 파일로** — 구매 가이드를 옮긴 규칙이 vault의 admin/rules/purchasing.yaml에 생겨요. 규정이 바뀌면 이 파일만 고치면 돼요. 진행 중인 건은 시작할 때의 규칙 판으로 계속 보이고, 새 판이 있으면 달라지는 것을 보여 준 뒤 바꿀지 물어요.
- **[가이드 가져오기](PC)** — 가이드 원문 md를 골라 vault의 admin/guides로 가져와요(같은 이름은 덮지 않아요). 원문은 앱에 넣지 않았어요. 단계의 [가이드 …]를 누르면 그 절만 보여요.
- **휴지통은 페이지별 설정에** — 파일탐색기 · 일정 · 실험 · 행정의 설정(⚙)에 그 페이지에서 지운 것만 보여요. 전체 설정의 휴지통은 뺐어요.
<!-- INMENTE_RELEASE:0.8.3:END -->

<!-- INMENTE_RELEASE:0.8.2:START -->
### inMente 0.8.2

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.2/inMente-Setup-0.8.2.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.2/inMente-0.8.2.apk)

- **휴지통 화면** — 설정 → 휴지통에서 지운 노트 · 실험 기록 · 샘플 배치를 지운 시각마다 모아 보여요. [되살리기]를 누르면 원래 자리로 돌아가요. 그 자리에 같은 이름이 있으면 덮지 않고 이름 뒤에 '-되살림'을 붙여요. 한 번에 지운 것은 [모두 되살리기]로.
- 앱은 휴지통을 비우지 않아요(파일을 잃지 않게). 비우려면 Windows 탐색기에서 vault 안의 .trash 폴더를 지워요.
- 지울 때 뜨는 안내도 '설정 → 휴지통에서 되살릴 수 있어요'로 바꿨어요.
<!-- INMENTE_RELEASE:0.8.2:END -->

<!-- INMENTE_RELEASE:0.8.1:START -->
### inMente 0.8.1

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.1/inMente-Setup-0.8.1.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.1/inMente-0.8.1.apk)

- **사용 완료가 저절로** — 실험 기록의 '쓴 샘플'에 적힌 전극은 샘플 표의 상태가 '사용 완료'로 보여요. 기록에서 빼면 다시 '보관'이에요. 상태를 누르면 폐기 ↔ 되돌리기만 해요. 배치 목록에도 사용 완료 수가 보여요.
- 전극 표 아래에 안내를 넣었어요 — '사용' 칸은 실험 기록 화면의 '쓴 샘플'에서 그 전극을 고르면 저절로 채워지고, 거기서 빼면 사라져요.
- **실험 기록 · 배치 지우기** — 정보 줄 끝의 휴지통 단추로 지워요. 한 번 더 묻고, 지우면 달라지는 것(그 배치를 쓴 기록 수 · 풀리는 사용 완료)을 알려 줘요. 파일은 없애지 않고 휴지통(.trash)으로 옮겨서 되살릴 수 있어요.
<!-- INMENTE_RELEASE:0.8.1:END -->

<!-- INMENTE_RELEASE:0.8.0:START -->
### inMente 0.8.0

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.8.0/inMente-Setup-0.8.0.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.8.0/inMente-0.8.0.apk)

- **샘플 관리** — 실험 페이지 위의 [기록 · 샘플]에서 샘플로 가요. 슬러리 한 번이 배치 하나, 거기서 찍은 전극들이 그 안의 한 장들이에요. 배치마다 활물질 · 활:도:바 비율 · 집전체 · 비용량을 적고, 전극마다 넓이 · 두께 · 질량 · 측정 용량을 표에 적어요.
- **로딩 · 이론 용량을 계산해서** 표에 보여 줘요(파일에는 적은 값만 남아요). 전극은 [보관 · 폐기]로 표시하고, [전극 더하기]로 늘려요.
- **[필드 추가]** — 필요한 칸(예: 기공률)을 언제든 더해요. 전극마다 칸인지 배치에 하나인지, 수인지 글인지 골라요. 정의에 없는 값도 지우지 않고 '기타'로 보여요.
- **실험 기록 ↔ 샘플** — 기록 화면의 '쓴 샘플'에서 전극을 골라요. 고른 전극의 값과 계산값이 기록 화면에 함께 보이고, 샘플 쪽 표에는 그 전극을 쓴 기록이 '사용'으로 나와요. 누르면 서로 오가요.
- 실험 기록의 상태 · 종류 · 날짜를 바꾸면 **바로** 바뀌어요(전에는 0.5초쯤 늦었어요). 상태마다 색이 생겼어요(계획 회색 · 진행 중 파랑 · 완료 초록 · 실패 주황).
- **프로젝트 색** — 실험 머리의 [프로젝트]에서, 또는 새 프로젝트를 만들 때 색을 골라요. 목록과 고르기 메뉴에 색 점으로 보여요.
<!-- INMENTE_RELEASE:0.8.0:END -->

<!-- INMENTE_RELEASE:0.7.5:START -->
### inMente 0.7.5

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.7.5/inMente-Setup-0.7.5.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.7.5/inMente-0.7.5.apk)

- **실험 틀 만들기** — 기록 화면의 [틀로 저장]을 누르면 지금 기록의 변수 표 · 목적 · 실험 환경 · 주의사항이 채워진 틀로 남아요. 결과 · 해석 · 변동사항은 비워서 저장해요. 같은 이름이 있으면 [덮어쓰기]를 한 번 더 눌러요.
- **새 기록의 시작 내용** — [+ 기록]에서 기본 틀 · 저장한 틀 · 지난 기록 복사 중에 골라요. 지난 기록을 복사하면 표와 목적은 그대로, 결과 · 해석 · 변동사항은 빈 칸으로 가져오고, 프로젝트와 제목이 따라오고, 복사한 기록을 이전 기록으로 이어 둬요.
- 고르기 메뉴가 화면 왼쪽 밖으로 잘리던 것을 고쳤어요(실험 기록의 '이전 기록' 등). 항목이 많으면 메뉴 안에서 스크롤하고, 긴 이름은 말줄임으로 보여요.
- 구글 캘린더: 로그인할 때 늘 계정 고르기부터 떠요. 구글이 거절하면(403 등) 까닭과 할 일을 알려 줘요(예: Google Calendar API를 켜세요).
<!-- INMENTE_RELEASE:0.7.5:END -->

<!-- INMENTE_RELEASE:0.7.4:START -->
### inMente 0.7.4

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.7.4/inMente-Setup-0.7.4.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.7.4/inMente-0.7.4.apk)

- **실험 기록을 입력 칸으로** — 기록을 열면 마크다운 편집기 대신 소제목(목적 · 변인 통제 · 실험 환경 · 주의사항 · 결과 · 해석 …)마다 글 칸이 나와요. 적다가 1초쯤 멈추면 저절로 저장돼요. 파일은 전처럼 마크다운이고, 고친 소제목의 내용만 바뀌어요.
- **변수 설정 표** — 변수 · 값 · 단위를 칸에 바로 적고, [줄 더하기]와 ✕로 줄을 더하고 지워요. 표 아래에 메모도 적을 수 있어요. 이전 기록과 견주기가 이 표를 그대로 읽어요.
- 틀(templates 폴더)에 있는데 기록에 없는 소제목도 빈 칸으로 보여요. 마크다운을 직접 보고 싶으면 기록 화면의 [원문]으로 바꿔요(고른 쪽을 기억해요).
<!-- INMENTE_RELEASE:0.7.4:END -->

<!-- INMENTE_RELEASE:0.7.3:START -->
### inMente 0.7.3

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.7.3/inMente-Setup-0.7.3.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.7.3/inMente-0.7.3.apk)

- **구글 캘린더(읽기 전용 · PC)** — 일정 화면 위에 [구글 캘린더]가 생겼어요. 설정 → 구글 캘린더에서 한 번 로그인하면 내 캘린더와 공유받은 캘린더(장비 예약 등)가 모두 달력에 막대로 보여요. 보기만 하고, 고치기는 구글 캘린더 웹에서 해요. 필요 없는 캘린더는 설정에서 꺼요. 처음 한 번 Google Cloud에서 앱 등록이 필요해요(안내서: 저장소 docs/google_calendar_setup.md).
- **앱 아이콘이 이제 제대로 바뀌어요** — 0.7.1 · 0.7.2는 빌드가 아이콘이 바뀐 것을 알아채지 못해 실행 파일에 옛 아이콘이 들어갔어요. 이제 뇌가 가운데이고 InMente 글씨가 있는 아이콘이에요(작업 표시줄에 옛 아이콘이 남아 있으면 다시 시작하면 바뀌어요).
- **파일탐색기 옆 칸** — 제목 · 새 노트 · 찾기는 위에 고정되고, 노트 나무와 라이브러리만 스크롤돼요. 제목의 아이콘도 inLoco 로고로 바뀌었어요.
- **메모 찾기 결과** — 좁은 옆 칸에서 아이콘 단추가 제목과 겹치던 것을 고쳤어요. 제목은 줄을 바꿔 다 보이고, 아이콘은 카드 오른쪽 아래에 있어요.
- **메모를 열면 PDF도 나란히(설정)** — 파일탐색기 설정 → 노트 열기에서 켜면 논문 메모를 열 때 그 PDF가 옆에 저절로 열려요(기본은 꺼짐).
<!-- INMENTE_RELEASE:0.7.3:END -->

<!-- INMENTE_RELEASE:0.7.2:START -->
### inMente 0.7.2

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.7.2/inMente-Setup-0.7.2.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.7.2/inMente-0.7.2.apk)

- **실험 기록** — 왼쪽 메뉴의 실험에서 이론 · 실험 · 시뮬레이션 기록을 써요. 목록은 최근 날짜 먼저이고, 종류 · 프로젝트 · 상태로 거르고 제목으로 찾아요.
- **[+ 기록]** — 제목 · 종류 · 프로젝트 · 날짜를 고르면 그 종류의 틀(목적 · 변수 설정 표 · 변인 통제 · 실험 환경 · 주의사항 · 이전 실험과의 변동사항 · 결과 · 해석)로 기록이 만들어지고 바로 열려요. 프로젝트는 그 자리에서 새로 만들 수 있어요(projects.yaml에 더해져요).
- **기록 화면** — 위에서 종류 · 프로젝트 · 날짜 · 상태(계획 · 진행 중 · 완료 · 실패)를 바꾸고, 아래는 파일탐색기와 같은 편집기(편집 · 나란히 · 읽기 · 저절로 저장)예요.
- **이전 기록과 견주기** — 같은 프로젝트 · 종류의 바로 앞 기록(또는 직접 고른 기록)과 '변수 설정' 표를 맞대어 바뀐 값 · 새 변수 · 빠진 변수를 보여 줘요. 틀은 vault의 templates 폴더에 있고, 고치면 다음 기록부터 그 틀로 만들어져요.
- **달력이 갤럭시 캘린더처럼** — 할 일 · 내 일정 달력의 칸마다 막대로 보여요. 여러 날 일정은 이어진 날에 한 줄로 쭉 이어지고(주가 바뀌면 다음 줄에서 이어져요), 하루 종일 일정은 색을 채운 막대, 시각 있는 일정 · 할 일은 왼쪽 색 줄 막대예요. 칸이 모자라면 +N으로 알려요. 폰에서도 제목이 보여요.
- **폰에서 할 일 · 일정 · 기록 만들기 창이 위쪽 팝업으로** — 아래에서 올라오던 창은 입력칸이 화면 아래에 붙어 치기 힘들었어요. 이제 화면 위쪽에 글 높이만큼 뜨고, 키보드가 올라와도 가려지지 않아요.
- **논문 메모 찾기를 부드러운 모양으로** — 둥근 찾기 칸(지우기 단추) · 색이 드는 칩 · 카드를 누르면 열리고, 메모 위치 · PDF 위치 · 탐색기는 아이콘 단추로.
- **앱 아이콘에 InMente 글씨** — 비커 그림 아래에 이름이 함께 보여요.
<!-- INMENTE_RELEASE:0.7.2:END -->

<!-- INMENTE_RELEASE:0.7.1:START -->
### inMente 0.7.1

- [Windows Setup](https://github.com/tystarme/inMente_release/releases/download/v0.7.1/inMente-Setup-0.7.1.exe)
- [Android APK](https://github.com/tystarme/inMente_release/releases/download/v0.7.1/inMente-0.7.1.apk)

- **inMente를 처음 여기에 올려요.** 0.7.0까지 들어간 기능은 저장소 README의 '0.1.0 ~ 0.7.0 — 지금까지 들어간 기능'에 모아 두었어요.
- **내 일정** — 일정 화면 위의 [할 일 · 내 일정]으로 바꿔요. 한 달 달력에 일정이 보이고, 날을 누르면 오른쪽(폰은 아래)에 그 날 일정이 떠요. [+ 일정]이나 일정을 누르면 옆 창에서 제목 · 카테고리 · 시작 날 · 끝나는 날(여러 날 일정) · 시각 · 장소 · 설명 · 알림을 적어요. 여러 날 일정은 이어지는 날에 ↳로 보여요.
- **일정 알림** — 시각을 정한 일정도 할 일과 같은 알림 설정(켜기 · 미리 알림)으로 알려요. 일정마다 켜고 끌 수 있어요.
- 일정은 vault의 schedule 폴더에 글로 저장되고 동기화로 폰과 맞춰져요. 지운 일정은 [실행취소]로 되살리고, 같은 폴더의 '지운 일정'에도 남아요.
- 왼쪽 메뉴의 파일탐색기는 inLoco 로고, 일정은 inLista 로고로 바뀌었어요. 앱 아이콘의 뇌가 정가운데에 오도록 다시 맞췄어요.
<!-- INMENTE_RELEASE:0.7.1:END -->
<!-- INMENTE_RELEASES_END -->

## 0.1.0 ~ 0.7.0 — 지금까지 들어간 기능

이 저장소에 올리기 전(0.1.0 ~ 0.7.0)의 기능을 한데 모았어요. 0.7.1부터는 위의 릴리스 기록에 버전마다 쌓여요.

### 논문 파일탐색기

- **라이브러리** — PC의 PDF 폴더를 별명으로 붙여 두고(기기마다 경로가 달라도 같은 별명), 파일 나무와 폴더 타일로 봐요. 메모가 있는 PDF · 사본 · 논문 아닌 파일을 표시해요.
- **정리** — 노트 · 폴더를 끌어 옮기기(폴더째 · 되돌리기), 새 폴더, 이름 바꾸기, 휴지통으로 지우기, 마우스 앞/뒤 단추로 오가기, 우클릭 메뉴.
- **서지 가져오기** — 누를 때만 Crossref · OpenAlex에서 저자 · 소속 · 연도 · 저널 · 키워드 · DOI를 가져와 논문 메모에 적어요. DOI가 없으면 제목으로 찾아 고르거나, AI가 첫 쪽에서 읽어요. 폴더째 한 번에, 미분류 목록, [논문 아님] 표시.
- **PDF 보기 │ 메모** — 앱 안에서 PDF와 메모를 나란히 보고, 고른 글을 쪽 링크와 함께 메모에 인용해요. 인용하면 PDF에 형광펜이 칠해지고, 형광펜은 우클릭으로 지워요(원본 보관은 설정에서).
- **AI 메모 채우기** — Claude Code로 논문의 섹션을 가려 섹션마다 핵심 2–3문장을 메모에 채워요. 수치는 원문과 대조하고, 편집 중인 글에 이어 들어가요.
- **찾기** — 제목 · 저자 · 연구그룹 · 연도(범위) · 저널 · 키워드 · DOI · 메모 본문 · 파일 이름으로 골라 찾고, 결과에서 [열기] [위치로 이동] [탐색기에서].
- **자료 메모** — 서지가 없는 강의자료 같은 PDF에도 메모를 달아요. 메모는 어느 폴더에 두어도 알아보고, 폴더마다 메모 자리를 정할 수 있어요.

### 노트

- inLoco와 같은 마크다운 문법으로 읽고 써요(편집 · 나란히 · 읽기). 한글 입력, 목록 잇기, 저절로 저장.

### 일정 · 할 일 (inLista에서 옮김)

- **할 일** — 날 → 카테고리로 묶인 목록, 체크하면 아래로 미끄러져 내려가요. 제자리 더하기, 끌어 옮기기, 옆 창에서 고치기(날짜 · 카테고리 · 개요 · 장소 · 시각 · 알림).
- **보기** — 오늘 · 이번 주 · 저번 주~이번 주 · 이번 달 · 최근 며칠, 줄/열 배치, 한 달 달력, 주 띠, 찾기, 이번 주 할 일 모아 보기.
- **메모** — 할 일마다 메모(체크리스트 · 그림 붙여 넣기). 폰 inLista와 같은 파일이에요.
- **알림** — 시각을 정한 할 일을 PC · 폰에서 알려요(미리 알림, 할 일마다 켜고 끄기).
- **정리** — 카테고리 관리(차례 · 이름 · 색 · 숨기기), 휴지통(되살리기 · 보관 기간), 내보내기, 부딪힌 사본 합치기.

### 동기화 · 폰

- inMente 서버로 노트를 PC와 폰에 맞추고, 할 일 · 메모 그림은 inLista 서버와 주고받아요. 저장하면 곧, 화면에 떠 있는 동안 1분마다 맞춰요.
- 폰에서는 고른 폰 폴더에 vault를 두고(앱을 지워도 남아요), 뒤로 가기 · 제스처로 앞 화면에 가요.

### 설정

- 섹션마다 설정 페이지(파일탐색기 · 일정 · 실험 · 행정), 움직임(켬 · 줄임 · Windows 따름), AI 연결(Claude Code CLI), 동기화 로그인.
