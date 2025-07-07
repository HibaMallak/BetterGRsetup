# User Documentation


Welcome to BetterGR – a platform built to streamline course management, user engagement and educational processes within universities.

This documentation serves as a guide for users and is designed to provide clear and concise instructions for end users of BetterGR. It aims to help users understand how to access, navigate and utilize the various functionalities of the platform to enhance their educational experience.




## Getting Started
### Downloading the Relevant Repository
To set up BetterGR, follow these steps:

1. **Clone the Setup Repository**:

    Clone the `setup` repository using the following command:
    ```bash
    git clone https://github.com/BetterGR/setup.git
    ```

2. **Run Docker Compose**:

    Navigate to the cloned repository:
    ```bash
    cd setup
    ```
    Start the application using Docker Compose:
    ```bash
    docker compose up
    ```
    This command will automatically set up all services and open the system link in your default web browser.

  ---

## Navigating the Dashboard

The BetterGR dashboard is the central hub for users to access and manage their academic activities. It provides a user-friendly interface with organized sections to help users stay updated and track their progress effectively.

### Dashboard Features
1.  **Navigation Bar**:
    - Located at the top of the dashboard.
    - Includes links to other pages such as:
        - **Courses**: View and manage all enrolled courses.
        - **Assignments**: Track and submit assignments.
        - **Grades**: Review grades and feedback.
    - Users can also select the semester they want to view, allowing them to filter data based on the academic term.


2. **Key Blocks**:
   At the top of the dashboard, there are three blocks summarizing key academic metrics:
    - **Courses**:
        - Number of courses enrolled, completed, and in progress.
    - **Assignments**:
        - Number of tasks submitted, pending, or late.
    - **Grades**:
        - Average grade, top grade, and lowest grade.
    
    These blocks provide a quick overview of the user's academic status in a friendly and concise manner.


3. **Recent Announcements**:
    - View the latest announcements from all enrolled courses.
    - Stay informed about important updates, deadlines, and events.


4. **Upcoming Assignments**:
    - A list of assignments due soon across all courses.
    - Helps users prioritize tasks and manage their workload.


5. **Your Courses**:
    - Displays courses the user is enrolled in.
    - Each course is clickable, allowing users to navigate to the course's dedicated page for detailed information and resources.


The dashboard is designed to provide users with a comprehensive yet accessible view of their academic activities, ensuring they can efficiently manage their tasks and track their progress.


### Dark and Light Mode
Users can customize the dashboard's appearance based on their preferences by toggling between light mode and dark mode, using a button located next to the Navigation Bar in the top-right corner, represented by a sun for light mode and a moon for dark mode.

### AI Chatbot Assistant
BetterGR features an AI Chatbot Assistant designed to enhance user experience by providing quick and accurate support for academic-related tasks and inquiries. It helps users efficiently manage their academic activities, resolve questions, and access information through a user-friendly interface.

#### How to Access the Chatbot
- On the bottom-right corner , you will find a button labeled with a chat icon.
- Clicking on this button opens the chat interface, allowing you to interact with the AI assistant.

When you open the chat, you can start by asking "hello, how can you help me?". The chat assistant will provide a brief list of actions it can help with.


#### Features and Capabilities
The Chatbot can assist with various tasks, including:
- **Course Information**: Provides details about your enrolled courses, such as course names and schedules.
- **Assignments and Grades**: Offers information about upcoming assignments, grades, and academic processes.
- **Navigation Assistance**: Guides you through the features and functionalities of the BetterGR platform.
- **Academic Queries**: Answers specific questions related to your studies, such as deadlines, course requirements, or grading policies.
- **Instructors Assistance**: Creating and managing courses, grading and feedback.

### Creating a New Course Page (Instructors Only)

BetterGR allows instructors to dynamically create new course pages using Markdown files. 

This feature simplifies the process of adding course-specific content and ensures consistency across pages.

#### Steps to Create a New Course Page:
1. **Access the Course Management Section**:
    - Navigate to the "Course Management" section from the dashboard.

2. **Upload a Markdown File**:
    - Click on the "Create New Course Page" button.
    - Select the Markdown file containing the course information and upload it.

3. **Preview and Confirm**:
    - After uploading, the system will generate a preview of the course page based on the Markdown content.
    - Review the preview and click "Confirm" to finalize the creation of the page.

4. **Access the New Page**:
    - The newly created course page will be accessible under the "Courses" section of the dashboard.

#### Requirements:
- Use standard Markdown formatting (headings, lists, links).
- Include course title, schedule, description, and grading criteria.

#### Notes:
- Ensure the Markdown file follows the required structure for course pages.
- Use headings, lists, and other Markdown elements to organize the content effectively.
- The system automatically formats the page based on the uploaded Markdown file.



## **Additional Resources**


- **Official Documentation**:
    - [API Gateway Documentation](api_docs.md)
    - [Microservices Documentation](microservices_docs)
    - [Developer Documentation](developer_doc.md)

- **Community and Support**:
    - [BetterGR GitHub Organization](https://github.com/BetterGR)
    - [Contact Support](link-to-support-page)

