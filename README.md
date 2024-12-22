# CS300
Project Overview

This project was developed as part of my coursework to create a Course Planner application that allows users to load and search for courses, print a course list, and view specific course details, including prerequisites. The application implements a custom HashMap to efficiently manage and retrieve course data.

Problem Statement

The primary problem addressed in this project was how to efficiently store, organize, and retrieve course data, including course IDs, titles, and prerequisites. The goal was to design a data structure that supports fast access and handles potential hash collisions effectively.

Approach

I used a custom HashMap to store course data, leveraging hashing to ensure efficient data retrieval. By using a hash function to map course IDs to table indices, I could organize the courses in a way that minimized lookup time. Data structures like vectors were critical for managing course lists and handling hash collisions within the table.

Understanding data structures was essential for solving this problem, as they directly impacted the performance and scalability of the application.

Overcoming Challenges

One of the challenges I encountered was handling hash collisions effectively in the HashMap. To address this, I implemented chaining, where collisions are resolved by storing multiple items in a vector at the same index. Debugging file I/O operations and ensuring data integrity during the loading process were also significant hurdles, but these were resolved through iterative testing and careful error handling.

Lessons Learned

Working on this project expanded my understanding of designing software with a focus on efficient data handling. I learned the importance of choosing the right data structures for specific tasks and how they influence both the performance and maintainability of an application.

Additionally, I developed a deeper appreciation for code readability and modularity. For instance, separating file-loading logic and user interface elements made the codebase easier to understand and maintain.

Writing Maintainable Code

This project reinforced the importance of writing programs that are:

Readable: By using descriptive variable names and modular functions, the code is easier to understand for future developers.

Adaptable: The HashMap design can be expanded to include additional features, such as course search by title or advanced sorting options.

Maintainable: Structured error handling and comments throughout the code ensure that updates and debugging are straightforward.

How to Run the Application

Compile the code using a C++ compiler.

Run the application.

Use the menu options to load course data, print the course list, or search for a specific course.
