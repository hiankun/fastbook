[Sat 24 Sep 2022]

Installation:

* Install PyTorch first via 
  ```
  mamba install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
  ```
* Then install fastai `pip install -U fastai fastbook ipywidgets`
* `mamba install jupyterlab -c conda-forge`
* `pip install nbdev` for viewing source.

---
The following steps will fail:

* `mamba create -n fastai_env`
* `mamba install -c fastchan fastai`
  * Cannot import `torchvision` due to cuda problem.
