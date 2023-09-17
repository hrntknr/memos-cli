# memos-cli
> Simple [memos](https://github.com/usememos/memos) cli client described in bash

## Dependencies
- [curl](https://curl.se/)
- [jq](https://stedolan.github.io/jq/)
- Either one is required.
  - [fzf](https://github.com/junegunn/fzf)
  - [peco](https://github.com/peco/peco)

## Installation
```sh
wget https://raw.githubusercontent.com/hrntknr/memos-cli/main/memo -O /usr/local/bin/memo
chmod +x /usr/local/bin/memo
```

## Usage
```
Usage: memo <subcommand> [<options>]
Subcommands:
  login           Login to the server
  list            List memos
  list_archived   List archived memos
  archive         Archive a memo
  archive <id>    Archive a memo with id
  unarchive       Unarchive a memo
  unarchive <id>  Unarchive a memo with id
  delete          Delete a memo
  delete <id>     Delete a memo with id
  show            Show a memo
  show <id>       Show a memo with id
  edit            Edit a memo
  edit <id>       Edit a memo with id (pipe or redirect supported)
  new             Create a new memo (pipe or redirect supported)
```
