1. Summarize the project and what problem it was solving.

The CelsuiusTempeture project was simple C++ program designed to convert a temperature from Celsius to Fahrenheit. The goal was to practice core programming concepts such as input handling, arithmetic
operations and output formatting. This project solved the basic problem of allowing a user to enter
a Celsius value and receive the correct Fahrenheit equivalent, demonstarting how user input can be
processed and transformed through logic in program.

2. What did you do particularly well?

I handled the filereading and file writing logic cleanly and correctly. The program opened the
input file read each city and temperature pair applied the conversion formula and worte the results
to a new file in a clear, organized format. I also made sure the file streams were opened and closed
properly whihc is crucial for preventing data loss or file-locking issues. Overall the structure
of the code made the dlow easy to follow.

3. Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
There are several enhancements that would stregthen the program:

- input validation: Currently the program assumes the input file is perfectly formatted. Adding
checks for missing values, invalid triggers or unreadable files would make the program more robust.
- Error handling: Using if(!file) checks or try/catch blocks would prevent crashes and allow kthe program to fail gracefully.
- Modular functions: MOving the conversion logic and file processing steps into seprate functions
would improve readability and make the code easier to maintain or expand.
- Dynaic file paths: Allowing the user to specify the input/output file names would make the program more flexible.

These improvements would makre the program more reliable, secure, and adaptable for real-world use where input data is not always perfect.

4. Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?

The most challenging part was correctly readinf pairs of values (city name + temperature) from the file and ensuring the loop is processed all six entries with errors. I overcame this by reviewing examples of file-stream usages, testing different input formats and using Visual Studio's debugger to verify tha variables were being read correctly. 

The resources that were added to my support network were:
- C++ file-strea, documentaiton
- STack Overflow discussions on ifstream and ofstream
- Visual Studios debugging tools
- Course examples and lecture notes

These resources helped me understadn how to work with external files and avoid common pitfalls like incorrect stream modes or forgetting to close files.

5. What skills from this project will be particularly transferable to other projects or course work?

This project stregthened several skills like:
- Reading and writting files in C++
- Parsing structured text data
- Applying methematical transformation to input data
- Debugging file-handling issues
- Structuirng code for clarity and maintainability

These skills will be essential in later courses especially when integrating C++ with Python working with larger datasets or building programs that rely on external configuration files.

6. How did you make this program maintainable, readable, and adaptable?

I used clear variable names, straightfoward logic and consisten formatting to make the program easy to understand. The code followed a simple sequence: Open file then read data, then convert to write output and lastly close file. The linear structure makes futures modifications easy, such as adding more cities, supporting different file formats, or expanding the program to handle errors. By keeping the code clean and avoiding unnecesary complexity, I ensured that the program can be adapted or extended without major restructuring.
