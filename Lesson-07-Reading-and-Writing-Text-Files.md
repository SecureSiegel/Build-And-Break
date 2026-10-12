# Lesson 07 - Reading and Writing Text Files

## Our goal

I will teach you how to read program data from a text file and save results to another text file.

## What I will teach

An `std::ifstream` reads from a file, and an `std::ofstream` writes to one. Opening a file can fail, so a program should check that the stream is ready before trying to use it. Input files need a format that both the program and a person can understand.

We will process records only when a complete record was read. Testing a stream before extracting a record can accidentally process an extra, incomplete record at the end of a file.

## Guided steps

1. Create `scores.txt` with a few lines. Put a first name, last name, and three scores on each line.
2. Include `<fstream>` and declare an input stream.
3. Open the file and check it. If it did not open, print a clear message and stop.
4. Read one complete record at a time. Calculate the total and average for each record.
5. Open an output file, check it, and write labeled results.
6. Close the files and open the output file in a text editor to check it.

## Practice

- Add a fourth score to every record and update the calculation.
- Write both the total and average to the output report.
- Rename the input file to test the error message for a missing file.

## Check for understanding

- What is the difference between `ifstream` and `ofstream`?
- Why do we check whether a file opened?
- Why should we avoid calculating a report from a partially read record?

## Source connection

`Feb2` practices file streams, and `Feb16` reads student records and writes a course report. The later projects use file input to fill arrays and structures. We will use reliable stream-state checks rather than copying fragile `while (fin)` patterns from some old examples.
