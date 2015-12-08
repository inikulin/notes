## Syntax highlighing 
```
echo "syntax on" >> ~/.vimrc
```

## Undo/redo
`:u` - undo
`ctrl+r` - redo

## Copy/paste
`y` -copy
`p`- paste
`d` - cut

## Selection 
`V`       - selects entire lines 
`v`       - selects range of text
`ctrl-v`  - selects columns
`gv`      - reselect block

## Indent
Set shift width in space:
```
echo "set sw=4" >> ~/.vimrc
```

Enable auto indent:
```
echo "set autoindent" >> ~/.vimrc

`:>` - indent 
`:<` - unindent

