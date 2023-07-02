# Jobbly - API Endpoint Integrated with LLM (OpenAI)
### Abstract: <br>
Jobbly is an API endpoint named, designed to assist job seekers and career enthusiasts. Integrated with the LLM (Large Language Model) from OpenAI, Jobbly offers a comprehensive set of features to provide valuable job-related information and resources. With Jobbly, users can access various endpoints to receive personalized job recommendations, explore necessary skills for different roles, discover salary ranges, and gain access to curated resources such as books, free online courses, and paid Udemy courses. With its seamless integration of the OpenAI LLM, Jobbly empowers users with the insights they need to make informed career decisions and take the next steps towards their professional success.
### API Link:
https://jobbly-65re.onrender.com <br> (Deployed on Render)

### Routes: <br>
### 1.
- **Route**: /
- **Method**: GET
- **Description**: This is the default route of the Flask app. When you access the root URL, it returns the message "Welcome to the API!".<br>
### 2.
- **Route**: /api
- **Method**: POST
- **Description**: This route handles POST requests. It expects a JSON payload with a "message" field which expects skills of the user and then the response contains a JSON object with a list of recommended jobs.<br>
### 3.
- **Route**: /jobs/links
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and the corresponding Indeed job link.<br>
### 4.
- **Route**: /jobs/skills
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and a list of necessary skills.<br>
### 5.
- **Route**: /jobs/salary
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and the salary range<br>
### 6.
- **Route**: /resources/books
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and a list of recommended books.<br>
### 7.
- **Route**: /resources/freecourses
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and the YouTube URL.<br>
### 8.
- **Route**: /resources/paidcourses
- **Method**: POST
- **Description**: The response contains a JSON array with dictionaries that include the job title and the Udemy URL.<br>

