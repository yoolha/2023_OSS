# 2023_OSS
## 2023 OSS 수업 

-----
### 3주차 git

### 이미지
![한국항공대학교 로고](https://user-images.githubusercontent.com/127286924/227757792-5d0145ce-8e22-4bce-8bcf-76654078bb18.png) "한국항공대학교 로고")

### 링크   
[LMS](https://lms.kau.ac.kr "항공대학교 강의관리시스템")

#### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2 "git 문서, 한국어")

##### 주요 git 명령어
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
    * 예) git add <file name>
* commit
* git reset HEAD <file> : stage된 파일을 unstaged로 변경
* git checkout -- <file> : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림 
* branch
* merge
* status
* log
    * 예) git log --oneline --decorate --graph --all
    
------
### 2주차 숙제

```bash
#!/bin/bash

path=$(find /home/kau2/ -name "w2_homework.txt" 2> /dev/null)
last=$(tail -n 1 $path)
line=$(cat $path | wc -l)

echo "----------"
echo "name : "
echo "윤서진"
echo " "
echo "----------"
echo "student id :"
echo "2022125036"
echo "----------"
echo " "
echo "file path : "
echo "$path"
echo " "
echo "----------"
echo "line number : "
echo "$line"
echo " "
echo "----------"
echo "last line : "
echo "$last"
echo " "

```
## 마크다운
### 목록
#### 번호 있는 목록 : 내림차순 정렬
1. 첫번째
3. 세번째
2. 두번째
#### 번호 없는 목록 : *, -, +
* 첫번째
- 세번째
+ 두번째
-----
* 빨강
  * 녹색
    * 파랑
### 강조
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~    
