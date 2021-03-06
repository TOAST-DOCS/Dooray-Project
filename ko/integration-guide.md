## Dooray! > Project > 서비스 연동 가이드 

### 서비스 연동 

Dooray!에서는 외부 서비스와의 연동을 위해 Dooray! 프로젝트의 이벤트를 외부 서비스로 알려주는 아웃고잉 웹 훅뿐 아니라 외부 다양한 서비스를 Dooray!로 연동할 수 있는 인커밍(Incoming) 훅을 제공합니다. 인커밍 연동이란 자주 사용하는 개발, 배포, 소스 관리, 성능 관리 도구들을 Dooray!에 연동하는 것으로 외부 서비스들의 다양한 변경 사항들을 Dooray! 프로젝트 또는 Dooray! 메신저 대화방으로 쌓는 방법입니다. 
Dooray!에서는 Jenkins, GitHub, Gitlab, Trello, NewRelic, JIRA, Bitbucket, IFTTT, Grafana, Dooray! Incoming 연동을 지원하고 있습니다. 
Dooray! 프로젝트에는 GitHub, GitLab, Bitbucket,  Azure DevOps 서비스 연동이 가능하며, Dooray! 메신저 에서는 Jenkins, GitHub, GitLab, Trello, NewRelic, JIRA, Bitbucket, IFTTT, Grafana, Incoming, Sonarqube 서비스 연동이 가능합니다.  

프로젝트 업무로 인커밍 훅을 받기 위해서는 프로젝트 설정 > 업무 > 서비스 연동 > 서비스 추가에서 연동할 서비스를 선택합니다. 메신저 대화방으로 인커밍 훅을 받기 위해서는 Dooray! 메신저 설정 > 서비스 연동 > 서비스 추가에서 연동할 프로젝트를 선택합니다. 즉 해당 서비스의 소식을 받을 곳으로 연동 URL은 각 서비스의 웹 훅 설정에서 추가해야 합니다.

다음은 GitHub 프로젝트에서 Push 이벤트 발생 시, Dooray! 프로젝트로 등록되게 하는 방법입니다.  

#### 프로젝트 업무에 서비스 연동하기 

프로젝트 설정 > 업무 > 서비스 연동 > 서비스 추가 > GitHub ‘연동 추가’ 버튼을 클릭합니다. GitHub 이벤트 발생 시 연동하고자 하는 Dooray! 서비스를 선택합니다. Dooray! 프로젝트 중 하나를 선택해 Git 이벤트를 선택한 프로젝트 댓글로 받습니다. 연동 대화방을 선택하고 싶은 경우에는 메신저 설정에서 서비스 연동을 추가하면 됩니다. 
Bot 이름을 정하고 연결할 프로젝트를 체크한 후 추가 버튼을 클릭합니다. 추가 후 생성된 연동 URL을 복사합니다.

![연동](http://static.toastoven.net/prod_dooray_project/09_project_integration.png)

<center>[그림] Dooray! 서비스 연동 설정</center>

#### GitHub 프로젝트 업무에 연동하기 

Bot 연동 URL을 복사하였으면, 연동하고자 하는 서비스에 웹 훅을 걸어야 합니다. Github의 설정 페이지로 이동합니다. Webhooks & services 메뉴를 눌러 웹 훅을 추가합니다.  

![연동](http://static.toastoven.net/prod_dooray_project/02_project_integration.png)
<center>[그림] Github 설정</center>

Payload URL에 복사한 Dooray hook 연동 URL을 입력 후 저장합니다. 

![연동](http://static.toastoven.net/prod_dooray_project/03_project_integration.png)
<center>[그림] 웹 훅 추가</center>

이제 Github에 commit을 push할 때, commit message에 "fix #my-dooray-project/1234"라는 문구가 있으면 #my-dooray-project/1234에 push알림이 댓글로 달립니다. 만약 pull request를 올려 merge될 경우, 해당 태스크는 알림 댓글과 함께 자동으로 완료 됩니다.

#### GitLab 메신저 대화방에 연동하기 

Dooray! 메신저 대화방>  설정 > 서비스 연동 > 서비스 추가 > GitLab ‘추가’ 버튼을 클릭합니다. 추가 후 생성된 연동 URL을 복사합니다. 
![연동](http://static.toastoven.net/prod_dooray_project/08_project_integration.png)
<center>[그림] Dooray! 서비스 연동 설정</center>

GitLab Settings > Integration 페이지에 복사한 Dooray hook 연동 URL을 입력하고, Trigger를 선택합니다. 트리거는 아래 파란색 체크한 것들이 연동됩니다. 연동할 트리거를 선택 후 Add webhook 버튼을 클릭합니다. 

![연동](http://static.toastoven.net/prod_dooray_project/05_project_integration.png)
<center>[그림] 웹 훅 추가</center>

commit을 push할 때 message에 "fix #my-dooray-project/1234" 라는 문구를 입력하면 my-dooray-project 프로젝트의 1234번 업무에 push 알림이 댓글로 등록됩니다. 만약 pull request를 올려 merge될 경우, 해당 태스크는 알림 댓글과 함께 자동으로 완료 됩니다. 

commit 시 fix이외에도 다음과 같은 단어를 사용하면 자동 댓글, 완료 처리가 활성화됩니다. 
- fix, fixes, fixed
- close, closes, closed
- resolve, resolves, resolved
- 해결, 완료 

#### Azure DevOps 프로젝트 업무에 연동하기 

Bot 연동 URL을 복사하였으면, 연동하고자 하는 서비스에 웹 훅을 걸어야 합니다. Azure DevOps의 설정 페이지로 이동합니다. service hooks 메뉴를 눌러 웹 훅을 추가합니다.
![연동](http://static.toastoven.net/prod_dooray_project/Project_01_ko.png)
<center>[그림] Azure DevOps 설정</center>

Payload URL에 복사한 Dooray hook 연동 URL을 입력 후 저장합니다.
![연동](http://static.toastoven.net/prod_dooray_project/Project_02_ko.png)
<center>[그림] 웹 훅 추가</center>

test를 통해 훅이 오는지 확인 후 finish를 선택해 주세요.  
commit을 push할 때 message에 "fix #my-dooray-project/1234" 라는 문구를 입력하면 my-dooray-project 프로젝트의 1234번 업무에 push 알림이 댓글로 등록됩니다. 만약 pull request를 올려 merge될 경우, 해당 태스크는 알림 댓글과 함께 자동으로 완료 됩니다. 

commit 시 fix이외에도 다음과 같은 단어를 사용하면 자동 댓글, 완료 처리가 활성화됩니다. 
- fix, fixes, fixed
- close, closes, closed
- resolve, resolves, resolved
- 해결, 완료 
