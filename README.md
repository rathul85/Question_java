\documentclass[11pt,a4paper]{article}
\usepackage[margin=2cm]{geometry}
\usepackage[T1]{fontenc}
\usepackage{booktabs}
\usepackage{tabularx}
\usepackage{array}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{fancyhdr}
\usepackage{xcolor}

\definecolor{hd}{RGB}{30,60,120}
\titleformat{\section}{\large\bfseries\color{hd}}{\thesection.}{0.5em}{}[\titlerule]
\titleformat{\subsection}{\normalsize\bfseries\color{hd}}{}{0em}{}
\setlength{\parindent}{0pt}
\setlength{\parskip}{4pt}
\renewcommand{\arraystretch}{1.25}
\pagestyle{fancy}
\fancyhf{}
\lhead{Software Engineering -- Question Paper}
\rhead{Total Marks: 40}
\cfoot{\thepage}

\newcommand{\Q}[2]{\textbf{Q#1.} #2}

\begin{document}

\begin{center}
{\LARGE\bfseries\color{hd} Software Engineering}\\[4pt]
{\large Question Paper Design (OBE-based, Bloom's Taxonomy, BNQF Standard)}
\end{center}

\begin{tabularx}{\textwidth}{@{}lX@{}}
\toprule
\textbf{Course} & Software Engineering \\
\textbf{Total Marks} & 40 \\
\textbf{Time} & 1 Hour \\
\textbf{Domain} & Cognitive (Bloom's Taxonomy, BNQF standard) \\
\textbf{Levels Used} & Knowledge (Remember), Understanding (Comprehend) \\
\bottomrule
\end{tabularx}

\section{Course Outcomes (CO)}
\begin{tabularx}{\textwidth}{@{}l X@{}}
\toprule
\textbf{CO} & \textbf{Statement} \\
\midrule
CO1 & Explain software engineering fundamentals and software process models (SDLC). \\
CO2 & Describe requirements engineering concepts and requirement types. \\
CO3 & Explain software design concepts, principles, architecture and UML models. \\
CO4 & Describe software testing and quality assurance techniques. \\
CO5 & Explain software maintenance and project management concepts. \\
\bottomrule
\end{tabularx}

\section{Question Paper Blueprint}
\begin{tabularx}{\textwidth}{@{}c l l c c c X@{}}
\toprule
\textbf{Sec.} & \textbf{Type} & \textbf{Questions} & \textbf{Marks Each} & \textbf{Total} & \textbf{Time} & \textbf{Bloom Level} \\
\midrule
A & MCQ & Q1--Q10 & 1 & 10 & 10 min & Knowledge \\
B & Short Answer & Q11--Q15 (all) & 4 & 20 & 25 min & Understanding \\
C & Descriptive & Q16--Q17 (all) & 5 & 10 & 25 min & Understanding \\
\midrule
 & & & & \textbf{40} & \textbf{60 min} & \\
\bottomrule
\end{tabularx}

\section{Questions}

\subsection*{Section A: Multiple Choice (10 $\times$ 1 = 10 marks)}

\Q{1}{In the Waterfall model, a phase can begin only when:}\\
\hspace*{1em}a) The customer approves the budget \quad b) The previous phase is completed\\
\hspace*{1em}c) Testing is finished \quad d) The code is deployed

\Q{2}{Which process model is driven mainly by risk analysis?}\\
\hspace*{1em}a) Waterfall \quad b) Spiral \quad c) Prototype \quad d) Big Bang

\Q{3}{``The system shall allow a student to register for a course'' is an example of a:}\\
\hspace*{1em}a) Non-functional requirement \quad b) Functional requirement\\
\hspace*{1em}c) Design constraint \quad d) Test case

\Q{4}{The formal document that records all software requirements is called:}\\
\hspace*{1em}a) SRS \quad b) SDD \quad c) UML \quad d) RTM

\Q{5}{A good software design should have:}\\
\hspace*{1em}a) High coupling, low cohesion \quad b) High coupling, high cohesion\\
\hspace*{1em}c) Low coupling, high cohesion \quad d) Low coupling, low cohesion

\Q{6}{Which UML diagram shows the static structure of a system (classes and relationships)?}\\
\hspace*{1em}a) Sequence diagram \quad b) Use case diagram \quad c) Class diagram \quad d) Activity diagram

\Q{7}{Testing of individual modules or functions in isolation is called:}\\
\hspace*{1em}a) Unit testing \quad b) Integration testing \quad c) System testing \quad d) Acceptance testing

\Q{8}{Black-box testing is based on:}\\
\hspace*{1em}a) Internal code structure \quad b) Specifications, without knowing internal code\\
\hspace*{1em}c) Database schema \quad d) Compiler output

\Q{9}{Which type of maintenance is performed to fix bugs found after delivery?}\\
\hspace*{1em}a) Corrective \quad b) Adaptive \quad c) Perfective \quad d) Preventive

\Q{10}{COCOMO is a technique used for:}\\
\hspace*{1em}a) Software testing \quad b) Software design\\
\hspace*{1em}c) Software cost estimation \quad d) Requirement elicitation

\subsection*{Section B: Short Answer (5 $\times$ 4 = 20 marks)}

\Q{11}{Explain two differences between the Waterfall model and the Agile model. \hfill (4)}

\Q{12}{Differentiate between functional and non-functional requirements. Give one example of each. \hfill (4)}

\Q{13}{Explain the terms \emph{coupling} and \emph{cohesion}. Why does good design aim for low coupling and high cohesion? \hfill (4)}

\Q{14}{Describe the difference between \emph{verification} and \emph{validation} with one example each. \hfill (4)}

\Q{15}{Briefly explain the four types of software maintenance. \hfill (4)}

\subsection*{Section C: Descriptive (2 $\times$ 5 = 10 marks)}

\Q{16}{Explain the three-tier (layered) architecture with a labelled diagram. Describe the role of each layer. \hfill (5)}

\Q{17}{Describe the main activities (phases) of the Software Development Life Cycle (SDLC). Explain the purpose of each phase. \hfill (5)}

\section{Mapping: Question -- CO -- Bloom -- BNQF}
\begin{tabularx}{\textwidth}{@{}c c c l X@{}}
\toprule
\textbf{Q} & \textbf{Marks} & \textbf{CO} & \textbf{Bloom Level} & \textbf{BNQF Cognitive Domain} \\
\midrule
Q1  & 1 & CO1 & Remember   & Knowledge \\
Q2  & 1 & CO1 & Remember   & Knowledge \\
Q3  & 1 & CO2 & Remember   & Knowledge \\
Q4  & 1 & CO2 & Remember   & Knowledge \\
Q5  & 1 & CO3 & Remember   & Knowledge \\
Q6  & 1 & CO3 & Remember   & Knowledge \\
Q7  & 1 & CO4 & Remember   & Knowledge \\
Q8  & 1 & CO4 & Remember   & Knowledge \\
Q9  & 1 & CO5 & Remember   & Knowledge \\
Q10 & 1 & CO5 & Remember   & Knowledge \\
\midrule
Q11 & 4 & CO1 & Understand & Understanding \\
Q12 & 4 & CO2 & Understand & Understanding \\
Q13 & 4 & CO3 & Understand & Understanding \\
Q14 & 4 & CO4 & Understand & Understanding \\
Q15 & 4 & CO5 & Understand & Understanding \\
Q16 & 5 & CO3 & Understand & Understanding \\
Q17 & 5 & CO1 & Understand & Understanding \\
\bottomrule
\end{tabularx}

\subsection*{CO-wise marks distribution}
\begin{tabularx}{\textwidth}{@{}l X c c@{}}
\toprule
\textbf{CO} & \textbf{Questions} & \textbf{Marks} & \textbf{\%} \\
\midrule
CO1 & Q1, Q2, Q11, Q17 & 11 & 27.5\% \\
CO2 & Q3, Q4, Q12 & 6 & 15\% \\
CO3 & Q5, Q6, Q13, Q16 & 11 & 27.5\% \\
CO4 & Q7, Q8, Q14 & 6 & 15\% \\
CO5 & Q9, Q10, Q15 & 6 & 15\% \\
\midrule
\textbf{Total} & & \textbf{40} & \textbf{100\%} \\
\bottomrule
\end{tabularx}

\subsection*{Cognitive level distribution}
\begin{tabularx}{\textwidth}{@{}X c c@{}}
\toprule
\textbf{Level} & \textbf{Marks} & \textbf{\%} \\
\midrule
Knowledge (Remember) & 10 & 25\% \\
Understanding (Comprehend) & 30 & 75\% \\
\bottomrule
\end{tabularx}

\section{Answer Key and Marking Scheme}

\textbf{Section A:} Q1-b, Q2-b, Q3-b, Q4-a, Q5-c, Q6-c, Q7-a, Q8-b, Q9-a, Q10-c

\textbf{Section B (4 marks each):}
\begin{itemize}[leftmargin=1.5em,itemsep=2pt]
\item \textbf{Q11:} 2 correct differences $\times$ 2 marks (e.g., sequential vs iterative; fixed vs changing requirements; late vs early customer feedback).
\item \textbf{Q12:} definition of each (1 + 1), correct example of each (1 + 1).
\item \textbf{Q13:} coupling explained (1), cohesion explained (1), reason: easier maintenance, reuse and testing (2).
\item \textbf{Q14:} verification = ``are we building the product right'' (1) with example (1); validation = ``are we building the right product'' (1) with example (1).
\item \textbf{Q15:} corrective, adaptive, perfective, preventive, 1 mark each with a one-line explanation.
\end{itemize}

\textbf{Section C (5 marks each):}
\begin{itemize}[leftmargin=1.5em,itemsep=2pt]
\item \textbf{Q16:} correct diagram with Presentation, Business Logic, Data layers (2); role of each layer (3).
\item \textbf{Q17:} five or more phases (planning, requirements, design, implementation, testing, deployment, maintenance) listed (2); purpose of each explained (3).
\end{itemize}

\end{document}
