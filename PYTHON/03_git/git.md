# git 이란...?
> 분산 버전 관리 시스템

```python 
# gitlab << ssafy에서 공부한 내용 저장
# github << 개인공부할때 사용
```

# git 초기화
```python
# git init <<< (깃이 들어간다 생성한다 라는 의미.)
```

# Commit 
```python
''버전'' 변경된 파일들을 저장하는 행위이며, 마치 사진을 찍듯이 기록한다 하여 'snap shot' 이라고도 함.
```

### 상태 확인 명령어
```python
# git status >> 상태확인
```

### staging aread에 추가
```python
# git add {path}<folder_name>/{file_name}
```

### Repository에 저장하기
```python
# git commit -m "commit message" <띄워쓰기 유의해서 "" 쓸것>
```
# 
# git 기초 설정

### 주어진 정보대로 작성 (1회성)
```python
# git config --global user.email "xxx@xxx"
# git config --global user.name "name.name"
```

### 등록한 정보 확인
```python
# git config --global --list
```


* 꿀팁 - 터미널에서 우클릭은 복사이다. 
* 꿀팁 - Shift + Ins = 붙여넣기이다.

### 커밋 기록 확인하기
```python
# git log
```
### 직전 커밋 이름 수정
```python
# git commit --amend // vi or vim 이라고 부른다 (메모장)
# :wq >> (write and quit)
# :q >> quit
``` 

### Repository의 구분
```python
local repository = 로컬저장소 > 1개이다.
remote repository = 원격저장소 > github 
    개인용 : github
    싸피용 : gitlab
    git을 지원하는 것이다. git은 아니다.

```

### git 설정 초기화

```python

1번

# git config --global --list
# vim (고급 메모장)을 활용해서 설정 제거하기
# vim git 설정 파일 열기
 = vim ~/.gitconfig
 # : wq (write and quit)

2번
``
 code ~/.gitconfig
```

# git 커밋이 많을 때...
```
 git log --oneline

```


# git push origin 을 하면 github에 넣는당.