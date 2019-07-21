
Something like this:

```
:let g:buftabs_only_basename=1
:let g:buftabs_in_statusline=1
:let g:buftabs_active_highlight_group="Visual"
:let g:buftabs_marker_start = " "
:let g:buftabs_marker_end = " "   
:let g:buftabs_marker_modified = "!"
                                     
noremap <f1> :bprev<CR>
noremap <f2> :bnext<CR>  
```
