# LaTeX Resume Template

This template is based on the resume format of Missouri University of Science and Technology's Career Opportunities and Employer Relations department. It is a simple, time tested resume format that removes some of COER's recommendations which I believe to be unnecessary (address, objective statement, etc.). Resumes written in this format are easily skimmed, important information stands out, and page real estate is maximized.

## Requirements

* `xelatex`
  * Used to build the PDF resume from the `.tex` file. `xelatex` often comes with the distribution of LaTeX you download.
* The LaTeX packages in `resume.tex`
  * These may come with your distribution of LaTeX. If not, download them individually.
* Cambria font
  * This should be downloaded on your system if it is not already, assuming you want to use this font. The Cambria font is included in this repo in case you need it.

## Usage (UNIX)

1. Clone this repository.
2. Make your changes to `resume.tex`. Rename the file as desired.
3. Build a PDF using the `build` script.
  ```bash
  ./build
  ```
  It will build the first `.tex` file it finds in the current directory.

## FAQs

* **Why is this a LaTeX template?** Because LaTeX is the least-worst way to write documents that I've come across. Once you understand this powerful markup language—which can be edited in your favorite text editor and built from the command line—you will never go back to using Google Docs or Microsoft Word.
