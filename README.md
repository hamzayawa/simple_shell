[![MIT license](https://img.shields.io/github/license/bhalut/Tropical-Puzzle.svg)](https://github.com/hamzayawa/simple_shell/blob/master/LICENSE)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)


![alt text](//s2.studylib.net/store/data/025893912_1-e26f616a2aee533fff3b9e292fd66a35.png-210x147.png)

 <p align="center">
  <br>
  <a href="https://github.com/hamzayawa/simple_shell/issues">
    <img src="https://img.shields.io/github/stars/hamzayawa/simple_shell?color=333&style=for-the-badge&logo=github" alt="hamzayawa/simple_shell issues"/>
  </a>
    <a href="https://github.com/hamzayawa/simple_shell/pulls">
    <img src="https://img.shields.io/github/commit-activity/m/hamzayawa/simple_shell?color=blue&style=for-the-badge&logo=github" alt="hamzayawa/simple_shell pull requests"/>
  </a>
  <a href="https://github.com/hamzayawa/simple_shell/pulls">
    <img src="https://img.shields.io/github/last-commit/hamzayawa/simple_shell?color=blue&style=for-the-badge&logo=github" alt="hamzayawa/simple_shell requests"/>
  </a>

</p>

# 0x16. C - Simple Shell
Write a simple UNIX command interpreter.

## Description
In this project, we build a custom, straightforward UNIX command interpreter. The program's output and error output must be identical to those of sh (/bin/sh). The only distinction is that your program name must be the same as your argv[0] when you print an error.


Usage
-----

Shellby tokenizes commands after receiving them into words using the delimiter " ". All subsequent words are viewed as arguments to the command that is implied by the first word. Following that, Shellby does the following:


* If the first character of the command is neither a slash (\) nor dot (.), the shell searches for it in the list of shell builtins. If there exists a builtin by that name, the builtin is invoked.
* If the first character of the command is none of a slash (\), dot (.), nor builtin, shellby searches each element of the PATH environmental variable for a directory containing an executable file by that name.
* If the first character of the command is a slash (\) or dot (.) or either of the above searches was successful, the shell executes the named program with any remaining given arguments in a separate execution environment.



## Authors :copyright:

:zap: **Bernice Akua Cobbinah** - [![Github URL](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnaliceBernice)</br>
:zap: **Hamza Abdullahi** - [![Github URL](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hamzayawa)

LICENSE :lock:
-------
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details!

## Acknowledgements :pray:

**Shellby** mimics the fundamental features of the **sh** shell.
This README is based on the Linux man pages for [sh(1)] and [dash(1)] (https://linux.die.net/man/1/sh and https://linux.die.net/man/1/dash, respectively).


This peer learning task was created as a requirement for ALX Africa curriculum.
An online full-stack software engineering project-based peer learning to get students ready for careers in the tech sector.
