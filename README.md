# tsky

**`tsky`** is a lightweight, CLI-based task management toolkit designed to help developers keep track of their tasks directly from the terminal. It provides an intuitive command-line interface to create, manage, and organize tasks without leaving the development environment.

---

## Features

- **Task Management**: Add, edit, delete, and list tasks seamlessly.
- **Tagging System**: Organize tasks using tags for better categorization.
- **Search Functionality**: Quickly find tasks by keywords or tags.

---

## Installation

To install `tsky`, use pip:

```bash
pip install tsky
```

---

## Usage

Once installed, you can use the `tsky` command to manage tasks:

### Add a Task
```bash
tsky add "Fix bug in authentication flow" --tag bugfix
```

### List All Tasks
```bash
tsky list
```

### Search for Tasks
```bash
tsky search "authentication"
```

### Delete a Task
```bash
tsky delete <task_id>
```

For more commands, run:
```bash
tsky --help
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
