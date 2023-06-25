# everyone-python-data-ITPLE

## conda 설정

conda를 설정할때는 다음과 같이 하면 된다.

```
conda env list
# 콘다의 환경 목록을 보여준다.

conda update -n base -c defaults conda
# conda 명령을 업데이트한다.

conda create -n study36 python=3.6
# study36이라는 이름으로 파이썬 3.6 환경을 하나 만든다.

conda activate study36
# study36이라는 이름의 환경을 활성화한다.

pip list
# 파이썬에 설치된 모듈을 확인한다. 여기서는 study36 환경에 있는 파이썬의 모듈들만 보여준다.

python -m pip install -U pip
# pip 명령을 업데이트한다.

pip install jupyter
# jupyter notebook 모듈을 설치한다.

jupyter notebook
# jupyter notebook 실행.

```
