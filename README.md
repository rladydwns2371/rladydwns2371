# 깃 실행 후 현재 작업 디렉토리 확인
pwd

# 현재 작업 폴더에 있는 모든 파일과 디렉토리에 대한 자세한 정보 확인
ls -al

# 작업 디렉토리 정보 확인 (git이 붙지 않음)
git --version     # 깃 버전 확인
git config --list # 깃 설정 확인
git --help        # 도움말

# 깃 필수 설정
git config --global user.name rladydwns2371  # 사용자 이름 설정
git config --global user.email gimyongjun796@gmail.com  # 사용자 이메일 설정
git config --global core.autocrlf true       # 줄바꿈 자동 변환
git config --global core.safecrlf false      # 줄바꿈 안전 설정
git config --global core.editor 'code-wait'  # 기본 편집기 설정
git config --global init.defaultBranch main  # 기본 브랜치 이름을 main으로 설정

# 저장소 생성 코드
git init <저장소이름>  # 저장소 생성
cd <저장소이름>        # 저장소로 이동

# 파일 생성 코드
echo "안녕하세요, Git!" > 파일이름.txt     # 파일 생성 및 내용 입력
cat 파일이름.txt      # 파일 내용 확인

# 깃 상태 확인
git status --long     # 현재 상태 자세히 표시
git status --short    # 파일 상태 간단히 표시 (git status -s)

# 파일 추가 및 상태 확인
git add 파일이름.txt  # 파일 추가
git status --long     # 현재 상태 자세히 표시

# 파일 삭제 및 상태 확인
git rm --cached hello.txt  # Staging 영역에서 파일 제거
git status --long          # 현재 상태 자세히 표시
