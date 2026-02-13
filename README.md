# I make easy RAG so you don't have to!

🚨  **Minimum Requirements `Python > 3.10.x` with  `SQLite > 3.35`, WSL/Ubuntu System**


---



## 1st Step : Prerequisites

- Ollama (because in my makefile I define llama3.2-1b and embeddings model nomic-embed-text)
```sh
ollama pull llama3.2:1b
ollama pull nomic-embed-text
```
- packages inside 'requirements'

## 2nd Step : Setting up locally 🔨

Create virtualenv and install dependencies.

```sh
make setup
```

## 3rd Step : Running the Application ⚡️

```sh
make run
```

Check for if there's any violations:

```sh
make check
```

Auto-fix lining violations:

```sh
make fix
```

## HELP

```sh
make

# OR

make help
```

## Common Issues and Fixes 🔧 

- TB Added
