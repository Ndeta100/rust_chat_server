# creating a simple chat server with rust using async from the tokio lib

 run `cargo new chat_server` to create project file

 Add tokio to your cargo toml file `tokio = { version = "1", features = ["full"] }` 

 you might encounter a Macro error here is a hint to fix it `frame-support = { version = "2.0.0" }`
 And use `use frame_support::decl_storage;`
