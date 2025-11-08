\documentclass{beamer}

% Theme and color
\usetheme{Madrid}
\usecolortheme{seahorse}

% Language and encoding
\usepackage[utf8]{inputenc}
\usepackage[russian, english]{babel}
\usepackage{booktabs} % For nicer tables

% Title info
\title{Laboratory Work №5 — Tables}
\subtitle{Practical Scientific Writing}
\author{Nadia Ezzakate}
\date{November 2025}

\begin{document}

% Title slide
\begin{frame}
    \titlepage
\end{frame}

% Purpose
\begin{frame}{Purpose of the Work}
Learn and practice creating tables in \LaTeX{}:
\begin{itemize}
    \item Use different column alignments (`l`, `c`, `r`)  
    \item Handle rows with too few or too many items  
    \item Apply the \texttt{\textbackslash multicolumn} command
\end{itemize}
\end{frame}

% Tasks
\begin{frame}{Tasks}
\begin{enumerate}
    \item Create a simple table with three columns
    \item Test `l`, `c`, `r` alignments
    \item Observe behavior with missing or extra items
    \item Apply \texttt{\textbackslash multicolumn} to merge columns
    \item Prepare report and presentation in Markdown and convert
\end{enumerate}
\end{frame}

% Tools
\begin{frame}{Tools and Environment}
\begin{itemize}
    \item Operating System: macOS  
    \item Editor: VS Code / Nano  
    \item Compiler: \texttt{pdflatex} (MacTeX 2025)  
    \item Version Control: Git + GitHub  
    \item Conversion Tool: Pandoc
\end{itemize}
\end{frame}

% Procedure - Simple Table
\begin{frame}{Procedure: Simple Table}
\begin{itemize}
    \item Created a three-column table: \texttt{\{l l l\}}  
    \item Result: all cells left-aligned
\end{itemize}
\end{frame}

% Procedure - Alignments
\begin{frame}{Procedure: Testing Different Alignments}
\begin{itemize}
    \item \texttt{\{c c c\}} → center-aligned  
    \item \texttt{\{r r r\}} → right-aligned  
    \item Each table compiled correctly and visually verified
\end{itemize}
\end{frame}

% Procedure - Missing / Extra Items
\begin{frame}{Procedure: Missing and Extra Items}
\begin{itemize}
    \item Too few items: missing cells left blank  
    \item Too many items: LaTeX warning ``Extra alignment tab has been changed to \textbackslash cr''
\end{itemize}
\end{frame}

% Procedure - Multicolumn
\begin{frame}{Procedure: Using \textbackslash multicolumn}
\begin{itemize}
    \item Command used: \texttt{\textbackslash multicolumn\{3\}\{c\}\{Animals and Food\}}  
    \item Result: merged three columns into one centered heading
\end{itemize}
\end{frame}

% Results Table
\begin{frame}{Results}
\begin{table}[h]
\centering
\begin{tabular}{lll}
\toprule
Experiment & Description & Result \\
\midrule
Alignment & Tested `l`, `c`, `r` columns & Works correctly \\
Missing / Extra Items & Checked behavior with uneven cells & As expected \\
\texttt{\textbackslash multicolumn} & Spanned cells across columns & Works correctly \\
\bottomrule
\end{tabular}
\end{table}
\end{frame}

% Conclusion
\begin{frame}{Conclusion}
\begin{itemize}
    \item Successfully designed professional tables in \LaTeX  
    \item Learned alignment rules, spacing, and column merging  
    \item Foundation for clean, publication-ready scientific documents
\end{itemize}
\end{frame}

% References
\begin{frame}{References}
\begin{enumerate}
    \item \emph{Practical Scientific Writing – Section 5: Tables}  
    \item LaTeX Documentation: \url{https://www.latex-project.org/help/documentation/}
\end{enumerate}
\end{frame}

% Repository Info
\begin{frame}{Repository Information}
\begin{itemize}
    \item Full Repository: \url{https://github.com/nadiaelfe/lab05}  
    \item Release (to be added after upload): \emph{TBD}
\end{itemize}
\end{frame}

\end{document}

