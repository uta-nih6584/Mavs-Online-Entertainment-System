# Mavs Online Entertainment System (MOES)

The **Mavs Online Entertainment System (MOES)** is a Java-based media management system that enables UTA students to legally access and manage a wide variety of media, including videos, music, podcasts, books, and games. This project was developed as part of a four-sprint course in CSE 1325 with guidance from Professor **George Fowler Rice**. The system demonstrates strong object-oriented design principles, including **inheritance, polymorphism, encapsulation**, and **file I/O**, while providing a **menu-driven interface** for managing students, media, and accounts.

---

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- **Java JDK 11 or higher**
- **Apache Ant** (optional, if using `build.xml`) or your preferred IDE (Eclipse, IntelliJ, VS Code)

---

### Installing, Running, and Demo

Open a terminal and run the following commands:

```bash
# Clone the repository
git clone https://github.com/uta-nih-6584/Mavs-Online-Entertainment-System.git
cd Mavs-Online-Entertainment-System

# Compile all Java classes
javac *.java

# Run the main program
java Main

Once running, use the menu-driven interface to:
Add students and media
Play media
List students and media
Purchase points and manage accounts
Save or load MOES files
Here’s a sample session demonstrating the menu interface:

=== Mavs Online Entertainment System ===
Current File: moes_data.txt

1. Add Student
2. Add Media
3. List Students
4. List Media
5. Play Media
6. Buy Points
7. Save to File
8. Save As New File
9. Open File
10. New MOES File
0. Exit

Select an option: 1
Enter student name: Alice Johnson
Enter student ID: 100123
Enter student email: alice@uta.edu
Student added successfully!

Select an option: 2
Enter media title: The Little Shop of Horrors
Enter media URL: https://publicdomainmovie.net/movie/the-little-shop-of-horrors-0
Enter media points: 5
Media added successfully!

Select an option: 5
Select a student by number: 1
Select media by number: 1
Playing The Little Shop of Horrors (https://publicdomainmovie.net/movie/the-little-shop-of-horrors-0)



### Running Tests

To verify the functionality of the system, run the regression tests for the core classes. These tests ensure correct implementation of saving/loading, account creation, media playback, and other core functionality.

Example commands:

```bash
java TestMedia
java TestAccount
java TestStudent

---
```
### Running Tests


 To verify the functionality of the system, run the regression tests for the core classes. These tests ensure correct implementation of saving/loading, account creation, media playback, and other core functionality.

Example commands:

```bash
java TestMedia
java TestAccount
java TestStudent
```

### Built With
 This project was built using the following technologies:

- JavaCore programming language

- BufferedReader / BufferedWriter – File I/O for saving and loading data

- ArrayList – Collection framework for managing students and media

### Authors
- Najat Hussein: Main Developer
- UTA Professor George Fowler Rice: Project Mentor



