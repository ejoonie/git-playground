# git-playground
git 연습공간입니다. 

## 명령어들
```
git commit
git push  
--  
git fetch
git pull  
--  
git diff  
--  
git branch
git checkout -b
git checkout  
--  
git reset —hard
git stash
git stash apply  
--  
git tag 1.0.0
git push 1.0.0  
```

## 살다보니 자주사용하는 명령어
```
git branch  
git branch -d xxx  
git tag xxx
git checkout -b xxxx
git checkout xxxx
git push xxx
git log
git add filename
git status
git reset
git stash
git diff 
```

## intellij (혹은 다른 툴) 를 적극 활용하자 


## 실습
1. 기능을 쪼개는 연습 (issue 만들기 습관화)
1. branch 따는 연습 - issue 와 매칭 
1. pull request 습관화
1. 코드 리뷰 습관화 

## 실습 시나리오
```
기능 add, subtract, multiply, divide 함수를 각자 만들고 통합해본다. 
```


### 코드의 추적성 - 공자왈맹자왈  
https://m.blog.naver.com/PostView.nhn?blogId=suresofttech&logNo=220719891642&proxyReferer=https%3A%2F%2Fwww.google.com%2F

### 기술부채  
https://brunch.co.kr/@leehosung/2

### 경험담  
버그가 없는 것이 개발 속도를 높이는 지름길  
버그가 있어도 추적가능해야 함 (장애대응시간을 줄여서 개발에 집중)  
잘, 열심히 가지고는 버그를 잡을 수 없음 ‘어떻게’ 가 중요  

그럼 다른 사람들은 ‘어떻게’ 하고 있나 (추적성 측면에서)  
예제) OHIF Viewer  
버그  
https://github.com/OHIF/Viewers/issues?q=is%3Aissue+is%3Aclosed  
https://github.com/OHIF/Viewers/issues/1147  
https://github.com/OHIF/Viewers/pull/1148  

기능  
https://github.com/OHIF/Viewers/issues?q=is%3Aissue+is%3Aclosed+label%3A%22Story+%3Araised_hands%3A%22  
https://github.com/OHIF/Viewers/issues/985  
https://github.com/OHIF/Viewers/pull/1011  
https://github.com/OHIF/Viewers/pull/1011/files  


