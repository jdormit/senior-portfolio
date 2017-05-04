# Senior Portfolio
> Jeremy Dormitzer's senior portfolio

## Spark Collaborative Editor
Web app repository: [https://github.com/sparkeditor/webapp]
Server repository: [https://github.com/sparkeditor/backend]

The Spark collaborative editor is a web-based code editor that enables real-time collaboration - multiple users can edit the same file simultaneously, Google-Docs-style. The editor is a static web application written with the Vue.js web framework. The server is written using Node.js. I used the [`Socket.io`](https://socket.io) WebSocket library to handle real-time network communication and the [`Ace`](https://ace.c9.io) embedded code editor to handle the text editing part of the application.

This project helped me understand the concepts and techniques of software design. I designed the whole system from the ground up, implementing a database, an HTTP/WebSocket server, and a standalone web application that communicated over the network. This required not only a solid understanding of networking, but also knowledge of good software engineering principles such as modularity, unit testing, and version control. The Spark project also helped me acquire significant project experience and develop effective problem solving skills.

## Livre eBook Reader
Repository: [https://github.com/livrereader/livre]

The Livre EBook Reader is a desktop app that parses and displays `.epub`-formatted eBooks. I wrote it as a side project to address a frustration of mine that I could not find any good-looking eBook readers for Linux. I wrote it using [Electron](https://electron.atom.io), a tool that compiles HTML, CSS, JavaScript into native desktop applications using Node.js and the Chromium browser engine. I released Livre as an open-source project on Github, which entailed responding to issues and pull requests and marketing the project on social media platforms.

Working with other developers on an open-source project provided excellent project experience working in a group. This project also expanded my knowledge about the concepts and techniques of software design, especially regarding turning source code into a working desktop applications that users can use without any hassle.

## LittleScheme
Repository: [https://github.com/jdormit/littlescheme]

LittleScheme is an interpreter for the Scheme programming language, written in Scala. This was a group project for my Programming Languages class. The interpreter knows how to handle a large subset of the Scheme language, including definitions, let-bindings, lambdas, and arithmetic operations. From this project, I learned about parsing, syntax trees, macro expansions, functional programming, and other high-level programming languages concepts.

Although both Scheme and Scala are quite high-level languages, this project still helped me attain a system level understanding of the computer. While implementing an interpreter, I had to optimize for things like stack allocations vs. heap allocations. I also learned about how computers translate source code into instructions, and got some insight into compilers and compiler optimizations. As a group project, LittleScheme helped me acquire more project experience working in a group. Developing a programming language includes lots of abstract thinking, which improved my problem solving skills.

## txtpic
Repository: [https://github.com/jdormit/txtpic]

`txtpic` is a small program I wrote in the Rust language that turns images into Unicode text art. It is a command line utility, so the project included not only writing the image transformation logic, but also implementing argument parsing and validation.

Rust is a systems-level non-garbage-collected language, so I had to carefully manage the memory allocated by my program. This helped my attain a system level understanding of the computer. The design of the code was very modular, which helped my understand the concepts and techniques of software design.

## Elm L-System Web App
Repository: [https://github.com/jdormit/elm-l-system]

This is a web application that lets users play around with Lindenmayer systems. L-systems are a type of [context-free grammar](https://en.wikipedia.org/wiki/Context-free_grammar) that can be used to represent fractals. The web application allows users to enter a set of L-system rules or choose from some presets, and iterate through the resulting fractal in their browser. I wrote it in the [Elm programming language](https://elm-lang.org), a functional programming language that compiles to JavaScript.

This project involved some fairly complicated recursive logic to calculate and render the fractal shapes, as well as implementing a parser for the L-system grammar language. These significant challenges boosted my problem solving skills quite a bit. The Elm language has a huge focus on [good architecture practices](https://guide.elm-lang.org/architecture/), so I learned a lot about the concepts and techniques of software design as well.

## My Resume
See [this link](https://docs.google.com/document/d/1y7cTOkCTmMeK64Lmi0p_Kh2bfWb-Gn-R6i9atkaJw60/edit?usp=sharing).
