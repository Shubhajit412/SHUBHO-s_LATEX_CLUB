# LaTeX Preamble Collection for Academic Use

This repository contains a collection of LaTeX preamble files created for academic purposes. These preambles aim to provide a consistent and efficient starting point for writing academic documents, such as papers, theses, and reports.

**Usage:**

These preamble files are designed to be easily incorporated into your LaTeX projects. To use a specific preamble file, simply include the `\input{}` command at the beginning of your main LaTeX document.

**Intended Use and Distribution:**

These preamble files are intended for academic use. You are free to use, modify, and distribute these files as long as this intended academic purpose is maintained. Please acknowledge the source if you find these files helpful in your own work.

**Technical Instructions:**

To effectively use these preamble files in your LaTeX project, please follow these technical guidelines:

1.  **Include Preamble:** The very first line of your main LaTeX document that utilizes one of these preambles should be the `\input{}` command, followed by the name of the preamble file you wish to use. This should be followed by either additional LaTeX commands specific to your document or directly by the `\begin{document}` command.

    ```latex
    \input{preamble.tex} % Replace with the actual preamble file name
    % Add any other document-specific packages or settings here if needed
    \begin{document}
    % Your main document content goes here
    \end{document}
    ```

2.  **Working Directory:** Ensure that all the files relevant to your LaTeX project, including your main `.tex` file and the specific preamble file you are using, are located within the **same working directory**. This simplifies the compilation process and ensures that LaTeX can find all necessary files.

3.  **Image Directory:** By default, the repository assumes that all images used in your LaTeX project will be stored in a subdirectory named `Images` within your main working directory. Therefore, if your project includes any images, you **must create an `Images` directory** in the same location as your main `.tex` file and place all your image files within this `Images` directory. You can then include images in your document using commands like `\includegraphics{Images/your_image.png}`.

    ```
    /project-root  
    ├── main.tex               # Your main LaTeX document  
    ├── preamble_file.tex      # The preamble file  
    ├── Images/                # Directory for images  
    │      ├── figure1.png  
    │      └── diagram.pdf  
    ├── chapter1.tex
    └── bibliography.bib       # (if using BibTeX)   
    ```

**Available Preamble Files:**

( *You would list the names of your preamble files here. For example: * )

* `preamble-I.tex`: A master preamble with almost all necessary requirements for math and CS majors.
* `preamble-II.tex`: A preamble tailored for writing mini articles/reports with abstract, for projects.


**Contributing:**

If you have created useful preamble files that you would like to share, feel free to contribute by submitting a pull request. Please ensure that your preamble files are well-documented and adhere to the intended academic purpose.

To contribute:
    1.  Fork the repository.\\
    2.  Create a new branch.
    3.  Add your changes and commit them.
    4.  Submit a pull request.

**License:**

This repository and its contents are intended for academic use and can be distributed under the condition that this intention remains intact.

**Notes:**

If you encounter any issues or have suggestions for improvement, feel free to open an issue.
Happy TeXing!
