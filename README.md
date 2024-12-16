# tskr

**`tskr`** is a lightweight, CLI-based task management toolkit designed to help developers keep track of their tasks directly from the terminal. It provides an intuitive command-line interface to create, manage, and organize tasks without leaving the development environment.

---

## Features

- **Task Management**: Add, edit, delete, and list tasks seamlessly.
- **Tagging System**: Organize tasks using tags for better categorization.
- **Search Functionality**: Quickly find tasks by keywords or tags.

---

## Installation

To install `tskr`, use pip:

```bash
pip install tskr
```

---

## Usage

Once installed, you can use the `tskr` command to manage tasks:

### Add a Task
```bash
tskr add "Fix bug in authentication flow" --tag bugfix
```

### List All Tasks
```bash
tskr list
```

### Search for Tasks
```bash
tskr search "authentication"
```

### Delete a Task
```bash
tskr delete <task_id>
```

For more commands, run:
```bash
tskr --help
```

---

## Contributing

We welcome contributions! If you have ideas or enhancements, feel free to:

1. Fork the repository.
2. Create a new branch (`feature/my-feature`).
3. Commit your changes.
4. Push to your branch and create a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Support

For issues or questions, please create a ticket on the GitHub issues page.
