<h2 align="center">Hi, I'm Jonathan 👋</h2>
<h3 align="left">I graduated double major in Mechanical Engineering and Computer Science from KAIST :kr:.</h3>
<p>I am very keen in robotics and system programming related topics. One of the courses I really liked the most while I was an undergraduate student is about concurrency. </p>
<p>I used to really like C++ as a programming language and is now moving on to Rust as it is more modern and has a built in package manager. </p>

## Open Source Contributions
### [reflect-cpp](https://github.com/getml/reflectcpp)
Reflect CPP is a Moderna C++ Library that allows for pydantic style (i.e. serde style) serialisation in C++. By only declaring structs, one can serialize whole structs into JSON and many more other structures. 

## Hobby Projects
### [jowi-cli](https://github.com/jowillianto/jowi-cli)
Modern C++ modules based CLI Application Library. Batteries included, parses argument and attach actions to arguments made. Use only the `import` keyword without any includes. 
### [test-lib](https://github.com/jowillianto/test-lib)
Modern C++ modules based testing library. Batteries included, perform asserts on `std::expected`, create new tests with macros (sadly this means includes), and add your tests to `CMakeLists.txt` with a function. 
This includes sanitizers, etc..
### [jowi-process](https://github.com/jowillianto/jowi-process)
Modern C++ modules based subprocess spawning, spawn childs with system code and results returned through `std::expected`, no more worrying about any exception being thrown obnoxiously. Since, in this library,
only `std::bad_alloc` will be obnoxiously thrown. 
### [jowi-io](https://github.com/jowillianto/jowi-io)
Moderna C++ modules based library for IO into file descriptors. Most of the functions described here are `noexcept` and results are as usual returned through `std::expected`. This way, no need to worry about obnoxious parsing error thrown during parsing.
### [cpp-module-toolchain](https://github.com/jowillianto/cpp-module-toolchain)
Developing with C++ modules requires the newest of compilers. `cpp-module-toolchain` installs everything in a docker container and allows you to compile for the linux os. 
### [clrust](https://github.com/jowillianto/clrust)
Rust port of `moderna-cli`, uses very similar structures with a few upgrades.

## Stance on Programming
I have currently used a variety of programming languages and can vouch that I have a good command of each one of them. I know C++, Rust, Python, Scala, Typescript and Javascript. If I am going to rank the languages from best to worst in terms of usability, I would rank them as follows: 
Rust, C++, Typescript, Scala, Javascript, Python. I really like how explicit rust is with their error handling. The bane of programming comes from when you use Python, Javascript or Typescript and there is an exception that is thrown by a specific library you are using, this exception
is very implicit and is hidden until you test a specific code paths. Hence, having explicit return codes like `Result` in Rust and `std::expected` in C++ is good when you want to program for long hours. Of course, testing is still needed, however, it is easier to reason about correctness
if errors are not implicitly thrown. Additionally, a lot of developers use exception as a means of flow control, this is also not very good in practice since it is not why exceptions are created for. Exceptions should really be reserved for exceptional cases or non-recoverable errors such as 
when memory cannot be allocated by the OS anymore or argument errors.


## Programming Skills
![](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  

## Languages
- 🇰🇷: kind of fluent
- 🇮🇩: born here haha
- 🇨🇳: spoken from birth, optimistically fluent.
- 🇬🇧: spoken from birth, fluent. 
