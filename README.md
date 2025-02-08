# 📊 LaTeX Equity Research Report & Cover Page

## 📝 Overview
This repository contains **two separate LaTeX projects**:
1. **Cover Page** - A standalone LaTeX project for the title page.
2. **Equity Research Report** - A structured LaTeX project for writing financial research.

Both projects should be managed **independently** in Overleaf, compiled separately, and then merged into a final PDF report.

---

## 📂 **Project Structure**

```bash
/coverpage/          → LaTeX files for the cover page (Upload as a separate Overleaf project)
    |-----> Cover_page.tex
/equityreport/       → LaTeX files for the research report (Upload as a separate Overleaf project)
    |-----> /Images/             → Folder to store report images and charts
    |-----> oup-contemporary.cls → DO NOT MODIFY unless absolutely necessary
    |-----> references.bst       → Required for bibliography, but IGNORE this file
    |-----> main.tex             → All of the report will be created in this file so focus on this one only really
```

---

## 🚀 **How to Use This Repository**
Follow these steps to generate the final equity research report.

### **1️⃣ Organize the Projects in Overleaf**
- **Upload `/coverpage/` as one Overleaf project.**
- **Upload `/equityreport/` as another Overleaf project.**
- Keep them as **separate projects** to avoid compilation errors.

### **2️⃣ Compile and Download PDFs**
- Compile each project **separately** in Overleaf.
- Download the resulting PDFs:
  - `coverpage.pdf`
  - `equityreport.pdf`

### **3️⃣ Merge PDFs into a Final Report**
Use **Adobe PDF Merger** (or any PDF combiner tool) to merge:

```bash
coverpage.pdf + equityreport.pdf → Final Report.pdf
```

---

## ⚠️ **Important Warnings**
### ❗ Project Synchronization  
- Keep **coverpage** and **equityreport** in **separate Overleaf projects**.
- Avoid merging them into one project—this will cause **compilation conflicts**.

### ❗ DO NOT EDIT `oup-contemporary.cls`
- This file **controls the document formatting** for the equity report.
- **Only modify if absolutely necessary.**
- There is one small section to modify but that is easy with the search feature on LaTeX

### ❗ IGNORE `references.bst`
- This is the bibliography style file.
- **DO NOT DELETE** it, but there is no need to modify it.

---

## 📂 **Managing Images**
- **Use the `/Images/` folder** inside `equityreport/` for all figures, charts, and tables.
- When adding images in LaTeX, use:
  ```latex
  \includegraphics[width=\textwidth]{Images/example-image.png}
  ```
- Keep images organized in /Images/ for easy access.

✅ Final Checklist

✔ Upload both projects to Overleaf separately
✔ Compile & download each PDF
✔ Use Adobe PDF Merger to combine the PDFs
✔ Do NOT edit oup-contemporary.cls
✔ Keep references.bst in the project without modifying it
✔ Store images in /Images/ for better organization
---

### **📌 Features in This README**
✅ **Clear setup instructions for Overleaf projects**  
✅ **Warnings about modifying `.cls` and `.bst` files**  
✅ **Step-by-step guide for compiling and merging PDFs**  
✅ **Best practices for handling images**  

Let me know if you need modifications! 🚀🔥


