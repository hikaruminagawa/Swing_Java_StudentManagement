# Student Management System

This repository contains the source code for a simple Student Management System implemented in Java. The main class in this project is `MainFrame.java`.

## MainFrame.java

`MainFrame.java` extends `JFrame` and serves as the main window of the application. It contains the following features:

### Student and Course Management

The class maintains two lists, `students` and `courses`, which are used to store `Student` and `Course` objects respectively.

### GUI Components

The class contains several GUI components including:

- `studentComboBox`: A combo box that allows the user to select a student.
- `courseComboBox`: A combo box that allows the user to select a course.
- `studentDetailsTextArea`: A text area that displays the details of the selected student.
- `courseDetailsTextArea`: A text area that displays the details of the selected course.

### Event Handling

The class also includes an `ActionListener` for the `studentComboBox`. When a student is selected from the combo box, the `actionPerformed` method is called, which in turn calls the `displayStudentDetails` method to display the details of the selected student.

## How to Run

To run the application, compile and run the `MainFrame.java` file.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

