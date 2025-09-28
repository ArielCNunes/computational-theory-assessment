# SHA-256 Hash Algorithm Implementation Assignment

This repository contains solutions to five problems focusing on different aspects of the Secure Hash Standard (SHA-256), as specified in NIST FIPS 180-4.

## Problems Overview

1. **Binary Words and Operations** - Implementation of SHA-256 logical functions
2. **Fractional Parts of Cube Roots** - Generation of SHA-256 constants from prime cube roots
3. **Padding** - Message padding according to SHA-256 specification
4. **Hashes** - Core SHA-256 hash computation function
5. **Passwords** - Password cracking and security analysis

## Dependencies

The implementation uses the following Python packages:
- `numpy` - For 32-bit integer operations and mathematical computations
- `jupyter` - For notebook environment
- Standard library modules as needed

## Running the Code

All code is contained within `problems.ipynb`. Each problem is clearly marked with level 2 headings and can be run independently. The notebook is designed to be executed from top to bottom, with each cell building upon previous results where necessary.

## Implementation Notes

- All SHA-256 functions strictly follow NIST FIPS 180-4 specification
- 32-bit integer operations are enforced using numpy data types
- Code includes comprehensive docstrings and comments
- Test cases verify correctness against known values
- Password analysis demonstrates common cryptographic vulnerabilities
