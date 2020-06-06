## install problems

* conda screws with system paths and replaces python
* conda installs outdated versions
* conda version of tensorflow broken
  * mac lib error
  * mac clash with system/brew openmp implementation
* pip required to install tensorflow from source
* tensorflow openblas & mkl version are slow, native acceleration fw should be used


```bash
conda create --name tf2 python=3.7
conda install nomkl jupyter numpy pandas matplotlib graphviz pydot
pip install tensorflow
```
