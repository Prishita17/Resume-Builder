# Resume-Builder
Web based editor to create Resume in a customizable template  


**Note** : Click the "VIEW INSTRUCTIONS" button in the editor to read usage instructions.

#### Features
- Resume content can be edited just like a normal document editor (cut,copy,undo etc).
- Entire sections can be added, reordered, removed just by cut,copy,pasting method.
- Section visibility can be toggled while retaining the content.
- Options provided in the left panel to modify the template and formatting.
- Sub-points can be added with various bullet styles and adjustable indentation.
- Script provided to merge multiple pages and compress the PDF.

#### Using the merge & compress script
- You must be able to run python file on your system for this.
- Save the individual pages in PDF format with name ```1.pdf``` , ```2.pdf```
- Download the ```compress_pdf.py``` file and open it in a text editor.
- Set the following variables :
	- ```dir_path``` : Directory path where you saved the PDFs for individual page
	- ```num_of_pages``` : Number of files to merge (i.e. pages in your Resume)
	- ```out_file``` : Name of output file
- Run this python file.
- Note: As this creates a new PDF file, you may have to see permission settings or run with sudo on terminal.


Screenshot of the project

Login Page

<img width="550" height="337" alt="Screenshot 2026-01-20 at 10 31 56 PM" src="https://github.com/user-attachments/assets/bd566792-5356-488d-9f62-fcee77bfd9ea" />

Create Resume

<img width="1425" height="780" alt="Screenshot 2026-01-20 at 10 13 41 PM" src="https://github.com/user-attachments/assets/834f90ea-cfb5-4092-bfb8-3e6af743e80d" />

<img width="1430" height="788" alt="Screenshot 2026-01-20 at 10 13 49 PM" src="https://github.com/user-attachments/assets/9c4c5c9f-af91-4a73-accc-5db2137380cc" />

Output of Resume

<img width="523" height="517" alt="Screenshot 2026-01-20 at 10 32 01 PM" src="https://github.com/user-attachments/assets/67b9f406-d1b1-4c29-9ba6-8e17a4513fdc" />


<img width="903" height="580" alt="Screenshot 2026-01-20 at 10 32 19 PM" src="https://github.com/user-attachments/assets/cfe06781-f72c-4267-b3ef-b4f76a721307" />


Resume gets stored in databse, so you can visit later

<img width="462" height="472" alt="Screenshot 2026-01-20 at 10 32 08 PM" src="https://github.com/user-attachments/assets/0b5139f9-6d2d-4743-a134-38487e994a8d" />




## Acknowledgement

This project was developed for learning purposes and is inspired by open-source
e-commerce projects available on GitHub




**Note** : Use Google Chrome
         : and better if open on desktop
