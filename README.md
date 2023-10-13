

# College Registration System

This is a simple college registration system implemented in C++. The system allows you to add, update, and retrieve student records and module information.

## Features

- **Add Student Record:** You can add a new student record, including their details and module information. The system prompts you for the student number, name, and module details, and it stores this information in a text file.

- **Update Student Record:** Update existing student records. You can modify the details of a specific student by entering their student number, and the program updates the record in the text file.

- **Get Student Record:** Retrieve information about a specific student by their student number. The program searches for the student with the given student number and displays their details.

- **Get All Student Records:** View a list of all student records. The program reads the student records from the text file and displays them.

- **Add Module:** Add new module information to the system. You can add modules by providing their number, title, and level (e.g., UnderGrad/Grad). The module details are saved in a separate text file.

- **Get Module Details:** Retrieve details of a specific module by its module number. You can enter a module number, and the program will display the module's information.

- **Get All Module Details:** View a list of all available modules. The program reads the module information from the text file and displays them.

- **Update Module Information:** Update module information. You can modify the details of a specific module by entering its number, and the program updates the module record in the text file.

- **Find Student Marks:** Calculate and display the average marks and grade for a specific student. The program calculates the average marks based on the entered marks for each module and displays a corresponding grade.

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/swetamishra123/college-registration.git
```

2. Compile the C++ code:

```bash
g++ -o college_registration college_registration.cpp
```

3. Run the program:

```bash
./college_registration
```

4. Follow the on-screen menu to perform various actions on student records and module information. The program will provide prompts for input, and you can follow these prompts to interact with the system.

## Output

- The program provides output by displaying information on the console. When you perform actions like adding, updating, or retrieving records, the results are shown in the console.

- For student records, the program uses text files (`stdtRecord.txt` and `tempFile.txt`) to store and manage student information. The records are stored in a structured format in these files.

- For module information, the program uses a separate text file (`modRecord.txt`) to store module details.

## Contributors

- [swetamishra123](https://github.com/swetamishra123)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

You can use this section to give credit to any libraries or tutorials that you may have used or were inspired by during the development of this project.

## Questions or Issues

If you have any questions or encounter issues, please [open an issue](https://github.com/swetamishra123/college-registration/issues).

