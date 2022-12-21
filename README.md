# data_processing

Penguin LIN data process repo.

## Usage

### Env Setup

Copy template, use sample group identifiy as folder name

Install poetry

```bash
pip3 install poetry
```

```bash
cd <folder>
# 创建虚拟环境
python3 -m venv ./venv
# 激活虚拟环境
source ./venv/bin/activate
# 安装依赖
poetry lock
poetry install
```

### Run

Set up venv as Jupyter kernel

Close vscode and reopen -> Go to jupyter notebook and select `<folder>/venv/bin/python3`
