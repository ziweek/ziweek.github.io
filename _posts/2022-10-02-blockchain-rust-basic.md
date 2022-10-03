---
layout: post
title:  "Rust Basic"
date:   2022-10-01 19:41:36 +0530
categories: Blockchain Rust
---

Rust is a relatively new language that focuses on high performance and safety. It is so appealing to scientists who want to perform heavy data analysis. In that sense, Rust is suitable for the process that should never be slow and unstable. For example, the process can be blockchain tech, operating system and machine learning.

<br/>
<br/>

## Installation
You can install Rust using below code in 2022.10.04. However, I think it is better to check [Rust's Official Documentation](https://www.rust-lang.org/) before just trying that.
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
If you ran that code, then you can run into several options like below. It is recommended to pick first one (the default). 
```
1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
> 1
```
If Rust is installed normally, then you can check it using the below code.
```
rustc -V
```
  
<br/>
<br/>
      
## Starting New Project
To start Rust project, you need to run below 
```
$ cargo new [YourProject]
```
If you ran the code, then you can run into below options. It is recommended to pick option #1 (the default). 

<br/>
<br/>

## Variable Declaration
```rust
let a = 1;
let mut b = 2;
```
snake_case


