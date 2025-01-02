# Multi Agent Crew to Automate Job Applications!

Welcome to the **Job-Search-AI-Agent** repository! This project is a robust AI-powered agent designed to streamline your job search process. By leveraging a multi-agent framework through CrewAI and its tools, this agentic system analyzes job descriptions and matches them with your skills, generating tailored resumes to enhance your job applications.

## Features
- **Intelligent Matching**: Matches your resume with job postings for high compatibility.
- **Customizable Filters**: Adjust criteria to focus on your ideal roles.
- **Automated Insights**: Provides actionable feedback on how to enhance your profile for specific roles.
- **Convenient Interface**: Designed for ease of integration and use by developers.

## Repository Structure
The repository follows a well-organized directory structure:

```plaintext
Job-Search-AI-Agent/

├── notebooks/        # Jupyter notebooks for core development inlcuding all Agent code using crewai
├── data/             # Placeholder for datasets (not included in the repo)
├── requirements.txt  # Dependencies for the project
├── README.md         # Project documentation (this file)
```

### Key File: `resume_builder.ipynb`
The `resume_builder.ipynb` notebook provides an interactive interface to create and optimize resumes tailored to specific job descriptions.

## Installation
To set up the project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/saadtariq001s/Job-Search-AI-Agent.git
   cd Job-Search-AI-Agent
   ```

2. Create a virtual environment and activate it (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/resume_builder.ipynb
   ```

## Usage
1. Open the `resume_builder.ipynb` notebook and follow the guided steps to load your resume and job descriptions.
2. The notebook will:
   - Parse the job descriptions.
   - Analyze your resume for compatibility.
   - Suggest improvements or generate tailored resumes for specific jobs.

## Contribution
We welcome contributions to enhance this project! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## Support
If you encounter any issues or have questions, feel free to open an issue in the repository or contact [Saad Tariq](https://github.com/saadtariq001s).

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
Happy job hunting! 🎯
