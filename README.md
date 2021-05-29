## A toy nodejs runtime using rust

This is a toy nodejs runtime which is implemented using rust. The file `main.rs`
contains all of the code. In order to change the code that it runs, change the
function `javascript` in the same file. This function contains the "javascript"
that we run. Beware that any new module would have to be implemented before our
module would recognize them.

### How To Run
* `cargo build`
* `cargo run`

