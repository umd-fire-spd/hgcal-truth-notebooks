# HGCAL truth tutorial notebooks

additonal info for SPD students:
--------------------------------
needs 3.7+
--------------------------------
This repo requires python 3.

First setup a virtual environment:

```
python3 -m venv myhgcalenv
source myhgcalenv/bin/activate
```

Then install a few packages:

```
pip install devhgcaltruth
pip install notebook
pip install plotly
```

Clone this repository:

```
git clone https://github.com/tklijnsma/hgcal-truth-notebooks.git
cd hgcal-truth-notebooks
```

Download the data:

```
wget https://cernbox.cern.ch/index.php/s/lYNghQUwb4htXhL/download -O hgcalntups.tar
mkdir ntups
tar xvf hgcalntups.tar -C ntups/
rm hgcalntups.tar
```

And run a jupyter notebook:

```
jupyter-notebook
```
