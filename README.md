# `creapack` Documentation

## Introduction

`creapack` is a command-line tool designed for interacting with the creaPack platform. It provides various functionalities to manage projects, login/logout, push projects, install packages, and handle dependencies.

## Version

Current Version: v0.1

Developed by: timuzkas & Kiefe

## Usage

### 1. Login to creaPack

```bash
creapack login <username> <password>
```

- Log in to the creaPack platform using your username and password.

### 2. Signout from creaPack

```bash
creapack signout
```

- Sign out from the creaPack platform.

### 3. Create a new creaPack project

```bash
creapack create <package_name> <description>
```

- Create a new project on creaPack with the specified package name and description.

### 4. Push a project to creaPack

```bash
creapack push <project_name> <version> <Patch notes>
```

- Push a project to creaPack, specifying the project name, version, and patch notes.

### 5. Install a package

```bash
creapack install <package_name> <path>
```

- Install a package from creaPack using the specified package name and path.

### 6. Manage dependencies

#### Add a dependency to a project

```bash
creapack dependency add <project_name(path)> <dependency_name>
```

- Add a dependency to a project, specifying the project name (or path) and the dependency name.

#### Remove a dependency from a project

```bash
creapack dependency remove <project_name(path)> <dependency_name>
```

- Remove a dependency from a project, specifying the project name (or path) and the dependency name.

### 7. Display Help

```bash
creapack help
```

- Display the help menu, providing information on the available commands and their usage.
