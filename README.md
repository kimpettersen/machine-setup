# Tools to install on a new machine

# Parse json in command line - JQ
`brew install jq`

Attempt to map invalid json *rc: ```alias jqq='jq -Rr ". as \$line | try fromjson catch \$line"'```


```
// Example:
➜  machine-setup git:(master) echo "{\"a\":2}" | jq
{
  "a": 2
}
```

#Visual Studio Code extensions
- Git History
- Git Lens
- Go
- Org Mode
- Sublime Text Keymap
