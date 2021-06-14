# Password Generator Python

Password Generator in Python can be used to create secure passwords for length upto 32 characters containing alphabets (UPPERCASE and lowercase), digits, and special characters at random places. 

# Arguments and Usage
## Usage
```
usage: pwdgen.py [-h] [-l] [-n] [-p] [-s | -cs  [...]]
```

## Arguments
### Quick reference table
|Short      |Long                                          |Default                                   |Description
|-----------|----------------------------------------------|------------------------------------------|----------------------------------------
|`-h`       |`--help`                                      |                                          |Show the help message and exit
|`-l`       |`--pwd_length`                                |`16`                                      |Set the length of Generated Password
|`-n`       |`--no_numbers`                                |`False`                                   |Do not use Numbers
|`-p`       |`--print_pwd`                                 |`False`                                   |Prints password to STDOUT
|`-s \| -cs`|`--no_special_chars \| --custom_special_chars`|`False \| <built-in string.punctuation>`  |Do not use Special Characters \| Use Custom Special Characters

### `-h`, `--help`
Show the help message and exit

Usage:
```
>>> pwdgen.py -h
```

### `-l`, `--pwd_length` (Default: `16`)
Set the length of Generated Password

Example:
```
>>> pwdgen.py -l 10
... (Returns password with length '10')
```

### `-n`, `--no_numbers` (Default: `False`)
Do not use Numbers

Example:
```
>>> pwdgen.py -n
... (Returns password with no numbers)
```

### `-p`, `--print_pwd` (Defualt: `False`)
Prints password to STDOUT

Example:
```
>>> pwdgen.py -p
... Generated Password: 9s$9jbn=_8zu]5'B (Prints a verbose statement with password)
```

### `-s \| -cs`, `--no_special_chars \| --custom_special_chars` (Default: `False \| <built-in string.punctuation>`)
Do not use Special Characters \| Use Custom Special Characters

Example:
```
>>> pwdgen.py -s
... (Returns password with no special symbols)
>>> pwdgen.py -cs ! @ #
... (Returns password containing <!, @, #> as special symbols)
```

# Usage License
### [MIT License](https://github.com/itsDV7/Password_Generator_Python/blob/main/MIT-LICENSE.txt)
