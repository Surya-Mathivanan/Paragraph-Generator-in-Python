# Paragraph-Generator-in-Python
This repository contains a Python script that generates random paragraphs by selecting characters from a predefined set of alphabets and spaces. The number of rows in the paragraph can be specified by the user.
## How It Works
  - Input: The user specifies the number of rows for the generated paragraph.
  - Random Character Generation: Each row consists of 70 randomly selected characters from the string " abcd efgh ijkl mnop qrst uvwx yz".
  - Output: The generated text is saved in the file lorem_in_python/text.txt.
## Requirements
  - Python 3.x
## File Structure
```bash
  random-paragraph-generator/       # Root directory of your project
  ├── lorem_in_python/              # Folder where the output file will be saved
  │   └── text.txt                  # Output file generated by the script
  ├── random_paragraph_generator.py # Main Python script to generate random paragraphs
  └── README.md                     # Documentation file describing the project

```
## Example
  - If you input 3 as the number of rows, the text.txt file might look like this:
  ```bash
         abcd efgh ijkl mnop qrst uvwx yzabcd efghij klmnop qrs
         tuvwx yza bcd efghi jklmn opq rst uvwx yz abcd efghij
         klm nopqrs tuvwx yz abcd ef ghi jklmno pq rstuvwx yz
```
## Contribution
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and create a pull request.

