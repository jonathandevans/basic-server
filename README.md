# Simple Server

This is a simple multi-threaded TCP server used to send static files implemented in Rust. It is a simple project to learn how to use the Rust programming language. The server is able to handle multiple requests at the same time through the use of threads, however it currently shuts down after a certain number of requests. This is determined by the `REQUESTS` constant in the `main.rs` file.

The static HTML files are stored in the `public` directory.