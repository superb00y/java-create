# java-project

A simple bash script that creates and compiles and runs a java project from the cli, if you don't want to use maven or Gradle or an IDE.

- Usage:

```bash
~ ❱ ./java-project help
Usage: ./java-project [create|add|remove|compile|build|run|clean|help]
  create NAME     Create a new Java project with the given name
  add CLASS       Add a new class to the current project
  remove CLASS    Remove a class from the current project
  add-resource    FILE|DIR  Add a file or directory to the project resources
  compile         Compile the current project
  build           Build the current project JAR file
  run             Run the compiled project
  clean           Clean the project by removing compiled files and JAR
  help            Display this help message
```

You can use the script as is or make it system-wide by doing the following:

- Place it in /usr/local/bin/ (recommended) or ~/.local/bin/

- Make it executable:

```bash
chmod +x /usr/local/bin/java-project
```

- Ensure the directory is in your PATH:

  If using ~/.local/bin/, add this to ~/.bashrc or ~/.zshrc:

```bash
export PATH="$HOME/.local/bin:$PATH"
```

- Then run:

```bash
source ~/.bashrc # or source ~/.zshrc
```
