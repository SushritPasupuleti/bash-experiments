# Bash Experiments

 Trying out bash scripting


## Setup

```bash
#! /bin/bash

### File Contents
```

Change Permissions

> $ chmod 700 script.txt

### Variables

- Uppercase always

- letters, numbers, underscores

```bash
NAME="Lawliet"
echo "Hi, ${NAME}"
```

### Inputs

```bash
read -p "Enter Choice: " CHOICE
echo "You chose: $CHOICE"
```

### Conditional Statements

```bash
NAME="Lawliet"

if [ "$NAME" == "Lawliet" ]
then
echo "True"
elif [ "$NAME" == "Sushrit" ]
then
echo "Kinda True"
else
echo "False"
fi
```

### Equality Operators

```bash
-lt
-gt
-ge
-le
-e
-ne
-f
-g
```