""""""""""""""""""""""""""""
set number
syntax on
colorscheme koehler
set hlsearch
"set ignorecase
"set cindent

"" change leader-string to ,
let mapleader = ","

" using space instead of tab
set tabstop=4
set shiftwidth=4
set expandtab

set nocp    " no compatible
filetype plugin indent on

"""""" taglist
let Tlist_Ctags_Cmd='/usr/bin/ctags'
let Tlist_Show_One_File=1
let Tlist_Exit_OnlyWindow=1
let Tlist_Enable_Fold_Column=0
":map <F4> :TlistToggle <Esc>
:map <Leader>1 :TlistToggle<ESC>

"""""" SingleCompile
"nmap <F9> :SCCompile<cr>:cope<cr> 
"nmap <F10> :SCCompileRun<cr>:SCViewResult<cr><cr>
nmap <Leader>5 :SCCompile<cr>:cope<cr> 
nmap <Leader>6 :SCCompileRun<cr>:SCViewResult<cr><cr>

" set key-mapping
:map <TAB>	:wincmd w<CR>
:map <CR>	<C-]>
:map <BS>	<C-T>

":map <S-LEFT>	:tabp<CR>
":map <S-RIGHT>	:tabn<CR>
":map <F2>	:tabnew .<CR>
:map <Leader>2	:tabp<CR>
:map <Leader>3	:tabn<CR>
:map <Leader>4	:tabnew .<CR>

"" open a shell window
:map <Leader>tt   :ConqueTermSplit bash<CR>
""""""""""""""""""""""""""""
" some testing
":map <Leader>1  ihi,zxj<ESC>
