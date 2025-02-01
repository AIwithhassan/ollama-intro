# Ollama Python Script Setup Guide

This guide will help you get started with running a Python script using Ollama and the requests library. Follow these steps to set up and run the script.

---

## Prerequisites

1. **Install Ollama**:
   - Download and install Ollama from the official website: [https://ollama.com/download](https://ollama.com/download)
   - Ensure Ollama is running locally on your machine.

2. **Install Required Libraries**:
   - Install the `requests` library using pip:
     ```bash
     pip install requests
     ```

---

## Setup Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AIwithhassan/ollama-intro.git
   cd ollama-intro
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Script**:
   ```bash
   python ollama_personal.py
   ```
   ```bash
   python ollama_with_library.py
   ```

---

## Troubleshooting

- **Ollama Not Running**:
  - Ensure Ollama is running and accessible at `http://localhost:11434`.
  - Restart Ollama if necessary or run **ollama serve**.

- **Connection Issues**:
  - Verify your network connection.
  - Check if the Ollama port (default: 11434) is open.

- **Missing Dependencies**:
  - Reinstall the dependencies using `pip install -r requirements.txt`.

---

## Ollama Command Cheatsheet

Here’s a quick reference table for major Ollama commands:

| **Command**                     | **Description**                                                                 | **Example**                                                                 |
|---------------------------------|---------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| `ollama list`                   | List all installed models.                                                     | `$ ollama list`                                                           |
| `ollama run <model>`         | Download and run a specific model.                                                      | `$ ollama run llama2`                                                    |
| `ollama rm <model>`          | Remove a specific model.                                                       | `$ ollama rm llama2`                                                    |
| `/bye`          | Get out of Model Prompt session                                                       | `/bye`                                                    |

---

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by the Ollama documentation and community resources.
- Special thanks to the Ollama team for creating this amazing tool!

---

If you encounter any issues or have suggestions, feel free to open an issue or reach out to the maintainer.