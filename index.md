---
layout: cv
title: Jake Becker
---
# Jake Becker
Elixir programmer. I wrote ElixirLS, a popular IDE plugin for Elixir developers. I also do Erlang, Ruby, and Javascript. 

<div id="webaddress">
<a href="mailto:jake@jakebecker.org">jake@jakebecker.org</a>
| <a href="https://github.com/JakeBecker">github.com/JakeBecker</a>
</div>


## Open-source work

`2017-now`

### [ElixirLS](https://github.com/JakeBecker/elixir-ls) (owner)

An IDE "smartness" server I wrote that powers IDE plugins for Elixir using the the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/). Provides features such as auto-completion, go-to-definition, compilation and error reporting, debugger integration, and quick static analysis using a modified Dialyzer. The [VS Code Elixir plugin](https://marketplace.visualstudio.com/items?itemName=JakeBecker.elixir-ls) it powers is one of the most popular IDE plugins among Elixir developers.

### [Elixir](https://github.com/elixir-lang/elixir) (contributor)

I contributed changes to Elixir to make it report compile errors and warnings in a standardized way that can be utilized by editors and IDE plugins. I added the behaviour [Mix.Task.Compiler](https://hexdocs.pm/mix/Mix.Task.Compiler.html) and updated Elixir's compilers to adhere to it.

### [Ecto](https://github.com/elixir-ecto/ecto) (contributor)

I contributed changes to Ecto's domain-specific query language and SQL adapter to support comparison between tuples of fields. (For example, WHERE ("Jake", "Becker") > (first_name, last_name)). This is supported by most relational databases and is useful for certain kinds of cursor-based pagination.

### [IntelliJ Elixir](https://github.com/KronicDeth/intellij-elixir) (contributor)

I added support for Elixir's debugger and for ExUnit tests using the IDE's graphical test runner. To my knowledge, IntelliJ Elixir and VS Code ElixirLS are the only two IDE plugins for Elixir that include debugger support.

## Treasure Data

`2013-2017`

### Lead API Engineer

I implemented and maintained Treasure Data's API, written in Ruby on Rails. It powers a CLI client and a web app. I also contributed to the web app, which was written initially in Angular 1.x and then later in React. Treasure Data was acquired by Arm in 2018 for approximately $600 million.

## Education

### Stanford

`Class of 2012`
B.S. in Computer Science

<!-- ### Footer

Last updated: September 2019 -->


