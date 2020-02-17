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

## Install example

```
$ wget -O ppc https://raw.githubusercontent.com/nielspedersen/ppc/master/ppc
$ mkdir ~/bin
$ mv ppc ~/bin
$ PATH="$HOME/bin:$PATH"
```

You can also add the `PATH` stuff to your `~/.bash_profile` or `~/.bash_rc`:

- Open `.bash_profile` or `.bash_rc`
- Add a new line at the end: `PATH="$HOME/bin:PATH"`
- Save and close the file

The `ppc` command should now be available to from bash:

```
$ ppc
Need 1 argument of new project name
```


# Usage example

```
$ cd <dir_with_python_projects>
$ ppc fancy_project
< all kinds of magic >
$ cd fancy_project
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python main.py
```



