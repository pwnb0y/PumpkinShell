# Batch Scripting Cheatsheet

## Introduction
---

Batch scripting is a way to automate tasks and operations in the Windows operating system using the Command Prompt. Batch scripts are written in a script file using a series of commands, and are executed by running the script file from the Command Prompt. Batch scripts can perform a wide range of tasks, including copying and moving files, running programs, displaying messages, and more. Batch scripting is an efficient and flexible way to automate repetitive or time-consuming tasks, and can be used to perform complex operations with just a few lines of code.

---

## Basics Batch Script Command.

---

> 1. **Echo**: The echo command is used to display messages or the contents of a variable on the screen. You can use echo to display messages to the user or to debug a batch script.

> **Syntax**

```
echo [message]
```
---
---

> 2. **Set**:  The **set** command is used to assign values to variables in a batch script. Variables are used to store data that can be used later in the script.

> **Syantax**

```
set [variable]=[value]
```

---
---

> 3. **Call**:  The **call** command is used to call another batch script from within a batch script. This allows you to create reusable pieces of code that can be called from multiple places in your script.

> **Syantax**

```
call [file.bat]
```

---
---

> 4. **Goto**:  The **goto** command is used to jump to a specific label in a batch script. Labels are defined using the : character and provide a way to organize the flow of a script.

> **Syantax**

```
goto [label]
```

---
---

> 5. **If**:  The **if** command is used to perform conditional operations in a batch script. The **if** statement allows you to specify a condition, and if the condition is true, a specified command will be executed.

> **Syantax**

```
if [condition] [command]
```

---
---


> 6. **For**:  The **for** command is used to repeat a set of commands a specified number of times. The **for** loop allows you to perform a set of commands for each item in a list or a range of numbers.

> **Syantax**

```
for [variable] in ([start] [step] [end]) do [command]
```

---
---


> 7. **Start**: The **start** command is used to **start** a new process in a new window. This allows you to run multiple commands or programs at the same time.

> **Syantax**

```
start [file]
```

---
---


> 8. **Rem**: The **rem** command is used to add comments to a batch script. Comments are ignored by the command prompt and are used to provide information or documentation for the script.

> **Syantax**

```
rem [comment]
```

---
---


> 9. **Pause**: The **pause** command is used to pause the execution of a batch script and display a message. This allows you to pause the script and wait for the user to press a key before continuing.

> **Syantax**

```
pause
```

---
---


> 10. **Exit**: The **exit** command is used to exit the current batch script or command prompt session. This allows you to terminate the script and return to the command prompt.

> **Syantax**

```
exit
```

---
---


> 11. **CD**: The **cd** command is used to change the current working directory in the command prompt. This allows you to navigate the file system and access different directories from within a batch script.

> **Syantax**

```
cd [directory]
```

---
---


> 12. **Dir**:  The **dir** command is used to list the files and directories in a directory. This allows you to see the contents of a directory and determine the names of files that you need to work with in your script.

> **Syantax**

```
dir
```

---
---


> 13. **Cls**: The **cls** command is used to clear

> **Syantax**

```
cls
```

---
---