# FerrumLink 📨
## Rust TCP Chat System 🦀💬

### Server 🖧
A simple, asynchronous TCP-based chat server built using Rust, Tokio, and SQLite for user account management.

### Terminal Client 🖳 
A simple TCP stream forwarder for the cli. To communicate with the server

### Web Client 🖥️
A web based client in yew.rs

## Features ✨

- [x] User registration and login 🔐
- [x] Broadcasting messages to all connected users 📡
- [x] List of all users with their online/offline status 👥
- [x] Colorful terminal output with Colored and PrettyTable crates 🌈
- [x] Asynchronous I/O with Tokio ⚡️

## Prerequisites 📚

- Rust (stable) and Cargo 🦀 </br>
- SQLite 🗄️

## Getting Started 🚀

### Starting the server ⏫

To start the server download FerrumServe from the release page

``` bash

$ ~/ferrum-serve 127.0.0.1:6142
```

### Connecting with the server 🎮

To connect to the chat server, you can download FerrumLinker from the release page

``` bash

$ ~/ferrum-linker 127.0.0.1:6142
```

After connecting, you will be prompted to either register a new user or log in with an existing user account. Once logged in, you can start sending messages to all connected users.
Commands

/listusers: List all registered users with their online/offline status 👥.
/whisper: Private Messenging to a specified user. Usage: /whisper [username] [message]
</br>

## Building

``` bash

$ git clone https://github.com/FerrumLink/FerrumServe.git
$ cd ferrum-serve
```

#### Build the project

``` bash

$ cargo build --release
```

#### Running the server

By default, the server will listen on 127.0.0.1:6142. You can provide an optional IP address and port as a command-line argument.

``` bash

$ ./target/release/ferrum-serve [IP:PORT]
```


## 📝 License

Copyright © 2023 [Simon Guglberger](https://github.com/sxmon17) and [Aleksa Nikolic](https://github.com/aaaleks07).</br>
</br>

