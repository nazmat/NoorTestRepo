# FancyCat

## Section 1 — Command Description

### What the tool does

FancyCat is a Node.js command that displays the contents of a text file and counts the number of lines in the file.

It combines the basic idea of the `cat` command with a line-counting feature.

### How to run it

First, make sure you are in the folder containing `fancyCat.js`.

Run:

node fancyCat.js example.txt

The command takes the filename as an argument.

For example:

node fancyCat.js example.txt

The program displays the contents of the file and then displays the line count.

### What commands/concepts it combines

FancyCat combines:

- The idea of the `cat` command, which displays file contents.
- A line-counting feature that counts the lines in the file.

The Node.js program uses `process.argv` to receive the filename from the command line and the `fs` module to read the file.

---

## Section 2 — AI-Assisted Programming

### What I asked AI

I asked AI questions about testing and debugging, including:

- "What are some test cases I should use for this command?"
- "What edge cases could cause this program to fail?"
- "Why is my program not producing the expected output?"

### Where AI helped

AI helped me identify test scenarios and possible edge cases.

For example, AI suggested testing:

1. A normal text file with multiple lines.
2. An empty file.
3. A file that does not exist.
4. A file containing only one line.

These tests helped me think about how my command behaves with different inputs.

### Where I had to think independently

I had to create and run the test files myself and compare the expected output with the actual output.

I also had to decide whether the output from my program matched the requirements of the assignment and make changes to my code based on my testing.

### What AI got wrong or missed

AI initially suggested some concepts that I had not learned yet, such as more advanced error-handling techniques.

I decided to keep my implementation simple and use concepts that I had already studied in class.

This helped me focus on understanding my own code rather than adding code that I did not understand.

---

## Example

Command:

node fancyCat.js example.txt

Example output:

Hello World
This is my test file.
I am learning Node.js.
Line count: 3
