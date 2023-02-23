# ABCU-Advising
Program created to use a csv file to generate a course schedule with prerequisites to courses for a university.

---

## Runtime/Memory Analysis

| Data Structure       | Best Case  Runtime Analysis | Worst Case  Runtime Analysis | Memory Analysis Worst Case |
|----------------------|-----------------------------|------------------------------|----------------------------|
| File Parser          | ASID - O(n)                 | ASID - O(n)                  | O(n)                       |
| Course Object Loader | ASID - O(n)                 | ASID - O(n)                  | O(n)                       |
| Vector               | Access - O(1) SID - O(n)    | Access - O(1) SID - O(n)     | O(n)                       |
| Hash Table           | ASID - O(1)                 | Access - O(1) SID - O(n)     | O(n)                       |
| Binary Search Tree   | ASID - O(log n)             | ASID - O(n)                  | O(n)                       |

---

### What was the problem you were solving in the projects for this course?

ABCU is a company that is trying to develop a program to display all courses in a student's schedule. The job of this program was to gather all of the necessary prerequisites, titles, and codes to each course from a csv file. Essentially, this program can be used to recieve a file from the user, and print out their course schedule from the file selected.

### How did you approach the problem? Consider why data structures are important to understand.

I had to approach the problem in a way that I could structure the data recieved from the courses file to improve the runtime and memory management correctly. I could have implemented a linked list structure which may have been sufficient since this only holds one student's course. But in the end it would be better to use a structure that could scale and still become easy to manage.

### How did you overcome any roadblocks you encountered while going through the activities or project?

I asked for help when I needed it. If I was stuck I first asked questions such as "How is this data in memory accessed?". Answering questions such as these led to me understanding data structures more as I could see how to make the program optimized to the best capacity

### How has your work on this project expanded your approach to designing software and developing programs?

This project has caused me to think more about how I can store the data in different structures to manipulate the data a little easier, depending on the implmentation of the program.

### How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

This has helped me to deteremine a more finite way to write programs by thinking more about how to implement a program such as this with different ways of doing the same thing. This has helped me to develop new approaches in writing programs that can alter or otherwise store data differently.
