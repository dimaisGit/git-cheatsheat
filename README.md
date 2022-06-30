# Config

## Command

```
git config
```

### Properties

#### Config level

```
git config  --[system/global/local]
```

#### Open config in default editor

```
git config --local -e
```

#### Show full help for the command

```
git config --help
```

#### Show short help for the command

```
git config --h
```

### Variables

#### User info

```
git config --local user.[name/email] "value"
```

#### Default editor for git

```
git config --local core.editor "code --wait" //for VSCode
```

#### Symbol for end of line

```
git config --local core.autocrlf [true/input]
// true is for windows
// input is for Max/Linux
```

# Commands

## Init repository

```
git init
```

## Stage file[s]

```
git add file1 file2 ...
```

## Current status

```
git status
```
