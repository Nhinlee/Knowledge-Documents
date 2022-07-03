# The Command Line

## What is the Command Line?
- The command line is a text interface for the computer’s operating system.
- Traverse, edit computer’s filesystem.

## What is Bash?
- **Bash**, or the Bourne-Again SHell, is a **CLI** that was created in 1989 by Brian Fox as a free software replacement for the Bourne Shell.
- Open source.

## Navigating The File System
[cheat sheet](./nav_file_system.pdf)

## View & Changing The File System
[cheat sheet](./view_changing_file_system.pdf)

## Redirecting The Input & Output
[cheat sheet](./redirecting_input_output.pdf)

## Configuring the Environment
[cheat sheet](./config_env.pdf)

### PATH
- **PATH** is an environment variable that stores a list of directories separated by a colon.
- The **PATH** variable simply lists which directories contain **scripts**.

### env
- The **env** command stands for “environment,” and returns a list of the environment variables for the current user.
- exam:
  - env | grep PATH


## Windows Command Line

### **Bash to Windows Command Prompt Translation Guide**

### **Navigation**
| Action                  | Mac/Linux Command | Windows Command                |
|-------------------------|-------------------|--------------------------------|
| List files/directories  | ls                | dir                            |
| Print working directory | pwd               | chdir                          |
| Change directory        | cd                | cd                             |
| Create new directory    | mkdir             | md                             |
| Create new file         | touch             | echo "hello world" > hello.txt |
| Clear screen            | clear             | cls                            |

### **Manipulation**
| Action                              | Mac/Linux Command | Windows Command |
|-------------------------------------|-------------------|-----------------|
| View contents of an individual file | cat               | type            |
| Copy file or directory              | cp                | copy            |
| Move files (without making copy)    | mv                | ren             |
| Delete files or directories         | rm                | del             |

### **Redirection**
| Action                              | Mac/Linux Command | Windows Command |
|-------------------------------------|-------------------|-----------------|
| View contents of an individual file | cat               | type            |
| Copy file or directory              | cp                | copy            |
| Action                              | Mac/Linux Command | Windows Command |
| Redirect output                     | >                 | >               |
| Pipe, or transfer, output           | |                 | |               |
| Append output to another file       | >>                | >>              |
| Search files for a pattern match    | grep              | find            |

### **Environment**
| Action                         | Mac/Linux Command | Windows Command                          |
|--------------------------------|-------------------|------------------------------------------|
| View all environment variables | env               | set                                      |
| Set an environment variable    | export VAR=value  | setx variable value (administrator mode) |
| Print specific variable        | echo $VAR         | echo %VAR%                               |
