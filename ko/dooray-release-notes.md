## Dooray! > 릴리스 노트

### 2018.03.08 

#### Project  
* 스크롤 이슈로 인해 본문 일부 가려지는 문제 해결
#### Mail 
* 메일 발송 전 미리보기
* 수신된 메일의 링크 자동 생성
* 첨부 파일 검색 추가
* 스팸신고 시, 자동으로 수신차단
* 예약 메일 편집
* 대용량 첨부 다운로드 횟수 50회로 확대 (설정으로 조정)
* 자동 분류를 통해 메일 업무 등록 시, 첨부파일 누락되는 현상 수정
* 개별 파일 용량을 초과하는 파일 첨부 시, 해당 파일만 제외하고 첨부 진행하도록 수정
#### Calendar 
* 구독 캘린더 1차: 국가별 휴일 추가
* 월간/2주뷰/3주뷰 UI 개선
* LNB 전체 선택 시 내 캘린더, 프로젝트 캘린더 선택 반영 속도 개선
* 일정 메일에서 일정 자세히 보기 선택 시 오류 수정
* 오랫동안 리프레시 하지 않은 경우, 오늘 날짜 오류 수정
* 프로젝트 캘린더 업무 공지 등록 시 오류 수정
#### Drive 
* 업로드 시, 건너뛰기, 취소 사용성 개선
* 드래그&드랍 시 업로드 버튼 클릭 없이 바로 업로드
* 드라이브 파일 목록 노출 개수 최대 20개에서 50개로 수정

### 2018.03.05 

#### Messenger
* 슬래시 커맨드를 위한 API 제공(일부 사용자에게만 제공, 4월 중 전체 사용자에게 제공)
* 앱 대화방 로딩 속도 개선
* 이모지 개선 
* 멘션 선택 시 프로필 열기 
* 프로필 화면에 부재 정보표시 
* 조직 이동 등 멤버 정보 변경 시 처리 
* 웹훅의 타이틀이 비어 있는 경우 렌더링 개선 
* 클라이언트 로그인 화면에서 뒤로 가기 디자인 개선 
* 검색 시 대/소문자 구분하지 않도록 변경 

### 2018.02.20
#### Messenger
* 특정 링크 전송 시 메신저에서 웹 링크로 이동하는 증상 해결

### 2018.02.12 
#### Mail 
* 예약 메일 기능 추가 (최대 2개월 이내 설정 가능)
* 발송 대기 기능 추가 (설정에서 최대 3분 대기 설정 가능)
* 메일 수/발신 시, 중요(!) 기능 추가
* 메일 쓰기창 내, From 노출/숨김 기능 추가
* 보내는 사람 이름 추가 등록/변경 가능 (최대 10개 등록 가능)
* 임시 저장 버튼 제공 (기존 제공되던 자동 임시 저장에 추가되는 기능)
* 파일 첨부 시, 자동으로 대용량으로 변경 지원
* To/Cc 입력 값 드래그로 순서 변경

### 2018.02.08 

#### Project 
* GNB를 통해 서비스 이동 시, 서비스별 마지막 화면으로 이동하도록 개선
* 오피스 문서 뷰어 및 편집 제공 (폴라리스 오피스 for Dooray!, 첨부파일 목록의 편집 아이콘 클릭)
* 첨부파일 목록 최신순으로 정렬 변경
* 첨부파일 전체 다운로드 추가
* To/Cc 입력 값 드래그로 순서 변경

#### Calendar  
* 일정 공개/비공개 설정 기능 추가
* 일정 바쁨/한가함 설정 기능 추가 (기본 캘린더만 반영)
* 주말 제외 옵션 추가
* 거절 일정 제외 옵션 추가
* 바 캘린더 5분/10분 전 알림 추가
* 첨부파일 전체 다운로드 추가

#### Drive 
* zip 파일 해제 시, 폴더 내 일본어 파일명이 깨지는 버그 수정
* 드라이브 휴지통 내 영구 삭제 파일 조회 화면 제공
* 드라이브 왼쪽 메뉴 폴더에 파일 drag&drop으로 이동
* 드라이브 URL 개선 (파라미터 제외 및 URL로 LNB 특정 폴더 자동 선택)

### 2018.02.05 

#### Messenger 
* Command 기능 추가
* 중국 텐센트 푸시 추가
* 파일 업로드/다운로드 제한 설정 추가 
* 푸시에 대화방 명 표시

### 2018.01.15  

#### Project  
* 하위 업무 등록 시 기본 템플릿이 있으면 기본템플릿 조건을 채우도록 수정
* 프로젝트함에서 종료된 프로젝트를 진행하기 시 동작안되는 문제 수정
* 프로젝트 신규 추가 후 본창이 신규 프로젝트 정보 + 목록 표시되도록 수정
* 프로젝트명 변경 후 본창의 프로젝트명이 반영되지 않는 문제 수정
* 첫 진입시에 내 프로젝트가 보이지 않는 현상 수정
* 프로젝트함 > 대시보드 > 마일스톤 현황에서 완료 마일스톤 제외 오동작 수정
* 임시보관함 상세에 프로젝트 코드가 없으면 본문 표시 오류 수정
* 새 업무 쓰기 시 현재 보고 있는 업무 본문의 프로젝트를 자동 선택함
* 프로젝트 멤버가 나갈 때 멤버그룹도 반영되게 수정
* 메일을 업무로 등록하는 중에 취소하면 이어쓰기/삭제를 할 수 없는 현상 수정

#### Mail 
* 첨부 파일 '전체 다운로드' 기능 추가

#### Calendar  
* 2주, 3주뷰 추가
* 시작 요일 설정 추가
* 일정 기본뷰 설정 추가
* 캘린더 디자인 개선
* 일정 알림 받지 않기 설정 오류 수정
* 반복 일정에서 멤버 추가/삭제 시 변경 메일 발송 오류 수정

#### Drive 
* 별표파일, 휴지통에서 파일 업로드 가능하도록 개선
* 드라이브 목록에서 선택된 파일 개서 노출
* 상세보기 영역에서 파일 영구 삭제 시 알럿 노출 추가
* 드라이브 파일 목록에서 폴더 더블 클릭 시, LNB 메뉴가 변경되지 않는 현상 수정
* 폴더명에 #이 있는 경우 업로드 시 폴더 생성 안되는 버그 수정
* 폴더 이름이 긴 경우, 경로 노출 UI 버그 수정

#### Contacts 
* 외부 메일 주소를 주소록에 추가한 경우 프로필에서 주소록 정보 활용되게 개선
* 별표 연락처에서 별표 해제 시, 상단 기능 버튼이 활성화로 풀리는 버그
* 이름이 이메일 형식으로 입력된 경우, 연락처 선택해서 메일 발송 시, 수신인에 추가되지 않는 버그
