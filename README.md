# LaTeX Resume Template

This template is based on the resume format of Missouri University of Science and Technology's Career Opportunities and Employer Relations department. It is a simple, time tested resume format that removes some of COER's recommendations (address, objective statement, etc.) which I believe to be unnecessary. Resumes in this format are easily skimmed, important information stands out, and page real estate is maximized. 

Why is this a LaTeX template? Because once you understand this powerful markup language—which can be edited in your favorite text editor and built from the command line—you will never go back to using Google Docs or Microsoft Word. LaTeX documents look wack at first but give it time; you'll be glad you did.

## Requirements

* `xelatex` (Used to build our PDF document from the `.tex` file. This often comes with the distribution of LaTeX you download.)
* The LaTeX packages in `resume.tex` (These may come with your distribution of LaTeX. If not, download them individually.)

## Usage

1. Clone this repository.
2. Make your changes to `resume.tex`. Rename the file as desired.
3. Build a PDF using the `build` script.
  ```bash
  ./build
  ```
  It will build the first `.tex` file it finds in the current directory.
