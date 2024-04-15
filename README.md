# Resume-Builder
Using Python to build a Resume Builder
# Resume Generator

This Python script generates a resume in PDF format from user input. It prompts the user to input their personal details, education history, skills, work experience, projects, achievements, and other activities. It then converts the input into Markdown format and utilizes an API to convert the Markdown content into a PDF file.

## Features

- **User Input**: Collects user information interactively, including personal details, education, skills, work experience, projects, achievements, and activities.
- **Markdown Conversion**: Converts the user input into Markdown format, which is compatible with various text editors and version control systems.
- **PDF Generation**: Utilizes an external API to convert the Markdown content into a PDF file, providing a neatly formatted resume document.
- **Customization**: Allows customization of CSS styles for the PDF output, enabling users to tailor the appearance of their resume.

## How to Use

1. Clone or download the repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required Python packages by running `pip install -r requirements.txt`.
4. Run the script by executing `python resume_generator.py`.
5. Follow the prompts to enter your personal information, education, skills, experience, projects, achievements, and activities.
6. Once you've provided all the necessary details, the script will generate a PDF file named `Resume.pdf` in the current directory.

## Dependencies

- Python 3.x
- `requests` library (for making HTTP requests)
- An internet connection is required to utilize the Markdown to PDF conversion API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
