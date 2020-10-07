# yank_tutorial
## 0. Overview 
[Yank](http://getyank.org/latest/)는 [openmm MD 패키지](http://openmm.org/)를 이용해서 **absolute binding free energy** 계산을 쉽게 수행할 수 있도록 해주는 패키지이다. 
### 0.1. 장점


## 1. Yank의 설치
conda를 이용해서 쉽게 설치할 수 있다.
다른 패키지와의 충돌을 피하기 위해서 가상환경을 생성하여 설치하는 것을 추천한다. 
    
    conda create -n yank_env python 
    conda config --add channels omnia --add channels conda-forge
    conda install yank  
    
설치가 끝난후 가상환경을 activate 한 후에 해당 가상환경에서 yank를 실행시킨다. 
 
    conda activate yank_env
    
어떤 위치에 yank가 설치되었는지 확인한 후에 해당 binary를 사용한다. 

    which yank
    
****
* misc
> For Linux 64, Open MPI is built with CUDA awareness but this support is disabled by default.
To enable it, please set the environmental variable OMPI_MCA_opal_cuda_support=true before
launching your MPI processes. Equivalently, you can set the MCA parameter in the command line:
mpiexec --mca opal_cuda_support 1 ...
