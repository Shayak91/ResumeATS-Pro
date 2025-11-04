# ResumeATS Pro

ResumeATS Pro is a powerful web application built with Streamlit that helps users optimize their resumes for Applicant Tracking Systems (ATS) and improve their chances of landing their dream job. The application leverages Google's Gemini AI model to provide intelligent resume analysis and recommendations.

## Features

- **Multiple Analysis Options:**
  - Quick Scan: Get a rapid assessment of your resume with key strengths and improvement suggestions
  - Detailed Analysis: Receive comprehensive feedback on all aspects of your resume
  - ATS Optimization: Get specific suggestions to improve your resume's ATS compatibility

- **Smart Analysis:**
  - Profession identification
  - Strength assessment
  - Improvement recommendations
  - ATS compatibility scoring
  - Job description matching
  - Keyword optimization suggestions

- **Interactive Features:**
  - Chat functionality to ask questions about your resume
  - Helpful resources in the sidebar
  - Feedback submission option

## Technical Requirements

- Python 3.x
- Required packages:
  ```
  streamlit
  google-generativeai
  python-dotenv
  PyPDF2
  ```

## Setup Instructions

1. Clone this repository
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project root and add your Google API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```
4. Run the application:
   ```
   streamlit run main.py
   ```

## How to Use

1. Upload your resume in PDF format
2. (Optional) Enter the job description you're targeting
3. Choose your preferred analysis type:
   - Quick Scan
   - Detailed Analysis
   - ATS Optimization
4. Click "Analyze Resume" to get your results
5. Use the chat feature to ask specific questions about your resume

## Features in Detail

### Quick Scan
- Identifies suitable profession
- Lists 3 key strengths
- Suggests 2 quick improvements
- Provides an ATS score out of 100

### Detailed Analysis
- Comprehensive strength assessment (5 points)
- Detailed improvement recommendations
- Ratings for Impact, Brevity, Style, Structure, and Skills
- Section-by-section review
- Detailed ATS score breakdown

### ATS Optimization
- Job description keyword analysis
- Formatting recommendations
- Keyword density optimization
- Tailored improvement suggestions
- ATS compatibility scoring

## Resources

The application includes links to valuable resources:
- Resume Writing Tips
- ATS Optimization Guide
- Interview Preparation

## Contributing

Feel free to submit issues and enhancement requests!
