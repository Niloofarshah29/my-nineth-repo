# my-nineth-repo
my testing
fro PyPDF2 import PdfMerger

merge = PdfMerger()
files = ["file1.pdf", "file2.pdf"]

form pdf in files:
    merger.append(pdf)

merger.write("merged.pdf")
merger.close()
print("PDFs merged into merged.pdf")
