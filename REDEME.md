[뒤로](README02.md)

# Git 버전관리

* vscode 기본쉘 Git Bash로 설정하기
  - 명령어 팔레트(F1 or ctrl + shift + p) -> select default profile(터미널기본프로필) -> Git Bash선택   
     
        
## 초기환경설정
git을 사용하려면 사용자이름, 이메일 설정, 기본에디터 설정이 필요하다.

1. CLI   
    - git config --global user.name 사용자이름   
    - git config --global user.email 사용자이메일   
    - git config --global core.editor "code --wait" [기본에디터 vscode등록]  
    - git config --list [등록한 옵션들 확인]    

1. GUI
    - git config --global -e [git 글로벌 설정판 open]
    - code 파일명을 입력하면 파일을 열수 있다
    - code 명령을 사용하기 위해 명령파레트 -> code 입력 -> 셀명령:PATH에 'code'명령 설치

## 버전관리
[CLI]   

    1. git --version (Git 버전확인)   
    2. mkdir folder name (폴더생성)
    3. cd folder name (change directory 디렉토리 이동)
    4. git init (Git 초기화)
    5. echo "# Git 버전관리" > README.md (혹은) touch README.md(README.md파일 생성)
    6. cat README.md (파일생성 및 내용확인)
    7. git status (Git 상태확인 - 브랜치, 커밋여부, 생성파일 추적여부)
    8. git add README.md (생성파일 스테이징)
    9. git commit -m "커밋내용" (생성파일 커밋)


[GUI]

    1. 폴더생성
    2. 에디터에서 폴더열기
    3. 소스제어 -> 리포지토리 초기화
    4. 탐색기 -> 새파일생성(README.md)
    5. 내용입력 후 저장
    6. 파일상태 U (추적하지 않는 상태)


