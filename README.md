# KG-ML-Study

### 사전 준비하기
- homebrew 설치
  - https://brew.sh/index_ko.html
  
- Python 설치 
~~~  
  버전 확인 : python -V
  2버전 or 미설치 시 
    brew install python3
  python3 alias 설정
    vi ~/.bash 
    alias python=“python3" 
    source ~/.bash_profile
  version 확인
~~~

- Anaconda / Jupyter notebook 설치 
  - http://jupyter.readthedocs.io/en/latest/install.html
  - https://www.anaconda.com/download/
  - 버전 확인 : conda -V

### GitHub 연동하기
- git clone (원격 저장소 -> 로컬 저장소로 복사)
  - 로컬 저장 위치로 이동 git clone https://github.com/james-jjj/KG-ML-Study.git
- 초기 설정 진행
  - pip install -r requirements.txt
- 본인 폴더 생성 및 테스트 코드 작성
  - KG-ML-Study/james/HelloWorld.ipynb 참고
- git 업로드 
  - add
    - git add *
  - commit
    - git commit -m "커밋 내용을 입력"
  - push
    - git push origin master
    - 저장소 찾지 못할 경우 : git remote add origin https://github.com/james-jjj/KG-ML-Study.git
    - 최초 1회 github ID / password 입력
- github.com/james-jjj/KG-ML-Study 접속 후 정상 커밋 확인
---

#### 참고1. TensorFlow Machine Learning Cookbook
- https://github.com/nfmcclure/tensorflow_cookbook
- http://acornpub.co.kr/book/tensor-machine-learning-cook

#### 참고2. git - 간편 안내서
- https://rogerdudler.github.io/git-guide/index.ko.html

#### 참고3. Simplicity and power in a beautiful Git GUI
- https://www.sourcetreeapp.com/

