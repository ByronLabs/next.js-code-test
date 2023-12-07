# next-code-test

**Title: Simple Cybersecurity Incident Reporting Web App**

**Description:**

You are tasked with creating a simple web application using Next.js that interacts with a backend FastAPI server for basic cybersecurity incident reporting. This system will allow organizations to report cybersecurity incidents and view a list of reported incidents.

**Requirements:**

1. **Incident Model:**
   - Utilize the same model for representing a cybersecurity incident with the following attributes:
     - Incident ID (auto-generated)
     - Date and Time of Incident
     - Description

2. **Backend FastAPI Server:**
   - Use FastAPI, check the [Python code test](https://github.com/ByronLabs/python-code-test), to implement the backend API with the previously defined endpoints for reporting incidents and listing all incidents.

3. **Frontend Next.js App:**
   - Create a Next.js application that interacts with the FastAPI backend.
   - Implement a form for organizations to report new incidents with input fields for Date and Time and Description.

4. **Integration:**
   - Ensure that the Next.js frontend interacts seamlessly with the FastAPI backend. Use appropriate API calls to report incidents and retrieve the list of incidents.

5. **Authentication:**
   - Implement a simple authentication mechanism for the Next.js app to ensure that only authorized users can report incidents.


**Notes:**
- Keep the focus on simplicity and ease of understanding for interview purposes.
- Use in-memory data storage for the FastAPI backend.
- Do not worry about advanced features or complex functionalities.

**Submission:**
- Provide the source code for the FastAPI backend and Next.js frontend.
- Include a brief README.md file explaining how to set up and run both the backend and frontend.
- Share the GitHub repository link or a zip file with the submission.
