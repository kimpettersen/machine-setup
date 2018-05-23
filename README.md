# Tools to install on a new machine

# Parse json in command line - JQ
`brew install jq`

Attempt to map invalid json *rc: `alias jqq='jq -Rr ". as \$line | try fromjson catch \$line"'` 
