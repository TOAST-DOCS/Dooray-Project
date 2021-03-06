## Dooray! > Project > 서비스 상세 가이드  

## 프로젝트 만들기
### 프로젝트 추가
즐겨찾는 프로젝트 옆의 + 버튼을 이용해서 프로젝트를 추가할 수 있습니다. 프로젝트의 제목과 설명만 입력하고 간단하게 프로젝트를 만들 수 있습니다.
(참고로 `손님 권한`과 `관리자만 프로젝트 추가` 로 설정된 경우 프로젝트 추가 메뉴가 보이지 않습니다.)

![프로젝트 추가](http://static.toastoven.net/prod_dooray_project/detail/01_pjt_detail_addpjt.png  )
<center>[그림] 프로젝트 만들기</center>

![프로젝트 추가](http://static.toastoven.net/prod_dooray_project/detail/02_pjt_detail_member.png)
<center>[그림] 프로젝트 추가 </center>                                                                               

### 프로젝트명
프로젝트 이름이고, 프로젝트에 있는 업무를 지칭할 때 사용합니다. 예를들어, 프로젝트명이 ‘쇼핑몰개선’이고 그 프로젝트의 56번 업무는 ‘쇼핑몰개선/56’이라고 표현합니다.

### 설명
마크다운이나 위지윅 형식으로 자유롭게 내용을 기술합니다. 짧은 내용부터 이미지를 포함한 긴 내용까지 자유롭게 사용할 수 있습니다.

## 권한 설정하기

### 대시보드 권한 설정
프로젝트 설정된 서비스 내역을 대시보드를 통해 한 눈에 확인할 수 있으며 서비스별 각각 권한 옵션을 선택해서 대시보드를 설정할 수 있습니다. 

![권한 설정](http://static.toastoven.net/prod_dooray_project/detail/03_pjt_detail_project_dashbord.png)
<center>[그림] 프로젝트 대시보드 권한 설정</center>    

### 서비스 별 권한 설정
업무/드라이브/위키 서비스 별로 권한 설정을 할 수 있습니다. 프로젝트 설정에서 각 서비스 탭으로 들어가 권한을 설정할 수 있습니다.

![권한 설정](http://static.toastoven.net/prod_dooray_project/detail/03_pjt_detail_project_settings.png)
<center>[그림] 프로젝트 설정에서 업무/드라이브/위키 탭 선택 후 권한 설정</center>    

### 업무 권한 설정하기
읽기, 등록, 편집, 이동/삭제/공유 기능에 대해 각각 권한 옵션을 선택해서 설정할 수 있습니다.

![업무 권한 설정](http://static.toastoven.net/prod_dooray_project/detail/04_pjt_detail_project_settings.png)
<center>[그림] 업무 권한 설정 옵션</center>  

### 읽기 권한
업무에 접근할 수 있는 권한입니다.
- 멤버와 업무 등록자/담당자/참조자 읽기 가능: 프로젝트 멤버는 업무에 접근할 수 있습니다. 혹은 멤버가 아니어도 담당자, 참조자로 지정된 경우면 업무에 접근해서 업무 내용을 읽을 수 있습니다.
-	모두 읽기 가능: 멤버 비멤버 구분 없이 모두 접근해서 업무 내용을 읽을 수 있습니다. 조직이 여러 개면, 조직을 선택할 수 있고, 선택된 조직의 조직원들이 업무 읽기 권한을 갖게 됩니다. 

### 등록 권한
- 멤버만 등록 가능: 프로젝트 멤버만 업무를 등록할 수 있습니다. 비멤버는 업무를 등록할 수 없습니다.
-	모두 등록 가능: 멤버 비멤버 구분 없이 모두 접근해서 업무를 등록할 수 있습니다. 조직이 여러 개면, 조직을 선택할 수 있고, 선택된 조직의 조직원들이 업무를 등록할 수 있습니다.

### 편집 권한
- 본인이 등록한 업무만 편집 가능: 내가 등록한 업무만 편집할 수 있습니다. 다른 사람이 등록한 업무에 대해서는 편집할 수 없습니다. 
- 멤버는 모든 업무 편집 가능: 프로젝트의 멤버만 업무를 편집할 수 있습니다. 프로젝트 멤버라면, 내가 등록하거나 다른 사람이 등록한 모든 업무를 편집할 수 있습니다.
- 멤버, 비멤버 모든 업무 편집 가능: 멤버와 비멤버 모두 업무 편집 권한을 갖게 됩니다. 멤버라면 해당 프로젝트의 모든 업무에 대해 편집할 수 있고, 비멤버라면 접근할 수 있는(읽기 권한이 있는) 업무에 대해 편집 할 수 있습니다. 
- 모든 업무 편집 불가능: 멤버, 비멤버 구분 없이 관리자를 제외한 그 누구도 업무 편집을 할 수 없습니다.
- 편집의 범위: 제목과 본문 편집, 업무 우선순위 조정, 일정과 마일스톤 변경, 태그 등록, 상위/하위 업무 추가, 공지 등록과 내림, 첨부파일의 삭제

### 첨부파일의 삭제 
- 본인이 업로드한 첨부파일은 스스로 삭제할 수 있습니다. 
- 다른 사람이 업로드한 첨부파일의 삭제는 업무의 삭제 권한을 따릅니다. 
    - 예 1) 본인이 등록한 업무만 편집 가능한 경우, 다른 사람이 올린 첨부 파일은 삭제할 수 없습니다.
    - 예 2) 멤버는 모든 업무 편집 가능의 경우, 다른 사람이 올린 첨부 파일에 대해 프로젝트 멤버는 삭제할 수 있지만 프로젝트 비멤버는 삭제할 수 없습니다.
    
### 이동/삭제/공유하기 권한
- 본인이 등록한 업무만 이동/삭제/공유 가능: 업무를 등록한 본인만 이동/삭제/공유하기를 할 수 있습니다.
-	멤버는 모든 업무 이동/삭제/공유 가능: 프로젝트의 멤버는 내가 등록한 업무가 아니라도 이 프로젝트의 모든 업무에 대해 이동/삭제/공유 권한을 갖게 됩니다.
-	모든 업무 이동/삭제/공유 불가능: 업무를 이동하거나 삭제하거나 공유하는 권한은 관리자에게만 주어집니다.

### 권한 설정 예시
#### 전체 공개 프로젝트를 만들고 싶을 때 
-	읽기와 등록은 모두 가능으로 선택해주세요. 조직이 여러 개면 공개할 조직을 선택해주세요.
-	편집도 모두 가능하게 하려면 멤버, 비멤버 모두 편집 가능 옵션을 선택해주세요. 

#### 일반 프로젝트를 만들고 싶을 때
- 읽기는 멤버와 등록자, 담당자, 참조가 가능으로 선택해주세요.
-	등록은 멤버만 가능하도록 선택해주세요.
-	편집은 아래 내용을 참고해서 원하는 방향으로 선택해주세요.
    -	비멤버가 업무를 읽을 수는 있지만 편집 권한을 주고 싶지 않은 경우: 멤버만 가능으로 편집 권한을 선택해주세요.
    -	업무를 함께 하는 비멤버에게는 편집 권한을 주고 싶은 경우: 멤버와 비멤버 모두 편집 가능하도록 선택해주세요.

#### 문의, 접수, 신고 용도의 프로젝트를 만들고 싶을 때
-	문의, 접수, 신고 용도의 프로젝트는 모두가 등록할 수 있지만 모두가 읽을 수는 없어야 합니다. 
-	읽기는 멤버와 업무 등록자, 담당자, 참조자만 가능하도록 선택해주세요.
-	등록은 모두 가능하도록 선택해주세요. 조직이 여러 개면 공개할 조직을 선택해주세요.
-	편집은 아래 내용을 참고해서 원하는 방향으로 선택해주세요.
    -	글을 등록한 사람만 편집할 수 있도록 하려면: 등록자만 편집 가능으로 선택해주세요.
    -	업무를 처리하는 멤버들만 편집할 수 있도록 하려면: 멤버만 편집 가능으로 선택해주세요. 이 경우, 등록자가 비멤버인 경우는 본인이 등록한 글을 편집할 수 없습니다.
    - 업무를 처리하는 멤버와 등록한 사람 모두 편집할 수 있도록 하려면: 멤버와 비멤버 모두 편집 가능하도록 설정해주세요. 이 경우 업무를 처리하는 멤버들도 편집을 할 수 있고, 등록자가 비멤버여도 본인이 등록한 글을 편집할 수 있습니다. 다만, 등록자 외 다른 비멤버가 참조 된다면, 참조된 비멤버도 편집 권한을 가질 수 있음을 염두 해주세요. 
    -	아무도 편집하지 못하게 하려면: 모두 편집 불가능으로 선택해주세요. 이 경우 글을 등록한 등록자와 업무를 처리하는 멤버 모두 편집이 불가능합니다. 관리자만 편집을 할 수 있습니다.

### 드라이브/위키 권한 설정하기
업무 설정과 마찬가지로, 프로젝트의 설정 화면에서 드라이브와 위키 탭을 선택한 후 권한 설정을 할 수 있습니다. 
드라이브와 위키의 권한도 읽기/등록/편집/삭제의 권한을 각각 설정할 수 있습니다.

![드라이브 권한 설정](http://static.toastoven.net/prod_dooray_project/detail/05_pjt_detail_drive_settings_option.png)
<center>[그림] 드라이브 권한 설정 옵션</center>   

![위키 권한 설정](http://static.toastoven.net/prod_dooray_project/detail/06_pjt_detail_wiki_settings_option.png)
<center>[그림] 위키 권한 설정 옵션</center>   

## 프로젝트 관리자를 위한 프로젝트 설정
Dooray! Project에서는 프로젝트별로 1명 이상의 관리자를 지정할 수 있습니다. 프로젝트 관리자와 멤버 간에는 권한 차이가 거의 없습니다. 다만 ‘기본 설정’과 ‘웹 훅’은 설정을 변경했을 때 미치는 영향이 크기 때문에 프로젝트 관리자만 할 수 있습니다.

### 기본 설정

#### 상태
- 프로젝트 상태를 ‘보관’으로 변경하면 더 이상 새로운 업무를 등록하거나 댓글을 달 수 없습니다.
![프로젝트 기본 설정](http://static.toastoven.net/prod_dooray_project/detail/07_pjt_detail_project_settings_2.png)
<center>[그림] 프로젝트 기본 설정</center>   

### 업무/드라이브/위키의 사용 설정
#### 업무 사용 설정
- 업무 탭을 선택하고, 사용 설정 메뉴로 들어가서 설정할 수 있습니다.
-	업무의 사용 설정은 사용함으로만 선택할 수 있습니다. 
-	보드와 플래닝 기능에 대해서는 사용을 원하는 기능을 체크하고 저장합니다.

#### 업무/ 보드 /플래닝 활용 
- 업무 : 프로젝트에 등록된 모든 업무를 확인할 수 있습니다.
-	보드 : 마일스톤별 업무를 칸반보드 형태로 확인할 수 있습니다. 업무 현황을 파악하기 쉬우며 마일스톤이 있는 업무에 대해 담당자들의 업무를 직관적으로 확인이 가능합니다.
    * 단 마일스톤이 있는 업무만 확인이 가능합니다.
- 플래닝 : 마일스톤이 없는 업무를 확인하고 마일스톤을 계획할 수 있습니다.

#### 드라이브 사용 설정
-	드라이브 탭을 선택하고 사용 설정 메뉴로 들어가서 설정할 수 있습니다.

#### 위키 사용 설정
- 위키 탭을 선택하고, 사용 설정 메뉴로 들어가서 설정할 수 있습니다.
![서비스별 사용 설정](http://static.toastoven.net/prod_dooray_project/detail/08_pjt_detail_project_drive_wiki.png)
<center>[그림] 업무/드라이브/위키 서비스별 사용 설정</center>   

### 프로젝트 삭제
프로젝트 삭제는 테넌트 소유자 / 테넌트 관리자 / 조직 관리자만 가능합니다.
해당 프로젝트 관리자는 '보관'으로 변경만 가능합니다. 
따라서 프로젝트 삭제를 원하시면 조직관리 화면에 접근 가능한 관리자에게 요청해 주세요. 

관리자는 [조직 관리] 메뉴에서 프로젝트를 삭제할 수 있습니다. 
![프로젝트 삭제](http://static.toastoven.net/prod_dooray_project/detail/Project_detail_02_ko.png)
<center>[그림] 프로젝트 삭제</center> 

영구 삭제를 원하시면 삭제 탭(위 화면 참고)에서 [영구 삭제] 버튼을 눌러주세요.

### 웹 훅
Dooray!는 아웃고잉 웹 훅(Outgoing Webhook)기능을 지원합니다. Dooray! 프로젝트에 업무, 댓글이 등록되거나 업무의 변경된 상태를 추가한 URL로 전달받을 수 있습니다. 아웃고잉 웹 훅은 프로젝트 내용을 어디든 외부로 전송할 수 있는 보안 위험 때문에 프로젝트 관리자만 설정할 수 있으며, 프로젝트 설정에서 [웹 훅] 메뉴를 통해 설정할 수 있습니다. 아래의 웹 훅 추가 화면에서 Dooray! 이벤트를 내보낼 메시지 포맷은 Dooray!와 Slack의 포맷을 지원하며 알림을 받을 웹 훅 URL을 등록합니다.

#### 웹 훅 URL
- 웹 훅 URL로 입력한 곳으로 업무나 업무에 등록된 댓글을 전송합니다.

#### 발송 메세지 포맷
- 현재는 Dooray!와 Slack 포맷을 지원하고 있습니다.

####  알림 이벤트 선택
- 알림 항목 중 선별하여 받을 수 있습니다.

####  사용 여부
- 해당 웹 훅을 잠시 멈추고 싶을 때는 웹 훅을 삭제하지 않고 사용 중인 웹훅 목록에서 ‘편집’을 눌러 사용 여부를 ‘사용 안 함’으로 설정하면 됩니다.
  
![프로젝트 설정](http://static.toastoven.net/prod_dooray_project/detail/07_pjt_detail_add_webhook.png)
<center>[그림] 웹 훅 추가 화면 </center>   

#### 로그 
- 등록한 웹 훅의 동작 이력은 웹 훅 ‘로그’ 버튼을 눌러 쉽게 확인할 수 있습니다.

## 업무 등록

프로젝트당 업무 등록은 최대 9,999개까지 등록 가능합니다.

### 프로젝트 없이 업무 등록하기
Dooray!에서는 보통의 이슈 트래커나 프로젝트 관리 도구와 달리 프로젝트 없이 단발적인 업무를 등록하여 관리할 수 있습니다. ‘새 업무’ 버튼을 클릭합니다. 제목, 담당자 등을 입력하고 등록합니다.

### 간편 등록
담당자, 본문, 완료일 등은 미정이고 제목만 있는 업무를 등록할 때가 있습니다. 앞서 설명 드린 방법대로 등록하면 되지만 이런 때 사용할 수 있는 굉장히 쉽고 빠른 방법이 있습니다. 프로젝트 이름 옆에 있는 [+] 아이콘을 클릭합니다. 커다란 쓰기창이 아니라 아주 간략한 쓰기 창을 볼 수 있습니다.

![간편 쓰기창]( http://static.toastoven.net/prod_dooray_project/detail/08_pjt_detail_w.png)
<center>[그림] 간편 쓰기창 </center>   

이 레이어 팝업에서 첫 줄은 제목이고 두 번째 줄부터는 본문입니다. 제목만 입력하고 싶다면 첫 줄만 입력하고 ‘등록’ 버튼을 클릭하면 됩니다. 만일 등록 후에 연달아 계속 등록하고 싶다면 ‘저장 후 계속 등록’을 클릭합니다. 이 과정을 단축키를 이용하면 훨씬 더 빠르게 할 수 있습니다. 업무 목록 화면에서 단축키 fw를 입력합니다. 그러면 간략한 쓰기 창이 나타납니다. 제목을 입력하고 \[Ctrl\]+\[Enter\](macOS는\[Cmd\]+\[Enter\])를 입력합니다. ‘저장 후 계속 등록’을 클릭한 것과 동일하게 동작합니다. 만일 담당자 지정까지 한번에 하고 싶다면 제목에 ‘-&gt;@홍길동’을 가하면 담당자 지정까지 가능합니다.

### 메일을 업무로 등록
Dooray! 메일 서비스에서도 소개를 하겠지만, Dooray! 메일을 바로 업무로 등록을 할 수 있습니다. 외부와 메일로 커뮤니케이션을 하다가 메일 본문을 업무로 진행을 해야할 경우가 있습니다. 이럴 경우 본문을 복사해서 다시 Dooray! 프로젝트의 업무로 등록하지 않고 메일 읽기 화면 상단의 [업무로 등록] 메뉴를 선택하면, 해당 메일이 업무로 등록됩니다.

### 하위 업무 등록
유관된 업무를 하위 업무로 묶는 것은 좋은 방법입니다. Dooray! Project에서는 기존 업무를 하위로 등록하거나 새로운 업무를 하위로 등록하는 두 가지 방법을 제공합니다.

#### 기존 업무를 하위로 등록하기
- 제목으로 검색하여 원하는 업무를 지정합니다.
- 모든 업무를 하위 업무로 지정할 수 없습니다. 하위의 하위를 지원하지 않기 때문에 이미 하위 업무가 있는 업무는 하위 업무로 지정할 수 없습니다. 

![하위추가](http://static.toastoven.net/prod_dooray_project/detail/09_pjt_detail_addtask.png)
<center>[그림] 상/하위 업무 추가</center>   

#### 신규 업무를 하위로 등록하기
- 업무에서 ‘하위 업무 추가 > 신규 또는 불러오기 기능을 통해 하위 업무로 추가하고자 하는 업무를 추가합니다.
- 하위 업무의 관계에 있어 주의할 점이 있습니다. 하위 업무가 모두 ‘완료’가 되었을 때 상위 업무가 자동으로 ‘완료’가 되지 않습니다. 하위 업무가 모두 ‘완료’가 되지 않아도 상위 업무의 상태는 ‘완료’가 될 수 있습니다.

### 외부 사용자와 협업하기
Dooray!프로젝트를 통해 외부 사용자들과 협업을 하고자 할 경우, 외부 사용자들을 멤버로 추가하지 않고도 함께 업무를 할 수 있습니다. 

#### 업무 담당자, 참조자에 외부 이메일 추가 
- 업무의 담당자, 참조자에 외부 이메일 주소(예.gmail.com)를 추가하면 외부 사용자들에게 업무의 본문이 외부 이메일로 발송됩니다. 외부 이메일에서 회신을 할 경우, 회신한 내용이 댓글로 등록이 되서 한 업무에서 업무 이력관리가 됩니다. 
- <Span style="color:#FF0000">※ 주) 이 때 외부 이메일로 발송된 업무 본문은 편집이 불가합니다. </span>

![외부 이메일 추가](http://static.toastoven.net/prod_dooray_project/detail/pjt_detail_external_mail.png)
<center>[그림] 외부 이메일 추가</center>  

#### 댓글을 이메일로 발송 
- 댓글로 멤버들끼리 편하게 소통을 하다가, 외부 사용자에게 전달할 내용이 있을 경우 댓글에서 바로 메일을 발송할 수 있습니다. 
- 이메일을 설정하고자 하는 프로젝트의 [프로젝트 설정 > 업무 > 메일 연동]에서 수/발신 용으로 사용하고자 하는 이메일을 생성할 수 있습니다. 
- <Span style="color:#FF0000">※ 주) 댓글을 메일로 발송한 경우, 메일로 발송되었으므로 일반 댓글과 다르게 표시되며 업무 본문과 동일하게 편집이 불가합니다. </span>

![댓글 메일 발송](http://static.toastoven.net/prod_dooray_project/detail/pjt_detail_external_mail01.png)
<center>[그림] 프로젝트 메일 설정</center> 

- 담당자와 참조자에 외부메일이 있는 경우, 댓글저장 버튼 우측 화살표를 클릭 해 메일발송을 할 수 있습니다.
![댓글 메일 발송](http://static.toastoven.net/prod_dooray_project/detail/pjt_detail_external_mail02.png)
<center>[그림] 보내고자 하는 이메일의 이름을 선택해 메일 발송</center>  

- [주의] 담당자와 참조자에 외부메일이 없는 경우는 메일발송 할 수 없기 때문에 화살표가 나타나지 않습니다.
![댓글 저장](http://static.toastoven.net/prod_dooray_project/detail/pjt_detail_save.png)
<center>[그림] 외부메일이 없는 경우 댓글저장 버튼</center> 

![메일로 발송된 댓글](http://static.toastoven.net/prod_dooray_project/detail/pjt_detail_external_mail021.png)
<center>[그림] 메일로 발송된 댓글</center>  

### 담당자 복수 지정
모든 업무에는 되도록 담당자를 한 명을 지정하여 그 업무의 책임을 명확히 하는 것이 좋습니다. 하지만 때에 따라 여러 사람이 한 업무를 하는 경우가 있습니다. 그런 경우 기존 도구에서는 사람별로 업무를 등록해야 해서 매우 불편했습니다. Dooray! Project에서는 이메일처럼 담당자에 여러 사람을 지정할 수 있습니다. 또한 담당자에 있는 각 사람별로 워크플로우를 관리할 수 있습니다.

#### 업무 진행 상태 확인 
- 담당자여러 명을 담당자로 지정할 경우 각 담당자 이름 색깔을 보고 진행 상태를 바로 파악할 수 있도록 하였습니다. 
    - 할 일 상태 : 초록 
    - 진행 중 상태: 파랑
    - 완료 상태 : 회색

![담당자상태](http://static.toastoven.net/prod_dooray_project/detail/10_pjt_detail_add_npeople.png)
<center>[그림] 담당자 여러 명 지정</center>   

#### 참조자 
- 업무의 참조자에 참조된 이름의 색상으로 읽음여부를 확인할 수 있습니다. 
    - 읽지 않음 상태 : 검정
    - 읽음 상태 : 회색

#### 담당자 참조자 변경 
- 댓글을 작성하면서 담당자, 참조자를 변경할 경우가 있습니다.
  댓글에서 -&gt;@홍길동 표기하고 댓글을 입력하면 ‘홍길동’이 해당 업무의 담당자가 되고, 기존 담당자는 참조가 됩니다. 댓글에서 "-&gt;&gt;@홍길동
  댓글..."을 입력하면 '홍길동이 해당 업무의 담당자로 추가됩니다.
- 프로젝트 멤버가 아닌 사람도 담당자나 참조로 지정 가능하며, 이 경우, 그 업무에만 읽기/쓰기 권한이 생깁니다.

## 본문과 댓글 형식
### 마크다운 작성하기

 https://nhnent.dooray.com/htmls/guides/markdown\_ko\_KR.html에 있는 마크다운 도움말을 확인해 주세요. 
 해당 페이지에서 바로 연습도 가능합니다. 왼쪽 화면이 마크다운 편집기이며, 우측이 결과 화면입니다.

### 업무 참조
본문이나 댓글에 다른 업무의 링크를 삽입할 수 있습니다. 다른 업무 읽기 화면에서 브라우저의 URL을 복사해서 본문(혹은 댓글)에 삽입할 수도 있지만 그렇게 할 경우 해당 업무가 다른 프로젝트로 이동했을 때 링크가 유효하지 않게 됩니다. 편집기에서 ‘[‘를 입력한 후, ‘업무 참조’를 선택합니다. 최근 본 업무 목록이 나타나고, 화살표 키나 마우스를 이용하여 삽입하고 싶은 업무를 선택합니다. 만일 목록에 원하는 업무가 없다면 키워드를 입력하여 제목 검색을 할 수 있습니다.

![참조]( http://static.toastoven.net/prod_dooray_project/detail/11_pjt_detail_ref_task.png)
<center>[그림] 편집기에 [ 입력</center>    

### 멘션
‘@’를 입력한 다음, 사람 이름이나 멤버 그룹을 입력하여 특정인이나 특정 멤버 그룹을 소환할 수 있습니다. 이 기능을 멘션이라고 합니다. 멘션을 하면 해당 사용자의 설정에 상관없이 알림을 보냅니다. 또한 멘션한 업무의 참조에 추가되어 해당 업무에 대한 읽기/쓰기 권한을 얻습니다. 같은 멘션이라 할지라도 누구를 멘션하냐에 따라 멤버, 나, 손님 세 경우를 시각적으로 다르게 표현합니다. 멘션 기본색은 옅은 파랑색입니다. 하지만 나를 멘션한 것은 진한 파랑색으로 표현하여 당사자가 자기를 멘션했다는 것을 더 잘 인지할 수 있도록 도와줍니다. 또한 손님을 멘션하면 회색으로 표현해서 테넌트의 정식 멤버가 아닌 것을 표현합니다.

![멘션](http://static.toastoven.net/prod_dooray_project/detail/13_pjt_detail_mention.png)
<center>[그림] `그룹 멘션/멤버/손님/나` 멘션 케이스</center>   

## 프로젝트 멤버를 위한 프로젝트 설정
### 멤버
멤버를 초대하고, 멤버 그룹을 관리하는 곳입니다.

#### 멤버 그룹
-  ‘그룹 추가’ 버튼을 클릭합니다.

![멤버그룹](http://static.toastoven.net/prod_dooray_project/detail/14_pjt_detail_add_group.png)
<center>[그림] 프로젝트 설정 &gt; 멤버 &gt; 그룹 추가</center>   

- 그룹 이름을 입력하고, 그룹에 넣고 싶은 멤버를 선택하고, ‘생성’ 버튼을 클릭합니다.
- 모든 프로젝트에는 프로젝트 멤버 전체를 뜻하는 ‘/all’이라는 멤버 그룹이 있습니다.
- 하나의 프로젝트에는 여러 직무의 사람들이 함께 합니다. 그 직무별로 멤버 그룹을 만들면 협업이 보다 쉽습니다. 

> 예를 들어, ‘쇼핑몰개편/디자인’이라는 멤버 그룹을 만들면 디자인 파트에 업무를 줄 때, 디자이너 이름을 기억할 필요가 없습니다. 담당자 입력 칸에
> ‘/디자인’이라고 입력하면 자동완성 목록에서 ‘쇼핑몰개편/디자인’을 쉽게 선택할 수 있습니다.
> 이렇게 프로젝트 내에 직무별로 다양한 멤버 그룹을 만들면 타 프로젝트간 업무 협의 때 보다 정확하게 담당자를 찾을 수 있습니다. 대개의 경우 프로젝트 이름은 알기 때문에 담당자 칸에 프로젝트 이름을 입력하면 해당 프로젝트에 있는 멤버 그룹을 볼 수 있습니다. 그 목록에서 ‘/디자인’을 찾아 선택하는 일은 어렵지 않습니다.
> 기존에 관련 프로젝트의 디자이너를 찾는 것은 매우 어려운 일이었지만 Dooray! Project에서는 멤버 그룹 덕분에 매우 쉽습니다. 이런 멤버 그룹 이름에 대해 테넌트 관리자가 가이드를 해서 규칙성을 띄면 더욱 협업하기 좋습니다.

### 마일스톤
업무 하나하나에 완료일을 지정하여 그 때까지 끝내는 것을 목표로 일할 수 있습니다. 그렇게 개별 완료일을 지정했더라도 특정 날짜를 기준으로 상품을 출시하거나 서비스를 내놓을 때 그 출시 날짜를 기준으로 업무를 관리하고 싶을 때가 있습니다. 그 때 사용하는 것이 마일스톤입니다. ‘마일스톤 추가’ 버튼을 클릭하여 마일스톤을 추가할 수 있습니다. 그리고 추가한 마일스톤으로 업무 목록에서 특정 마일스톤을 필터링해서 보는 것이 가능합니다.

![마일스톤](http://static.toastoven.net/prod_dooray_project/detail/15_pjt_detail_add_milestone.png)
 <center>[그림] 프로젝트 설정 > 마일스톤 추가</center>   

- 기간은 지정할 수도 있고, 지정하지 않을 수도 있습니다. 지정할 경우, 해당 기간이 되면 자동으로 번다운 차트가 대시보드에 생깁니다.

### 태그
업무를 분류하기 위한 목적으로 사용합니다. ‘태그 추가’ 버튼을 클릭하여 추가할 수 있습니다.

 ![태그](http://static.toastoven.net/prod_dooray_project/detail/17_pjt_detail_tag.png)
 <center>[그림] 프로젝트 설정 > 태그</center>  

####  태그명
- 태그 이름에 “그룹명:태그명”와 같이 “:”을 입력하면 “:” 앞을 그룹으로 인식하여 태그를 그룹핑할 수 있습니다.
- 태그 그룹을 만들면, 그룹 단위로 필수/1개만 선택을 활용하여 업무에서 반드시 태그를 선택하도록 필수 값으로 지정하거나 그룹 중에서 1개만 선택하도록 강제할 수도 있습니다. 정형적인 입력을 받을 때 유용합니다.

###  템플릿
템플릿은 업무에 적을 수 있는 담당자, 참조, 제목, 본문, 태그, 마일스톤, 우선순위를 미리 지정하는 기능입니다. 이 기능을 이용하면 반복적으로 업무를 등록할 때, 보다 쉽고 빠르게 등록할 수 있습니다.

#### 템플릿 활용
- 템플릿을 이용해서 업무를 등록하는 방법은 두 가지가 있습니다. 쓰기 창을 띄운 다음 ‘템플릿’을 고를 수 있고, 전체 프로젝트에서 템플릿을 확인하거나 검색해서 쓰기 화면으로 바로 진입할 수도 있습니다. 또한 프로젝트 대쉬보드의 템플릿 목록에서 바로 원하는 템플릿 링크를 클릭해서 업무를 등록할 수도 있습니다. 
- 링크를 다른 곳(예, 메일, 드라이브, 위키 등)에 전달하여 업무를 쉽게 등록하도록 가이드할 수도 있습니다.

> HR(인사) 업무 프로젝트에서는 휴가 신청, 구매 요청 등의 템플릿을 만들 수 있고, ITSM(IT Service Management)과 같은 프로젝트에서는 장비 신청, 네트워크 ACL 요청 등의 템플릿을 만들어 활용할 수도 있습니다. 템플릿은 Dooray! Project에서 가장 광범위하게 많이 사용하는 기능입니다.

![템플릿](http://static.toastoven.net/prod_dooray_project/detail/19_pjt_detail_template.png  )
<center>[그림] 쓰기 창에서 템플릿 선택 </center> 

![템플릿](http://static.toastoven.net/prod_dooray_project/detail/20_pjt_detail_template_list.png )
<center>[그림] 프로젝트 대쉬보드 > 템플릿 목록 </center>   
                                             
####  기본 템플릿
- 프로젝트에서 템플릿을 고르면 어느 정도는 정형화된 입력을 받을 수 있지만, 업무를 등록하는 사람이 템플릿을 고르지 않으면 원하는 데이터를 얻지 못해서 댓글로 다시 묻고 답하는 과정을 거칠 수 있습니다. 이런 과정을 줄이기 위해 ‘기본 템플릿’ 기능을 제공합니다.
- 템플릿 설정은 프로젝트 설정 > 업무 > 템플릿 탭 선택 > 템플릿 추가를 클릭해 템플릿 설정 화면에서 합니다.

![템플릿](http://static.toastoven.net/prod_dooray_project/detail/21_pjt_detail_setting_add_template.png)
<center>[그림] 프로젝트 설정 > 템플릿</center>   
 
- 템플릿 설정 시, ‘기본 템플릿’을 체크하면 해당 프로젝트에서 쓰기 창을 열면 자동으로 해당 템플릿이 적용됩니다.
  
![기본템플릿](http://static.toastoven.net/prod_dooray_project/detail/22_pjt_detail_default_template.png)
<center>[그림] 기본 템플릿 설정</center>   

#### 매크로 
- 템플릿을 만들 때 아래의 매크로들을 활용해보세요. 매크로를 통해 자동으로 데이터를 표기할 수 있습니다.
- 템플릿의 제목과 본문 필드에서 '$' 입력 시 매크로 변수 자동완성 제공
> 오늘 날짜가 2018/03/29 인 경우, 아래와 같이 매크로를 입력하면 자동으로 해당 데이터로 치환됩니다.
> ${year} 입력 시, 날짜의 년도를 표시합니다.(예:2018) 
> ${month} 입력 시, 날짜의 월을 표시합니다.(예:3)
> ${today} 입력 시, 날짜를 년/월/일 순으로 표시합니다.(예:2018/03/29)
> ${day} 입력 시, 일자를 표시합니다.(예:29)
> ${month2} 입력 시, 월을 표시하되 표시 형식이 다릅니다.(예:3)  
> 설명
> ${month}는 오늘 일자에 해당되는 월을 표기합니다. 
> ${month2}는${weekNum2}와 같이 사용하기 위한 매크로로 ${month2}는 그 주에 첫째주 월요일을 기준으로 월을 표기합니다. 
> * 주차의 기준은 월요일~일요일입니다.
> 예를 들어 2020년 01월이 5주로 되어 있을때 2월1일이 1월의 5주차의 금요일 입니다. 
> 이 경우 ${month2}는 해당 월을 2월 이라고 표기하지 않고 ${weekNum2}과 같이 사용하였을 때에는 1월의 5주차로 표기 됩니다. 
> ${weekNum2} 입력 시, 주차를 표시합니다. 2018년 3월 29일은 5번째 주입니다.(예:5) 

- 프로필에 설정된 이름으로 업무 작성 시 아래와 같이 매크로를 입력하면 자동으로 해당 데이터로 치환됩니다.
> ${name} 입력 시, 이름을 표시합니다.(예:Dooray) 

- 프로필에 설정된 부서가 Dooray기획 인 경우, 아래와 같이 매크로를 입력하면 자동으로 해당 데이터로 치환됩니다.
> ${department} 입력 시, 부서를 표시합니다.(예:Dooray 기획) 

#### 템플릿 예시
- 다음은 템플릿 예시입니다. 아래 그림과 같이 템플릿들을 추가해서 활용해보세요.
- 회의록에 고정으로 들어가는 항목들을 템플릿에 넣어두면 매번 동일한 양식의 문서를 불러와서 활용하기 좋습니다. 특히 회의한 오늘 날짜가 자동으로 들어가도록 ${today} 매크로를 활용해보세요.  

![템플릿 예시](http://static.toastoven.net/prod_dooray_project/detail/22-1_pjt_detail_template1.png)
<center>[그림] 회의록 템플릿</center>   

- 주간회의 템플릿은 아래 본문에서 설명한 대로 활용해보세요. 회의 준비와 회의록 정리로 시간을 허비하지 않을 수 있습니다. 

![템플릿 예시](http://static.toastoven.net/prod_dooray_project/detail/22-2_pjt_detail_template2.png)
<center>[그림] 주간회의 템플릿</center>   

- 서비스 QA항목 템플릿은 서비스 주요 기능을 테스트할 때 본문에 체크할 수 있는 항목을 만들어 활용한 예시입니다. 

![템플릿 예시](http://static.toastoven.net/prod_dooray_project/detail/22-3_pjt_detail_template3.png)
<center>[그림] 서비스 QA항목 템플릿</center> 

- 버그 등록 템플릿은 서비스별로 만들어두면 편리합니다. 각 서비스별 담당자 혹은 그룹 지정을 쉽게 할 수 있고, 버그 확인을 위해 알아야 할 정보들을 본문에 작성하면 놓치지 않고 확인을 할 수 있습니다. 특히 태그 그룹을 만들고, 그룹의 속성(필수, 한 개만 선택)도 활용하면 편리합니다.

![템플릿 예시](http://static.toastoven.net/prod_dooray_project/detail/22-4_pjt_detail_template4.png)
<center>[그림] 버그 등록 템플릿</center> 

### 공유 링크
프로젝트 내 멤버가 아닌 멤버에게 특정 업무를 공유하고 싶을 때 '공유하기' 기능을 통해 업무를 링크로 공유할 수 있습니다.  공유하기 권한은 프로젝트 설정에서 지정할 수 있습니다. 

![공유하기]( http://static.toastoven.net/prod_dooray_project/detail/23_pjt_detail_share_task.png)
<center>[그림] 업무 공유하기</center>   

-	공유하고자 하는 업무의 [추가 작업 > 공유하기]를 선택합니다. 
-	공유할 수 있는 링크를 생성하기 위해 ‘링크 추가’를 클릭합니다.
-	링크를 생성할 때에 공유기간, 공유 항목, 공유 범위를 지정할 수 있습니다. 

![공유하기]( http://static.toastoven.net/prod_dooray_project/detail/23_1_pjt_detail_share_task.png)
<center>[그림] 공유 링크 생성</center>   

#### 공유 기간
- 해당 날짜까지 공유합니다. 날짜가 지나면 링크는 유효하지 않습니다.

#### 공유 항목

- 첨부 파일까지 공유할 것인지 설정합니다.

#### 공유 범위
- 테넌트내 멤버, 손님 이외 외부 사용자에게도 공유할 수 있습니다.   

이렇게 특정 업무를 공유하면 업무 상단에 공유 중이라고 표시가 되고, 프로젝트 관리자는 ‘프로젝트 설정 > 공유 링크’에서 프로젝트 내에 공유된 업무를 한 눈에 파악할 수 있습니다. 
조직 관리자도 해당 조직 내 공유된 업무 목록 전체를 화면 우측의 [설정 > 조직 관리 > 서비스 관리 >공유 링크]에서 확인할 수 있습니다. 

![공유업무](http://static.toastoven.net/prod_dooray_project/detail/25_pjt_detail_share_task_list.png)
<center>[그림] 공유 업무 목록 </center>   

## 업무 상태
### 업무 상태 설정
프로젝트는 '할 일', '진행 중', '완료' 세가지 상태를 기본으로 제공합니다. 
세가지 기본 상태에서 필요하다면 프로젝트에 알맞는 상태를 추가 설정하여 사용할 수 있습니다.  

![업무상태](http://static.toastoven.net/prod_dooray_project/detail/project_setting.png)
<center>[그림] 업무 상태 추가</center>   

### 업무 상태 변경하기
업무에 접근이 가능한 멤버 누구나 업무 상태 변경이 가능합니다. 
![업무상태](http://static.toastoven.net/prod_dooray_project/detail/project_setting2.png)
<center>[그림] 업무 상태 변경</center>   
- 업무의 좌측 상단에서 나의 업무 상태 편집이 가능합니다.
- 업무의 우측 상단에서는 업무 상태와 담당자의 업무 상태 편집이 가능합니다.

### 업무의 상태와 담당자의 상태 구분하기
업무의 담당자가 한 명일 때는 업무 상태와 해당 업무의 담당자 상태가 같지만, 담당자가 2명 이상이면 그 상태가 일치하지 않을 수 있습니다.

예를 들어, 56번 업무에 A, B 두 사람이 담당자라고 가정할 때, 업무를 등록했을 때 해당 업무의 상태와 담당자인 A의 상태, B의 상태는 모두‘할 일’입니다. 하지만 A가 자신의 상태를 ‘진행 중’으로 바꾸면, A의 상태는 당연히 ‘진행 중’이지만 B의 상태는 여전히 ‘할 일’입니다. 그리고 업무는 여전히 ‘할 일’ 상태 입니다. 담당자 중 한 사람이라도 제일 왼쪽 상태에 있을 경우 업무의 상태는 담당자 중 제일 왼쪽 상태에 있는 상태 값을 따라갑니다. A가 ‘완료’로 변경해도 업무의 상태는 여전히 ‘할 일’입니다. B가 아직 마치지 않았기 때문입니다. B의 상태가 ‘진행 중’으로 변경되면 업무의 상태도 ‘진행 중’으로 변경됩니다.  
모든 담당자의 상태를 ‘완료’로 변경하고 한다면 업무의 상태를  ‘완료’로 변경해주세요,

모든 담당자가 ‘할 일’이면 업무 상태는 ‘할 일’이고, 모든 담당자가 ‘완료’이면 업무 상태는 ‘완료’입니다. 그 외 업무 상태는 담당자 중 상태가 제일 왼쪽에 위치한 담당자의 상태를 따라갑니다.

### 담당자 상태 바꾸기/되돌리기
담당자가 아니지만 해당 업무가 이미 끝났다는 것을 알 때가 있습니다. 이 때 해당 담당자에게 메신저나 메일로 업무의 상태를 바꾸라고 요청할 수 있지만 매우 번거롭습니다. Dooray!에서는 그런 상황에서, 업무 상태가 잘못되었다는 것을 발견한 사람이 바로 고치는 것을 권장합니다. 해당 업무에 대한 접근 권한이 있다면 담당자가 아니어도 누구나 담당자 개별의 상태를 임의로 바꿀 수 있습니다. 업무 상태를 표시한 곳을 클릭하면 담당자별 상태를 할 일/진행 중/완료 어떤 상태로든 바꿀 수 있습니다. 참고로 이렇게 권한을 많이 부여한 만큼 그런 행위에 대한 기록을 모두 남기고 있습니다. 따라서 권한이 있다고 함부로 바꾸는 일은 쉽게 발생하지 않습니다.

## 업무 속성 변경
#### ‘편집’ 버튼을 이용한 변경
-	‘편집’ 버튼을 클릭하면 새 창에서 업무의 모든 항목을 입력하거나 수정할 수 있습니다. 한번에 두 개 이상의 항목을 수정할 때 유용합니다.

#### 담당자, 참조 인플레이스 편집
- 담당자와 참조만 바꾸고 싶을 때는 담당자, 참조에서 \[그림\] 연필 아이콘을 클릭합니다.

 ![편집](http://static.toastoven.net/prod_dooray_project/detail/26_pjt_detail_edit_to.png )
 <center>[그림] 담당자 편집</center>   

- 담당자 영역에 마우스를 올리면 ‘내가 하기’ 버튼이 나타납니다. 해당 버튼을 클릭하면 기존 담당자들은 참조에 추가되고, 나만 담당자에 남게 됩니다.
- 멤버 그룹에게 업무를 주고, 멤버 그룹 중 실제로 업무를 할 사람이 ‘내가하기’를 눌러 담당자를 명확하게 할 때 사용하면 유용합니다.

#### 제목 인플레이스 편집
- 제목에 마우스를 올려 \[그림\] 연필 아이콘을 클릭하면 제목만 편집할 수 있습니다.
  
  ![제목 편집](http://static.toastoven.net/prod_dooray_project/detail/28_pjt_detail_inplace_title.png)
  <center>[그림] 제목 편집</center>   

#### 본문 인플레이스 편집
- 업무 읽는 화면에서 \[그림\] 연필 아이콘을 클릭하면 본문만 편집할 수 있습니다.

 ![본문 편집](http://static.toastoven.net/prod_dooray_project/detail/29_pjt_detail_inplace_body.png)
  <center>[그림] 본문 편집</center>  

-  ‘저장’을 누르면 저장을 하고 바로 읽기 화면으로 바뀌지만, ‘저장 후 계속’을 클릭하면 저장하고 계속 편집 모드를 유지합니다. ‘저장 후 계속’을 클릭했을 때, 임시 저장을 하는 것이 아니라 실제로 서버에 저장하는 것이기 때문에 다른 사람이 확인할 수 있으니 주의해야 합니다. 

#### 업무 만기일 설정
- 업무 우측 상단 영역에서 만기일을 설정 할 수 있습니다.
- 기본은 만기일 미정이며, 없음으로 설정할 경우 업무 상태 및 담당자 상태 설정이 불가합니다. 

 ![만기일 편집](http://static.toastoven.net/prod_dooray_project/detail/30_pjt_detail_inplace_duedate.png)
 <center>[그림] 만기일 편집</center>  

#### 태그 인플레이스 편집
- 제목 바로 아래 \[그림\] 태그+ 를 클릭하면 태그를 편집할 수 있습니다.
- 그룹으로 묶은 태그는 속성에 따라 한 개만 선택할 수도 있고, 반드시 선택해야하기도 합니다.
  
  ![태그 편집](http://static.toastoven.net/prod_dooray_project/detail/31_pjt_detail_inplace_tag.png)
  <center>[그림] 태그 편집</center>  

#### 마일스톤 인플레이스 편집
- 상단 영역의 ‘마일스톤’을 클릭하여 마일스톤을 편집할 수 있습니다

 ![마일스톤 편집](http://static.toastoven.net/prod_dooray_project/detail/32_pjt_detail_inplace_milestone.png)
 <center>[그림] 마일스톤 편집</center>  

#### 다른 프로젝트로 이동
- ‘추가 작업 &gt; 프로젝트 이동’을 선택하여 다른 프로젝트로 이동할 수 있습니다. 이동할 때, 이동할 프로젝트의 태그나 마일스톤을 지정하여 한번에 변경하는 것도 가능합니다.

 ![프로젝트 이동](http://static.toastoven.net/prod_dooray_project/detail/33_pjt_detail_move_project.png)
 <center>[그림] 프로젝트 이동</center>  

### 댓글 작성하기
#### 일반적인 댓글 작성

- 업무에 대한 피드백을 댓글을 달아 주고 받을 수 있습니다. 댓글에 적는 글은 짧은 글뿐만 아니라 긴 글도 가능합니다. 본문과 댓글에 적을 수 있는 내용과 문서를 꾸밀 수 있는 서식은 동일합니다.

#### 멘션을 이용한 담당자 변경
- 담당자를 바꿀 때, 댓글에 업무를 위임한다고 적고 실제 담당자를 바꾸지 않는 경우가 많습니다. Dooray!에서는 이런 문제를 쉽게 해결할 수 있습니다.
- 멘션 앞에 ‘-&gt;’기호를 붙이면 멘션된 멤버나 손님은 담당자가 되고 기존 담당자는 참조에 추가됩니다. 마치 손가락으로 담당자를 가리키는 모습을
 연상하면 됩니다.
- Dooray! Project는 담당자가 2명, 3명이 될 수 있습니다. 담당자를 추가하고 싶을 때는 멘션 앞에 ‘-&gt;&gt;’을 붙입니다.

#### 내가 쓴 댓글 
- 업무에 대해 댓글을 많이 주고 받게 되는데, 내가 어떤 댓글을 썼는지 알기 어려울 때가 종종 있습니다. 이럴 때, 프로젝트 업무함 위에 ‘내가 쓴 댓글’ 함을 누르면 모두 일괄 확인할 수 있습니다. 유사 서비스에서는 제공하지 않는 기능으로 자신이 썼던 댓글들을 관리할 수 있습니다.

### 변경 히스토리 
#### 업무 변경 사항 노출 
- 업무와 관련된 모든 편집 내용은 히스토리로 제공합니다. 업무 제목, 담당자, 일정, 본문 텍스트, 파일 첨부와 같은 업무 변경 외에도 덧글 변경 사항을 확인하고 싶을 경우 업무 본문 우측 하단에 있는 ‘변경 사항 포함’ 항목을 체크하세요. 본문과 덧글의 모든 변경 정보를 확인할 수 있습니다.

  ![변경 히스토리](http://static.toastoven.net/prod_dooray_project/detail/34_pjt_detail_edit_history.png)
  <center>[그림] 변경 히스토리</center>  

### 창 크기 조절
#### 새 창 띄우기
- 읽기 화면에서 우측 상단의 \[그림\] 새 창 아이콘을 클릭하면 현재 읽고 있는 업무를 새 창으로 띄울 수 있습니다. 단축키는 vn(ViewNew)입니다.

#### 창을 넓게 보기
- 분할 뷰를 이용할 때 읽기 화면이 좁은 경우가 있습니다. 이 때는 \[그림\] 본문 확대 아이콘을 클릭하여 확장 뷰로 넓게 볼 수 있습니다. 단축키 vw(ViewWide)입니다. 다시 확장 뷰에서 일반 뷰로 돌아가는 것은 아이콘을 다시 클릭하거나 vw을 다시 입력하면 됩니다.

### 화면 모드 변경 
#### 회의 모드
- 빔 프로젝터에 Dooray! 화면을 띄워놓고 회의를 하는 경우가 있습니다. 이때 화면의 글자 크기가 작아서 보기 어렵다면, ‘회의 모드’가 도움이 됩니다.
- \[그림\] 본문 보기 아이콘을 클릭하고 ‘회의 모드’를 선택합니다. 회의모드는 업무 자체를 제외한 나머지 영역을 모두 없애고 업무 글자 크기를 키워줍니다. \[ESC\]를 누르거나, 화면 맨 아래 ‘닫기’ 버튼을 클릭하여 ‘회의 모드’에서 나갈 수 있습니다. 단축키는 vm입니다.

#### 발표 모드
- 마크다운으로 작성한 업무를 자동으로 발표용 문서로 만들어주는 기능입니다. 발표 문서를 따로 만들지 않고도 업무 본문을 프리젠테이션 모드로 전환할 수 있습니다.
- 본문 보기 아이콘을 클릭하고 ‘발표 모드’를 선택합니다. 참고로 단축키는 vp (View Presentation)입니다

  ![발표 모드](http://static.toastoven.net/prod_dooray_project/detail/35_pjt_detail_vp_mode.png)
  <center>[그림] 발표 모드 선택</center>  

- 원하는 발표 화면의 스킨을 선택하고 ‘확인’을 클릭하면 발표 화면으로 전환됩니다. 다음 화면 혹은 다음 효과로 이동하는 것은 키보드의 \[\]키를 누르면 됩니다.
- 만일 내용이 많아 한 화면에 나오지 않을 경우, \[\]을 클릭하면 자동으로 스크롤되어 가려져 있는 다음 내용을 볼 수 있습니다.
- 발표를 하다 Shift 키 누르면 스팟라이트가 표시되며, Shift + Ctrl 키를 누를 경우 스팟라이트를 확대해주는 돋보기 기능이 제공됩니다.

### 알림 설정
#### 프로젝트, 메일, 캘린더, 드라이브, 위키 알림 설정

- Dooray! 프로젝트, 메일, 캘린더, 드라이브, 위키 서비스에 대한 알림을 설정할 수 있습니다. 프로젝트 담당, 참조, 보낸 업무별로 알림을 받고자 하는 프로젝트를 선택할 수 있으며 새 업무와 새 댓글 등록 시 알림을 받도록 선택할 수 있습니다.
- 메일도 전체 메일 또는 알림을 받고자 하는 메일함을 선택할 수 있으며, 멘션 소식에 대한 알림도 선택할 수 있습니다. 
- 알림 방법은 모바일 앱,메신저, 외부 메일로 받는 방법을 택할 수 있습니다.

 ![알림 설정](http://static.toastoven.net/prod_dooray_project/detail/36_pjt_detail_setting.png)
 <center>[그림] 알림 설정</center>  

#### 스트림 설정
프로젝트, 메일, 캘린더, 드라이브, 위키 스트림 설정
- Dooray! 프로젝트, 메일, 캘린더, 드라이브, 위키 서비스에 대한 스트림을 설정할 수 있습니다. 프로젝트 담당, 참조, 보낸 업무별로 스트림을 받고자 하는 프로젝트를 선택할 수 있으며 새 업무와 새 댓글 등록 시 스트림을 받도록 선택할 수 있습니다.
- 메일도 전체 메일 또는 스트림을 받고자 하는 메일함을 선택할 수 있으며, 멘션 소식에 대한 스트림도 선택할 수 있습니다.
- 모든 서비스에 내가 멘션된 소식은 항상 받을 수 있도록 설정할 수 있습니다. 

## 업무 내보내기
- 업무를 PDF 파일 또는 메일로 내보내기 할 수 있습니다. (업무 더보기 버튼 클릭)
- PDF 파일 내보내기: 내보내기 시점의 본문/첨부파일 목록/댓글(선택) 내용을 PDF로 저장할수 있습니다.
- 메일 내보내기 : 내보내기 시점의 본문/첨부파일 목록/댓글(선택)을 PDF로 저장한 파일과 업무내 첨부된 파일을 메일에 자동 첨부해 메일을 발송할 수 있습니다.

## 단축키 
- Dooray! 서비스의 단축키는 아래와 같습니다.  
- 화면별 Shift + ? 를 선택하면 해당 화면에서 사용할 수 있는 단축키 모음을 확인하실 수 있습니다. 

| 유형   | 단축키  |  기능 |
|--------|---------|-----------------------------| 
|업무 읽기 화면 | vn | 새 창(View New window) |
|   | vp | 발표 모드(View Presentation mode) |
|   | vm | 회의 모드(View Meeting mode) |
|   | vw | 넓게 보기 토글(View Wide) | 
|   | cu | 퍼머넌트 주소를 클립보드로 복사(Copy Url)  |
|   | cb | 본문을 클립보드로 복사(Copy Body) |
|   | cn | "(문의)Dooray/56"이 업무 문자열을 클립보드로 복사(Copy Number) | 
|   | cs | 업무 제목을 클립보드로 복사(Copy Subject) | 
|쓰기 화면 | ww | 쓰기 창(프로젝트면 업무 쓰기, 메일이면 메일 쓰기, 캘린더면 캘린더 쓰기)(Write Write) | 
|   | fw | 간편 업무 쓰기 창(Fast Write) | 
|   | cc |  댓글 창으로 포커스(Comment Comment) | 
|   | wt | 업무 쓰기 창(Write Task) | 
|   | wm | 메일 쓰기 창(Write Mail) | 
|   | we | 일정 쓰기 창(Write event) | 
|   | wk | 주소록 쓰기 창 | 
|서비스 이동 | gs |  스트림 열기(Go Stream) | 
|   | gp |  프로젝트 탭(Go Project) | 
|   | gm| 메일 탭(Go Mail) | 
|   | gc |  캘린더 탭(Go Calendar) | 
|   | gd | 드라이브 탭(Go Drive) | 
|   | gk |  주소록 탭 | 
|캘린더| cd | 캘린더 일간 뷰 | 
|   | cw | 캘린더 주간 뷰 | 
|   | cm | 캘린더 월간 뷰 | 
|   | c2 | 캘린더 2주 뷰 | 
|   | c3 | 캘린더 3주 뷰 | 
|  등록  | Ctrl(Cmd) + Enter | 윈도(맥) 에디터 등록 | 
|  임시 저장  | Ctrl(Cmd) + s  | 윈도(맥) 임시 저장 |
|  참조할 드라이브 폴더 선택  | Alt + Enter | 에디터에서 [ 로 참조할 드라이브 폴더 선택 | 
|  기타  | ms  | 별 찍기 토글(Mark Star)  | 
|  | Alt + 위/아래  | 줄 이동(에디터에서 여러 줄 선택 시에도 동작)  | 



