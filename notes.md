# Common Lisp

## Requirment 

- `sbcl`: Steel Bank Common Lisp, compiler / REPL. (installed with brew).
- [quicklisp](https://www.quicklisp.org/beta/): library manager. Follow installation steps.
- symlink project in `~/quicklisp/local-projects`

## Doc 

- [Practical Common Lisp](https://gigamonkeys.com/book/lather-rinse-repeat-a-tour-of-the-repl)

## Syntax

```lisp
(describe 'defun)
(load "my_code.fasl") ; load and interpret a file
(compile-file "my_code.lisp") ; compile a file
(load "my_code.fasl") ; load compiled files 
(ql:quickload :mycl) ;compiles and loads
```
