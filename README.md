# Malware Analysis Tool

This tool provides an in-depth analysis of files to help identify potential malware. It calculates entropy, detects file types, and searches for potentially malicious patterns. The tool supports multiple file formats, including Portable Executable (PE), Executable and Linkable Format (ELF), Java Archive (JAR), scripts, and Office documents.

## Features

- **File Type Detection**: Automatically detects the type of file being analyzed.
- **Entropy Calculation**: Computes the entropy of files to assess their randomness and potential for obfuscation.
- **Heuristic Analysis**: Checks script files for suspicious keywords and patterns that may indicate malicious behavior.
- **SHA-256 Hash Calculation**: Generates the SHA-256 hash of the file for further analysis or comparison with known malware hashes.
- **File Size Reporting**: Provides the size of the file in bytes for context during analysis.

## Installation

1. Ensure you have [Go](https://golang.org/doc/install) installed on your system.
2. Clone the repository:

   ```bash
   git clone https://github.com/14mb1v45h/cyberspace060.git
   cd cyberspace060
3. Build the tool :
   **go build**
4. Run the tool with the following command:
   **go run malware_analysis_tool.go <path_to_file>**

