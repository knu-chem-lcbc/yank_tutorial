# yank_tutorial
## 0. [Yank][http://getyank.org/latest/]는 [openmm MD 패키지][http://openmm.org/]를 이용해서 **absolute binding free energy** 계산을 쉽게 수행할 수 있도록 해주는 패키지이다. 
## 1. Yank의 설치
conda를 이용해서 쉽게 설치할 수 있다.
다른 패키지와의 충돌을 피하기 위해서 가상환경을 생성하여 설치하는 것을 추천한다. 
    
    conda create -n yank_env python 
    conda config --add channels omnia --add channels conda-forge
    conda install yank  
  
