# Tiny latex table generator

Generates tables of a given dimension that can be copy pased into latex editor.

## Installation
```bash
git clone https://github.com/justbobber/tex_tools.git
cd tex_tools
./install.sh
```
make sure <code>~./local/bin/</code> is in your PATH:
```bash
 echo $PATH | grep ".local/bin"
```
if not add it:
```bash
export PATH="$HOME/.local/bin:$PATH"
```

## Usage
```bash
latex_table --dim 5 5  # or what dimensions (row column) the table are to have. 
```
