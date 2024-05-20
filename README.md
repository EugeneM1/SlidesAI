# Slideshow Generator Using ChatGPT

Welcome to the Slideshow Generator! This program leverages OpenAI's ChatGPT to create beautiful, informative slideshows based on your textual descriptions. Whether you need a presentation for a business meeting, a school project, or any other purpose, this tool will help you create engaging slides quickly and easily.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Automated Slideshow Creation:** Generate slideshows from textual descriptions with ease.
- **Customizable Slides:** Tailor the content and style of each slide to meet your needs.
- **High-Quality Output:** Produce professional-grade slides with well-organized information.
- **User-Friendly Interface:** Simple command-line interface to interact with the tool.

## Requirements

- Python 3.8 or higher
- OpenAI API key

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/slideshow-generator.git
    cd slideshow-generator
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Set up your OpenAI API key:
    ```bash
    export OPENAI_API_KEY='your-api-key-here'  # On Windows, use `set OPENAI_API_KEY=your-api-key-here`
    ```

2. Run the program with your description:
    ```bash
    python generate_slideshow.py --description "Describe the content of your slides here."
    ```

3. The program will generate a slideshow file (e.g., `output.pptx`) in the current directory.

## Configuration

You can customize the configuration by editing the `config.yaml` file:

- **slide_template:** Path to a custom slide template.
- **output_format:** Format of the output file (e.g., `pptx`, `pdf`).
- **theme:** Specify a theme for the slides (e.g., `dark`, `light`).

## Examples

Here's an example of how to generate a slideshow:

```bash
python generate_slideshow.py --description "Create a slideshow about the benefits of renewable energy. Include sections on solar, wind, and hydro power."
```

Output:
- A `output.pptx` file with slides on the benefits of renewable energy, including sections on solar, wind, and hydro power.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy slide-making! If you encounter any issues or have any suggestions, feel free to open an issue or submit a pull request.
