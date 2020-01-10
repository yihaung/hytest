# hytest 20200108

도움을 받은 사이트 
git command
1. https://codevkr.tistory.com/46
2. https://devmjun.github.io/archive/git-more-often-command

명령어 : git clone [레포지터리명]  동기화를 수행<BR> 
파일 수정 : vi [해당파일명]  <BR>
파일 확인 : git status <BR>
파일 추가 : git add  [해당파일명] <BR>
파일 삭제 : git rm [해당파일명] <BR>
파일 업로드: git commit -m "start" <BR>
파일 동기화 : git push origin master <BR>
<BR></BR>

<p>--------------------------------------------------</p>

<H5> Github와 EC2 or lambda 와 연동하기. </H5>
ssh key 생성
<p> # ssh-keygen -t rsa -C yourmailaddress </p>
<p> # cd /root/.ssh </p>
해당 파일을 복사한 후에 그 파일을 github에 등록한다. 등록 방법은 계정 > setting 에서 종류별로 등록 가능

<p>--------------------------------------------------</p>

<H5>AWS IAM 권한 설정<br></H5>
 - 해당 모든 권한은 테스트를 위해 full access 권한이지만 보안을 위해 추후 권한 변경 필요.</br>
 - Managed Policy</br>
 - 1. AWSLambdaFullAccess</br>
 - 2. AmazonS3FullAccess</br>
 - 3. AWSLambdaBasicExecutionRole</br>
 <br>
 - 4. awslambdas3move</br>

