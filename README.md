# GoShell 🐚

![Completed](https://img.shields.io/badge/status-Completed-brightgreen)
![Go Version](https://img.shields.io/github/go-mod/go-version/hmdfrds/go-shell)
![License](https://img.shields.io/github/license/hmdfrds/go-shell)

Just a super basic **command-line shell**🖥️⚙️ written in Go. Cmd/shell wannabe.  

## Description 📄  

I Just started learning GO. So I decide to GO to build something with GO.

## Features ✨

- **Command Prompt**  
  Type stuff, hit `Enter`, and get responses.

- **Custom Commands**  
  Easily register and execute built-in commands like `cd`, `ls`, `echo`, and more.

- **Run External Commands**  
  Run commands that available in the system. Got it from `%PATH%`.

- **Pipe Stuff**  
  Send output from another command to another. This thing `|`.

- **Redirection**  
  Send output to file. Something like `echo "hi" > text.txt`.

- **History**  
  History with `↑` and `↓` key.

- **Tab Auto Completion**  
  Click `tab` will auto complete the directory name that exist in **working directory**.

## Getting Started 🚀

### Prerequisites

- You need **Go**. Just Go here [Go Install doc](https://go.dev/doc/install).
- I write this in **Go 1.23.2**. I think **Go 1.23+** should be okay.
- A Unix-based terminal (Windows with WSL works too).

### Installation

#### Clone the repository

```bash
git clone https://github.com/hmdfrds/go-shell.git
cd go-shell
go run .
```  

#### Build the binarry

```bash
go build -o goshell main.go
```

#### Run the shell  

```bash
./goshell
```

## Usage 📖  

Here's a quick overview of what you can do:  

| Command     | Description                         | Example                |
| :---------- | :---------------------------------- | :--------------------- |
| `cd`        | Change the current directory        | `cd /path/to/dir`      |
| `pwd`       | Print the current working directory | `pwd`                  |
| `ls`        | List files in the current directory | `ls -a`                |
| `echo`      | List files in the current directory | `echo Hello, GoShell!` |
| Redirection | Redirect output to files            | `ls > files.txt`       |
| Piping      | Pass output between commands        | `ls \| echo`           |

To exit just type:  

```bash
exit
```

## Limitations 🚧

This project was built as a learning exercise, and as such:

- There no text navigation around the input with `←` and `→`. Sad.

## Test 🧪

Ensure everything is working correctly by running tests:  

```bash
go test ./... -v
```

## Project Status 🚦

**Mission Accomplished**: This project has graduated, moved out of the "learning phase," and is living its best life. I hope so. I already implement most of the core features.

## Author 👨‍💻  

Created as a personal side project to learn Golang and improve my skills.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for the detail.  
