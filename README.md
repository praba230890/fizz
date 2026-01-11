# 🎈 Fizz - A Programming Language for Kids

**Fizz** is a beginner-friendly programming language designed specifically for children aged 7-12. It removes common barriers like indentation sensitivity and cryptic syntax, replacing them with natural English-like commands that read like stories.

## 🌟 Philosophy

- **Cognitive load > Syntax purity** - Every rule must earn its place
- **Programs read like stories** - Kids understand sequences naturally
- **Visual structure > invisible rules** - No hidden indentation
- **Errors should teach** - Friendly, conversational error messages
- **Immediate reward** - First program runs in under 60 seconds

## 🎯 Design Principles

1. **No indentation requirements** - Blocks use explicit `end` keywords
2. **English-like syntax** - `put 5 into score` instead of `score = 5`
3. **Conversational errors** - Helpful messages that guide learning
4. **Built-in fun** - Commands like `say`, `wait`, `play sound`

## 📖 Quick Example

```fizz
say "Hello, world!"

put 10 into score

repeat 3 times
    say "Jump!"
end

if score > 5
    say "You win!"
otherwise
    say "Try again!"
end

how to greet name
    say "Hello " + name
end

greet "Alex"
```

## 🏗️ Project Structure

```
kids-lang/
├── src/              # Source code
│   ├── lexer/        # Tokenization (breaking text into words/symbols)
│   ├── parser/       # Parsing (building program structure)
│   ├── ast/          # Abstract Syntax Tree (program representation)
│   ├── interpreter/  # Execution engine
│   └── main.cpp      # Entry point
├── include/          # Header files
├── tests/            # Test programs
├── examples/         # Example Fizz programs
└── docs/             # Documentation

```

## 🎓 Learning Journey

This project is designed to teach:
1. **C++ Programming** - Modern C++17 features
2. **Compiler Design** - Lexer, Parser, AST, Interpreter
3. **Language Design** - Making syntax decisions that matter

### Phase 1: Lexer (Tokenization)
Breaking source code into meaningful chunks (tokens)
- Keywords: `say`, `put`, `if`, `repeat`, `end`
- Identifiers: variable names
- Literals: numbers, strings
- Operators: `+`, `-`, `>`, `<`

### Phase 2: Parser
Building a tree structure from tokens
- Understanding grammar rules
- Creating Abstract Syntax Tree (AST)
- Handling syntax errors

### Phase 3: AST (Abstract Syntax Tree)
Representing the program structure
- Expression nodes
- Statement nodes
- Function definitions

### Phase 4: Interpreter
Executing the program
- Variable storage (environment)
- Expression evaluation
- Control flow (if, loops)
- Function calls

## 🚀 Getting Started

### Prerequisites
- C++17 compatible compiler (GCC, Clang, or MSVC)
- CMake (optional, for build system)

### Building
```bash
# Coming soon - we'll add build instructions as we go
```

### Running a Fizz Program
```bash
# Coming soon
fizz my_program.fizz
```

## 📚 Language Reference

See [LANGUAGE_SPEC.md](docs/LANGUAGE_SPEC.md) for complete grammar and syntax.

## 🎮 Example Programs

Check the `examples/` folder for:
- `hello.fizz` - Your first program
- `counter.fizz` - Variables and loops
- `functions.fizz` - Teaching the computer tricks
- `game.fizz` - A simple game

## 🛣️ Roadmap

- [x] Language design & specification
- [ ] Lexer implementation
- [ ] Parser implementation
- [ ] AST definition
- [ ] Basic interpreter
- [ ] Error handling
- [ ] Standard library (say, wait, etc.)
- [ ] File I/O
- [ ] Advanced features (lists, more functions)

## 🤝 Contributing

This is a learning project! Contributions, suggestions, and feedback welcome.

## 📄 License

MIT License - Learn, share, and have fun!

---

**Built with ❤️ for curious young minds**
