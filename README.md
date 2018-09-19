# GodotEnvDTE
Godot utility to open files in an existing Visual Studio instance using EnvDTE

Opens the file(s) in a Visual Studio instance that is editing the solution.
If an existing instance for the solution is not found, a new one is created.

## Usage

```
GodotEnvDTE solution [file[:line[:col]]...]
```
