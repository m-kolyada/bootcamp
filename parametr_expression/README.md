# Parameter Expansion

- [Parameter Expansion](#parameter-expansion)
  - [${parameter:-word}](#parameter-word)
  - [${parameter:=word}](#parameterword)
  - [${parameter:?word}](#parameterword-1)
  - [${parameter:+word}](#parameterword-2)
  - [${#parameter}](#parameter)

## ${parameter:-word}

If parameter is **unset or null**, use word as the default value.

```bash
 # HACK: 1) ${parameter:-word}

 var=""
 echo ${var:-"default"} # Output: default
 ```
