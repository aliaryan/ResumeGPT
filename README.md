## ResumeGPT: An AI Driven Resume Screening Tool

## About

Resume GPT is an efficient recruitment assistant powered by OpenAI's GPT-3.5. The tool allows recruiters to upload multiple resumes along with a job description. You can further specify mandatory keywords that should be present in a candidate's resume. As a result, the tool will provide an evaluation of each resume against the provided job description and give insights into the suitability of the candidate for the role.

## Features

- Bulk upload of resumes in PDF format.
- Specification of a job description to compare the resumes against.
- Option to add mandatory keywords for the desired candidate profile.
- Analysis of resumes using OpenAI GPT-3.5 to generate suitability remarks.
- Downloadable results in a CSV format with columns for resume name, comments, and suitability.

## Requirements
- Flask
- OpenAI Python Client
- pdfplumber
- CSV module

## Setup

1. Clone the repository.
```
git clone https://github.com/aliaryan/ResumeGPT.git
```
2. Change directory to the cloned repository.
```
cd resume-gpt
```
3. Install the required packages.
```
pip install Flask openai pdfplumber
```
4. Update the OpenAI API key in the openai.api_key = "OPEN AI KEY" line with your own key.
5. Run the application.
```
python screening_tool.py
```

## Usage

1. Access the tool by visiting http://localhost:5000 in your browser.
2. Upload the desired resumes.
3. Provide a detailed job description.
4. Specify any mandatory keywords that you want to be present in the candidate's resume.
5. Click on "Submit" to get the analysis.
6. You can then download the results in a CSV format.

## Limitations

1. As the tool uses the OpenAI API, you will need a valid API key which might have associated costs.
2. The current version supports resumes in PDF format only.

## Contributing

Feel free to submit pull requests, raise issues, or give feedback. Your contributions are welcome!

## If you find this tool useful, please give us a ⭐! Starring the repository supports the project and encourages further development.

## License

This project is open source and available under the MIT License.
