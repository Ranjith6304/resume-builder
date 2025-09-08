

# Resume Builder with OpenAI API

The OpenAI Resume Builder is a web application that generates resumes based on user-provided information. Users can input their name, education, skills, and hobbies, and the app uses the OpenAI API to create a one-page resume tailored for a software engineering job.

## Features

- User-friendly interface for inputting personal and professional details.
- Integration with the OpenAI API for generating personalized resumes.
- Ability to add and manage education, skills, and hobbies.
- Outputs a one-page resume highlighting skills for a software engineering job.

## Getting Started

To get started with the OpenAI Resume Builder, follow these steps:
1. Install the required dependencies:

   ```
   npm install
   ```



2. Create a `.env` file in the root directory of your project and store your API key as follows:

   ```
   REACT_APP_OPENAI_API_KEY=your-api-key

   ```

3. Start the development server:

   ```
   npm run dev
   ```

4. Access the application in your web browser at `http://localhost:3000` or another port number allocated by your system.

## Usage

1. Enter your OpenAI API key in the provided input field and click "Submit API Key."

2. Fill out your name, education, skills, and hobbies in the respective input fields.

3. Click the "Generate Resume" button to create a one-page resume highlighting your skills for a software engineering job.

4. The generated resume will be displayed with line breaks using `<br/>` tags.

## Dependencies

- React
- Vite
- OpenAI API

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.





