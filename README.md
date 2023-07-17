
# 설치파일
아래 명령을 터미널에 따라 입력하면 된다.

```
python -m venv venv
source venv/Scripts/activate
pip install mkdocs-material
mkdocs new .
mkdocs serve -a localhost:8001
```

# 접속하기

명령으로 실행한 `http://localhost:8001/` 로 접속하면 짠 문서페이지가 등장한다.


# mkdocs.yml 수정

반드시 자신의 정보로 수정해야 한다.

## 개인정보 수정

아래 정보는 반드시 수정해야 한다.  

```
#####################################
# 꼭 fork 후에 변경해야 하는 변수들

# Project information
site_name: 문서타이틀
site_url: https://아이디.github.io/mkdocs/
...

```

## 페이지 구성 정보 수정

페이지트리 구성하기

```

# Page tree
nav:
  - Home: index.md
  - Getting started:
    - Installation: getting-started.md

```
