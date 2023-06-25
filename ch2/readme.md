# ch2 서울시 청소년 정신건강 분석

## 0. 데이터 출처

- https://data.seoul.go.kr/dataList/10956/S/2/datasetView.do

## 1. 파이썬에서 모듈 import

만약 exam_module이라는 모듈을 import하려고 하면,

```
import exam_module
```

이라고 하면 된다. 이때, exam_module의 hellow_world라는 함수를 사용하려면

```
exam_module.hello_world()
```

라고 호출하면 된다. 만약 이름이 너무 길거나, 대표적으로 통용되는 이름이 있다면 as 명령으로 수정하면 된다.

```
import exam_module as em
```

이라고 하면, exam_module 모듈을 em이라는 이름으로 import 하겠다는 뜻이다. 이제 hello_world라는 함수를 사용할 때는

```
em.hello_world()
```

이라고 호출하면 된다.  
만약 exam_moduyle에 있는 hello_world 함수만 따로 import 하고 싶으면

```
from exam_module import hello_world
```

라고 하고, 사용할 때는

```
hello_world()
```

라고 하면 된다.  
결국, ch2_teenage_mental.ipynb의 In [1]에 있는 코드는 pd라는 이름으로 pandas 를 import 하겠다는 뜻이다.

## 2. pandas DataFrame 구조

- https://pandas.pydata.org/docs/user_guide/10min.html  
  위 링크는 pandas 공식 홈페이지에 나와있는 튜토리얼이다.
