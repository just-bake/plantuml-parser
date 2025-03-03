# PlantUML Code Generator

## Overview
The **PlantUML Code Generator** is a tool designed to bridge the gap between visual design and code implementation. It allows users to convert **PlantUML class diagrams** into **source code files** in a selected programming language (e.g., Java, Python, C++) and vice versa. This tool is particularly useful for developers who want to generate code from diagrams or visualize existing codebases using PlantUML.

---

## Features
- **PlantUML to Code:** Convert PlantUML class diagrams into source code files.
- **Code to PlantUML:** Generate PlantUML class diagrams from source code files.
- **Multi-Language Support:** Supports multiple programming languages (Java, Python, C++, etc.).
- **User-Friendly Interface:** Provides both CLI and GUI options for ease of use.
- **Extensible Architecture:** Easily add support for new programming languages.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Java (for PlantUML library)
- Graphviz (for rendering PlantUML diagrams)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/plantuml-code-generator.git
   cd plantuml-code-generator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download and set up PlantUML:
   - Download the PlantUML JAR file from [PlantUML's official website](https://plantuml.com/download).
   - Place the JAR file in the `lib/` directory of the project.

4. Install Graphviz:
   - On Ubuntu:
     ```bash
     sudo apt-get install graphviz
     ```
   - On macOS:
     ```bash
     brew install graphviz
     ```

5. Run the tool:
   ```bash
   python main.py
   ```

---

## Usage

### 1. Convert PlantUML to Code
To generate source code from a PlantUML diagram:
```bash
python main.py --plantuml-to-code --input diagram.puml --output output_dir --language java
```
- `diagram.puml`: Path to the PlantUML file.
- `output_dir`: Directory where the generated code will be saved.
- `language`: Target programming language (e.g., `java`, `python`, `cpp`).

### 2. Convert Code to PlantUML
To generate a PlantUML diagram from source code:
```bash
python main.py --code-to-plantuml --input src_dir --output diagram.puml --language java
```
- `src_dir`: Directory containing the source code files.
- `diagram.puml`: Path to the output PlantUML file.
- `language`: Source code language (e.g., `java`, `python`, `cpp`).

### 3. GUI Mode
To launch the graphical user interface:
```bash
python main.py --gui
```

---

## Supported Languages
- Java
- Python
- C++
- (More languages can be added by extending the tool's templates.)

---

## Contributing
We welcome contributions! Here's how you can help:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

Please ensure your code follows the project's coding standards and includes appropriate tests.

---

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- [PlantUML](https://plantuml.com/) for providing the diagram generation library.
- [Graphviz](https://graphviz.org/) for rendering diagrams.
- The open-source community for inspiration and support.

---

## Contact
For questions, feedback, or support, please open an issue on the [GitHub repository](https://github.com/your-repo/plantuml-code-generator/issues) or contact the maintainer at [your-email@example.com](mailto:your-email@example.com).

---

Happy coding and diagramming! 🚀
