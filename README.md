
Resource planner for employees: In this Application, we are aiming to get Top employees based on certain condition and filters in which we have a best fit function where we are getting top employees based on experience and rating and returning the result in this tabular format where you can see the sample output in below image

issue List:
05/24
* If I am searching for multiple skills and there is a threshold which skills you want to give more priority, we have to decide that we were also checking if any of the skills had a matching score above 80% for a given competency code. This means that if at least one skill had a score above the threshold, the competency code would be included in fuzzy_results. However, this might lead to cases where one skill has a good match, but others don't.(resolved)

![image](https://github.com/puranjay1234/tek-react-poc/assets/55429956/08ad5720-dd45-4d21-99b7-e11a9284a9b7)





Libraries to install:
1. Flask
2. react
3. Python
4. flask_cors

## Running the Server

To run the server, follow these commands:

1. For Node.js server:
   ```bash
   npm start
   ```

2. For Flask server:
   ```bash
   python app.py
   ```

## Features

### Completed Tasks

1. **Search Bar Priority:** The search bar now loads on the home screen if no data is present. ✅
2. **Search Button Addition:** Added a search button near the search bar. ✅
3. **Multiple Words Functionality:** This feature is pending. ⛔
4. **Best Fit Option (Todo):** To be implemented.
5. **Download Button (Todo):** To be implemented.
6. **Suggestion in Search Bar (Todo):** To be implemented.
7. **Database Display:** Data is shown in a tabular format. ✅

### Error/Bug Fixes and Suggestions

1. **API Data Visibility Issue:**
   - Data is being fetched from the API but is not visible in the UI. Only half of the fields are displayed in a random order, making it difficult to understand the structure of the tables.
   ![image](https://github.com/puranjay123/tek-react-poc/assets/55429956/8655dc6f-9f69-4370-a57a-39400347daa3)

2. **React Components for Table Rendering:**
   - Consider leveraging React components for rendering tables. This can simplify the process and ensure a consistent tabular format without manual interventions.

3. **Handling Multiple Words:**
   - Multiple words functionality might not be necessary, as separate rows for distinct skills can be displayed for a particular employee.

4. **Predefined Suggestions:**
   - Suggestions in the search bar could be predefined or retrieved from the database for easier implementation.













