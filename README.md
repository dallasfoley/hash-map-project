
# Hash Table Project README
## Overview
The Hash Table Project for CSE 331 FS23, is a comprehensive implementation of a hash table in Python. This project demonstrates the use of hash tables for efficient data storage and retrieval, as well as custom applications such as plagiarism detection in songs.

## Features
HashNode: Basic building block of the hash table, storing key, value, and deletion status.<br />
HashTable: Core class implementing the hash table with dynamic resizing and collision handling capabilities.<br />
Plagiarism Detection: A unique application using the hash table to detect similarities between songs, which can be used to identify potential plagiarism.<br />
## Usage
HashNode: Represents a single data point within the hash table.<br />
HashTable Operations:<br />
Insertion (__setitem__): Add key-value pairs to the hash table.<br />
Retrieval (__getitem__): Fetch value based on key.<br />
Deletion (__delitem__): Remove a key-value pair from the hash table.<br />
Resizing (_grow): Automatically resize the hash table to maintain efficiency.<br />
Utility Functions:<br />
keys: Returns a list of keys in the hash table.<br />
values: Returns a list of values in the hash table.<br />
items: Returns key-value pairs as a list of tuples.<br />
clear: Clears all entries in the hash table.<br />
Plagiarism Detection (is_plagiarism): Analyze two songs to determine if there is a significant similarity based on a given threshold.<br />
## Installation
Requires Python 3.7 or newer. No external dependencies are needed.

## Dependencies
Python 3.7+
## Contributors
Project developed as part of CSE 331 FS23
Instructor: Onsay
## Author
Dallas Foley
