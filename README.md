

---

# TCL Scripting – VSD Workshop

## Overview

This repository contains materials, practice labs, and automation scripts developed as part of the VSD TCL Scripting Workshop.
The focus is on building strong TCL fundamentals and applying them in real-world digital design flows, including automating tasks for synthesis and timing analysis using tools like Yosys and OpenTimer.

---

## Learning Highlights

* Develop a solid understanding of TCL scripting
* Automate generation of design constraints from CSV and SDC formats for use in OpenTimer
* Integrate TCL with Yosys to perform RTL synthesis and memory block creation
* Carry out hierarchical design checks to identify missing or mismatched modules
* Extract and analyze QOR (Quality of Results) data such as WNS (Worst Negative Slack) and FEP (False Path Endpoints)


---

## Tools Used

* **TCL** – for scripting and automation
* **Yosys** – for RTL synthesis
* **OpenTimer** – for static timing analysis

---

## Key TCL Syntax Covered

| **TCL Command**                           | **Purpose**                                            |
| ----------------------------------------- | ------------------------------------------------------ |
| `set var value`                           | Store a value in a variable                            |
| `$var` or `${var}`                        | Retrieve the value stored in a variable                |
| `puts "text"`                             | Print text to the terminal with a newline              |
| `puts -nonewline "text"`                  | Print without adding a newline                         |
| `open filename mode`                      | Open a file (`"r"` read, `"w"` write, `"a"` append)    |
| `close fileHandle`                        | Close a file handle                                    |
| `gets fileHandle var`                     | Read a single line from a file into a variable         |
| `read fileHandle`                         | Read the entire contents of a file                     |
| `glob -dir path *.ext`                    | List files matching a given pattern                    |
| `foreach var list {}`                     | Loop through each element in a list                    |
| `proc name {args} {body}`                 | Create a new procedure with arguments                  |
| `return`                                  | Exit a procedure and optionally return a value         |
| `[expr {...}]`                            | Evaluate an expression                                 |
| `incr var ?amount?`                       | Increase a variable’s value by 1 or a specified amount |
| `lindex list index`                       | Get a specific element from a list                     |
| `llength list`                            | Get the number of elements in a list                   |
| `lsearch list pattern`                    | Find the index of an element in a list                 |
| `lappend list_var value`                  | Append a value to a list variable                      |
| `split string sep`                        | Convert a string into a list using a separator         |
| `join list sep`                           | Join a list into a single string with a separator      |
| `lsort -unique list`                      | Sort a list and remove duplicates                      |
| `regexp pattern string`                   | Test if a string matches a regular expression          |
| `regsub pattern string replacement`       | Replace text in a string matching a pattern            |
| `string match pattern string`             | Compare a string with a wildcard pattern               |
| `string map {pattern replacement} string` | Replace all occurrences of a pattern in a string       |
| `exec command`                            | Run a system shell command                             |
| `catch {script} resultVar`                | Run code and catch any errors                          |
| `exit`                                    | End script execution immediately                       |
| `source filename`                         | Execute another TCL script                             |
| `format formatStr args`                   | Format strings similar to C’s `printf`                 |
| `# comment`                               | Add a comment in the script                            |
| `array set arr {key val ...}`             | Initialize an associative array                        |
| `array get arr`                           | Retrieve all key-value pairs from an array             |
| `switch -- $var { case {...} }`           | Match a value to predefined cases                      |
| `file exists path`                        | Check if a file exists                                 |
| `file isdirectory path`                   | Check if a path is a directory                         |
| `file normalize path`                     | Get the absolute, normalized path                      |
| `file dirname path`                       | Get the parent directory of a path                     |
| `file tail path`                          | Get the filename from a path                           |
| `time {script} count`                     | Measure execution time of code                         |
| `lassign list var1 var2`                  | Assign elements of a list to variables                 |

---

## Acknowledgement

Special thanks to **Mr. Kunal Ghosh (VSD)** for his guidance and deep technical insights throughout this workshop.

---
