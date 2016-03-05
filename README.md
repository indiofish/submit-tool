# [Baekjoon Online Judge](http://www.acmicpc.net/) Submit Tool

## Tool 사용법
```shell
python submit.py 파일이름
python submit.py 문제번호 파일이름

```

### 예제
```shell
python submit.py 1920.cpp
python submit.py 1920 1920.cpp
```

#### 추가: 몇몇 언어의 버전 선택 가능
```shell
# python submit.py 파일이름 버전
# python submit.py 문제번호 파일이름 버전
(기본: python2)
python submit.py 1920.py python3
python submit.py 1920.py 3
python submit.py 1920.py pypy

(기본: c++)
python submit.py 1920.cpp 11
python submit.py 1920.cpp cpp11
python submit.py 1920.cpp c++11
```
	
## 주의 사항
- 확장자로 어떤 언어인지 판별합니다.
- 문제번호를 입력하지 않고 제출할 때는  문제번호.확장자 형식이어야 합니다. 예) 1920.cpp, 1000.py

### python을 치기 귀찮다면…

아래와 같이 해도 제출은 됩니다.

	./submit.py 1920 1920.cpp
	
그런데, .py도 치기 귀찮다면

	mv submit.py submit
	./submit 1920 1920.cpp
	
이렇게 하면 됩니다.


