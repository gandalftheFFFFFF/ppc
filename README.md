# ppc

A project to generate simple python project templates containing:

- `main.py`
- `requirements.txt`
- `test/`
- `.gitignore`
- `.dockerignore`

# Installation

Download the `ppc` bash script and put it in some directory on your computer.

Add the directory to your PATH variable. Use it in your CLI: `$ ppc project_name`.

# Usage example

```
$ cd dir_with_python_projects>
$ ppc fancy_project
< all kinds of magic >
$ cd fancy_project
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python main.py
```



