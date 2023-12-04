--깃실행후 깃상태확인
pwd ->작업폴더확인
ls-al ->현재 작업폴더에 있는 모든 파일과 디렉토리에 대한 자세한 정보를 제시

--작업디렉토리의 정보확인(앞에 git이 붙지 않는다)
git --version ->버전확인
git config --list ->설정확인
git --help ->도움

--깃 실행 이후 필수 코드들
git config --global user.name rladydwns2371      ---->사용자이름 설정
git config --global user.email gimyongjun796@gmail.com     --->사용자 메일 설정
git config --global core.autocrlf true       --->줄바꿈자동 변환
git config --global core.safecrlf false        --->줄바꿈 안전 설정
git config --global core.editor 'code-wait'    --->기본편집기 설정
git config --global init defaultBranch main     --->기본브랜치이름을 메인으로 설정하고 예전에는 master을 주로 썻지만 요즘에는 main을 주로 쓴다.

--저장소 생성 코드
git init <저장소이름>  ->저장소 생성
cd <저장소이름>  ->폴더 이동 (위 폴더 밑에서 작업)


--파일 생성코드
echo (파일에 들어갈 문장) 파일이름.txt
cat hello.txt
(파일에 들어가 있는 문장)

git status --long   -->현재상태표시
git status --short   -->파일 상대를 간단히 표시 (=git status -s)

git add <파일이름>.txt ...
git status --long

git rm --catched hello.txt
