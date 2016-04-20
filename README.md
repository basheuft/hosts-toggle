# Overview

`hosts-toggle` allows you to easily enable or disable certain rules in your hosts file

# Installation
`go get github.com/101Bas/hosts-toggle`.

# Usage

## Host file

```
# TOGGLE example-project
127.0.0.1 example.com
# END TOGGLE
```

## Command

```
sudo hosts-file -p="example-project"
```

## Result

After first run:

```
# TOGGLE example-project
#127.0.0.1 example.com
# END TOGGLE
```

After second run:

```
# TOGGLE example-project
127.0.0.1 example.com
# END TOGGLE
```
