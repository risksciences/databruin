Select the correct branch for your operating system.

```sh
conda activate base && yes y | conda remove --name databruin --all && yes y | conda create --name databruin python=3.10 && conda activate databruin && yes y | conda install pip && yes y | pip install -r https://raw.githubusercontent.com/risksciences/databruin/macos-arm64/requirements.txt
```
