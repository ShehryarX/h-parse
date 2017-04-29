# HParse
_An accurate résumé grader script written in Python 2.7._

## Abstract
HParse accepts a batch list of PDF files that it parses and grades accordingly to a predefined text file immideately. It systematically grades résumés and exports the results in a file, ```results.tex```.

## Installation
1. Install Python 2.7.
2. Ensure there is an environmental variable referencing its respective installation path.
3. Run ```it clone https://github.com/ShehryarX/h-parse/``` or download this repository as a zip and extract it in a directory.
4. ```cd h-parse/``` or if you downloaded it manually, ```cd path/to/directory/of/h-parse```.
5. ```python parseResume.py```.

## Usage
- To specify a single file, please input the final name and its extension; for example, ```sample.pdf```, or ```/batchsample/sample1.pdf/```.
- To specify a directory or batch list of resumes, simply specify the directory; for example, ```batchsample```.
- As aforementioned, results are exported to ```results.tex```. Open it up in a LATEX compiler and see the results.
- For searching degrees, enter the degree name, and when prompted to continue, enter ```Y``` or ```N```.

## To-do List
- [x] Add ```.pdf```, ```.doc```, ```.docx```, and ```.txt``` support.
- [x] Implement suffix tree searching for faster lookup ```O(log (n))```.
- [ ] Convert ```results.tex``` to ```results.pdf```.
- [ ] Allow more user flexibility.
