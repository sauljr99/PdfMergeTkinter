README.txt
PDF Merger - GUI App

A desktop app I made that lets you merge multiple PDF files together
through a simple window. You click the button, select as many PDFs
as you want using a file browser, then choose where to save the
merged file. No typing file names manually.

This was an upgrade from an earlier script that merged PDFs through
code. This version makes it way easier to use for anyone.

Language: Python
Libraries: Tkinter (for the GUI window and button),
           tkinter filedialog and messagebox (file browser pop-ups and alerts),
           PyPDF2 / PdfMerger (handles the actual merging of the PDF files)

Notes:
- Install PyPDF2 first by running: pip install PyPDF2
- Run the .py file and a small window with one button will open.
- You can select as many PDFs as you want at once in the file browser.
- The merged file gets saved wherever you choose in the save dialog.
