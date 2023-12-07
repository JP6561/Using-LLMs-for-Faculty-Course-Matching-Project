# Using LLMs for Faculty Course Matching Project
This project aims to improve the process of matching faculty to courses at universities by leveraging large language models (LLMs).This will ensure efficient allocation of faculty expertise to appropriate courses, enhancing overall educational quality.
# Project Description
This project create a prompt engineering methodology utilizing LLMs to align faculty resumes with program course descriptions, identifying gaps and facilitating the assignment of courses.This project aims to improve the process of matching faculty to courses at universities by leveraging large language models (LLMs). The current system uses basic text similarity scoring in R. By utilizing the advanced natural language capabilities of LLMs through prompt engineering, we can automate the matching process to quickly and accurately align faculty skills and interests with course needs.The technology tools will automatically generate a list of courses in order of similarity score. Our clients can use this productive tool to assign highly relevant courses based on individual resumes quickly.
# Use Case
Claude AI and ChatGPT allows users to seamlessly upload both a resume and a data file containing course descriptions. Through its advanced algorithms, the application generates a table, presenting scores that indicate the compatibility of the uploaded resume with various course descriptions. This insightful report serves as valuable guidance, advising users on the optimal courses to assign to the faculty member based on the analysis of their qualifications and expertise. It will produce a report of resume scores against course description to advise the users on the best courses to assign to the faculty member. 
1. Users should convert all Excel files into Text files before uploading the
resume.
2. Users should make sure the CSV file (courses titles and course descriptions) contains two
columns with the “Title” header and the “Description” header. These will allow the
algorithm to read that column.
3. Upload the source files.
4. Upload the Prompts 
5. Hit the button
6. If the user uploads a resume and course descriptions as the source files, he/she will get a
scouring table contained course title and similarity score in order of descending similarity
scores.
7. The user can copy the table to the result as an Excel file.
