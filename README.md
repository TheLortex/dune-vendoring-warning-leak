# dune-vendoring-warning-leak

With dune version 3.4.0:
```
$ git clone https://github.com/TheLortex/dune-vendoring-warning-leak
$ dune build
File "vendor/a/vendor/b/src/b.ml", line 1, characters 6-16:
1 | let b unused_var = ()
          ^^^^^^^^^^
Error (warning 27 [unused-var-strict]): unused variable unused_var.
```
