<h1 align="center">
	🚀 Minishell
</h1>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/JBVer/Minishell?color=lightblue" />
	<img alt="Number of lines of code" src="https://tokei.rs/b1/github/JBVer/Minishell?category=code" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/JBVer/Minishell?color=yellow" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/JBVer/Minishell?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/JBVer/Minishell?color=green" />
</p>

## 💡 About the project
* Minishell is the fruit of a collaboration between two students at the School 42 in Paris. In this project, we aimed to create a simple shell, which provided us with valuable hands-on experience in processes and file descriptors. Our task involved building a fully functional shell with features such as prompt display, command history, redirections, and pipes. We also learned how to interpret environment variables and implement built-in commands.

## 🧮 Skills
* Rigor
* Unix
* Imperative programming

## 🔌 Built-ins Implemented
* `echo`: Supports the `-n` option.
* `cd`: Allows for changing the current working directory using relative or absolute paths.
* `pwd`: Displays the current working directory.
* `export`: Manages environment variables without any options.
* `unset`: Removes environment variables without any options.
* `env`: Displays the environment variables or arguments.
* `exit`: Exits the shell without any options.

## 📝 Features

- ``CTRL-C``
- ``CTRL-\``
- ``CTRL-D``
- ``|`` pipes
- ``;`` semicolons
- ``>`` ``>>`` ``<`` ``<<`` redirections
- ``&&`` ``||`` operators
- ``*`` wildcard
- local variable
- env expansions + ``$?``

## ⚙️ Usage

```shell
# Within Project dir; Compile
make

# Launch the shell
./minishell
```
