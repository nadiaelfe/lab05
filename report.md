# Laboratory Work №5 — Tables

## Course
**Practical Scientific Writing**

## Author
**Nadia El Fe**

## Academic Year
2025–2026

---

## 1. Purpose of the Work
The purpose of this laboratory assignment is to learn and practice creating tables in LaTeX.  
The experiment includes using different column alignments, understanding row item mismatches, and applying the `\multicolumn` command to span multiple columns.

---

## 2. Tasks
1. Create a simple table with three columns.  
2. Experiment with the `l`, `c`, and `r` alignment options.  
3. Observe what happens when a row has too few or too many items.  
4. Apply the `\multicolumn` command to merge several columns.  

---

## 3. Tools and Environment
- **Operating System:** macOS  
- **Editor:** VS Code / Nano  
- **Compiler:** `pdflatex` (MacTeX 2025 distribution)  
- **Version Control:** Git + GitHub  
- **Conversion Tool:** Pandoc

---

## 4. Procedure

### 4.1 Simple Table Example
A three-column table was created with the column specification `{l l l}`.  
Result: all cells are **left-aligned** as expected.

![](image1.png)

### 4.2 Testing Different Alignments
Two additional tables were built with `{c c c}` and `{r r r}` specifications.  
Result:  
- The `c` alignment centered each cell’s content.  
- The `r` alignment right-justified all entries.

![](image2.png)

### 4.3 Too Few or Too Many Items
Rows with fewer or extra cells were tested.  
Result:  
- **Too few items:** missing cells are left empty.  
- **Too many items:** LaTeX displayed a warning  
  (“Extra alignment tab has been changed to \cr”).

  ![](image3.png)

### 4.4 Using `\multicolumn`
The `\multicolumn{3}{c}{Animals and Food}` command successfully merged three columns into one centered heading.

![](image4.png)

---

## 5. Results
All required experiments were performed successfully.  
Tables compiled without critical errors, and the output verified expected alignment and merging behavior.

| Experiment | Description | Result |
|-------------|--------------|---------|
| Alignment   | Tested `l`, `c`, `r` columns | Works correctly |
| Missing / Extra items | Checked behavior with uneven cells | As expected |
| `\multicolumn` | Spanned cells across columns | Works correctly |

---

## 6. Conclusion
The laboratory work confirmed the ability to design professional tables in LaTeX and understand alignment rules, spacing, and column-merging features.  
This knowledge forms the foundation for producing clean, publication-ready scientific documents.

---

## 7. References
1. *Practical Scientific Writing – Section 5: Tables*  
2. LaTeX Documentation: [https://www.latex-project.org/help/documentation/](https://www.latex-project.org/help/documentation/)

---

## 8. Repository Information
- **Full Repository:** [https://github.com/nadiaelfe/lab05](https://github.com/nadiaelfe/lab05)  
- **Release (to be added after upload):** _TBD_

---

© 2025 Nadia Ezzakate — Practical Scientific Writing, Moscow

