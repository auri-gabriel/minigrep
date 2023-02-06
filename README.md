# minigrep

Note: This project is a guided project from The Rust Programming Language book. It aims to reinforce the concepts learned in the first 11 chapters of the book.

Minigrep is a command-line utility written in Rust that searches a file for a specified query and returns the matching lines. The user can choose to perform a case-sensitive or case-insensitive search.

## Usage

The user can run the utility from the command line by passing two arguments: the query and the file name, in that order. By default, the search is case-sensitive, but if the user sets the CASE_INSENSITIVE environment variable, the search will be case-insensitive.

## Example

graphql

$ minigrep query file.txt

This will search the file file.txt for the string query and return any lines that contain it.
