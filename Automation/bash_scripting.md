# Bash scripting

- Automate repetitive tasks 
- Bash scripts execute within a Bash shell interpreter terminal
- Set of commands using frequently


## How

- [cheat sheet](./resouces/bash_scripting.pdf)

### Variables

- Variables in a bash script are set using the `=` sign and accessed using `$`.
- exp:
  - `greeting="Hello"`
  - `echo $greeting`
  
### Conditionals
  
- ```
    if [ $index -lt 5 ]
    then
        echo $index
    else
        echo 5
    fi
  ```

#### 1. Compare numbers

- Equal: `-eq`
- Not equal: `-ne`
- Less than or equal: `-le`
- Less than: `-lt`
- Greater than or equal: `-ge`
- Greater than: `-gt`
- Is null: `-z`

#### 2. Compare string

- Equal: `==`
- Not equal: `!=`

- best practice to put the variable into quotes (")

- ```
  if [ "$foo" == "$bar" ] 
  ```


### Loops

- There are 3 different ways to loop within a bash script: `for`, `while` and `until`.

- `for`
  - ```
    for word in $paragraph
    do
      echo $word
    done
    ```

- `while`
  - ```
    while [ $index -lt 5 ]
    do
      echo $index
      index=$((index + 1))
    done
    ```

- `until`
  - ```
    until [ $index -eq 5 ]
    do
      echo $index
      index=$((index + 1))
    done
    ```

### Inputs

1. **Prompting** the user for input
- ```
    echo "Guess a number"
    read number
    echo "You guessed $number"
  ```

2. **Arguments**
- ```
    saycolors red green blue
  ```
- ```
    for color in "$@"
    do
      echo $color
    done
  ```

- Access by `$1`, `$2`, ...

3. **Read external files**

- ```
    files=/some/directory/*
  ```

- ```
    for file in $files
    do
      echo $file
    done
  ```
