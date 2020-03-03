# dotlink-sh

A minimalist dotfiles management tool written in POSIX shell.

## Usage

```
dotlink - A dotfiles management tool

USAGE:
    dotlink [OPTION]...

OPTIONS:
    -s, --source-dir <path>   Sets the source directory (default: current working directory)
    -t, --target-dir <path>   Sets the target directory (default: parent directory of source directory)
    -r, --replace-dot         If a file or directory name begins with 'dot-', it is replaced with '.'
    -a, --absolute-paths      Uses absolute paths for links instead of relative paths
    -f, --force               Removes existing destination files
    -i, --interactive         Prompts whether to remove existing destination files
    -v, --verbose             Prints verbose output
    -h, --help                Prints this help message
```
