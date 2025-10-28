# my-nineth-repo
my testing
fro PyPDF2 import PdfMerger

merger = PdfMerger()
files = ["file1.pdf", "file2.pdf"]

form pd in files:
    merger.append(pdf)

merger.write("merged.pdf")
merger.close()
print("PDFs merged into merged.pdf")
