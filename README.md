# Ho-pay
Transfer money to another account
\documentclass[a4paper,10pt]{article}
\usepackage[margin=1cm]{geometry}
\usepackage{enumitem}
\setlist[itemize]{noitemsep, topsep=0pt}
\usepackage{hyperref}      % clickable links
\usepackage{xcolor}
\usepackage{graphicx}

% Optional: generate a QR code in the PDF (comment out if not available)
% Some LaTeX installations include 'qrcode'; if not, remove these lines.
\usepackage{qrcode}        

\begin{document}

\begin{center}
  {\LARGE\bfseries Your Full Name}\\[4pt]
  Phone: +91-XXXXXXXXXX \quad | \quad Email: your.email@example.com\\[3pt]
  Location: City, State \quad | \quad LinkedIn: \href{https://www.linkedin.com/in/yourprofile}{linkedin.com/in/yourprofile}\\[6pt]
  % --- Add your provided AI Studio link as a portfolio/coding link ---
  \textbf{Portfolio / Coding Projects:} \\
  \href{https://ai.studio/apps/drive/1ub8RIf_MMcOhuhW5UMujDlRVAPn4Qoub}{\texttt{ai.studio/apps/drive/1ub8RIf\_MMcOhuhW5UMujDlRVAPn4Qoub}}
\end{center}

\vspace{6pt}

\section*{Career Objective}
Motivated BCA student with internship experience at Magic Bus India Foundation. Strong foundational knowledge in programming and IT support. Looking for an opportunity to apply technical and analytical skills in a growing organization.

\section*{Education}
\textbf{Bachelor of Computer Applications (BCA)} \hfill Expected: 202X \\
College Name, University Name — City, State \\
CGPA/Percentage: X.X / XX\%

\section*{Internship Experience}
\textbf{Magic Bus India Foundation} — Intern \hfill Month Year – Month Year
\begin{itemize}
  \item Assisted in digital literacy and technology-based learning activities.
  \item Supported data entry, IT coordination and program facilitation tasks.
  \item Collaborated in organizing workshops focused on skill development.
\end{itemize}

\section*{Technical Skills}
\begin{itemize}
  \item \textbf{Programming:} C, C++, Python, Java (Basics)
  \item \textbf{Web:} HTML, CSS, JavaScript (Basics)
  \item \textbf{Database:} MySQL
  \item \textbf{Tools:} MS Office, VS Code, Git (Basics)
\end{itemize}

\section*{Academic Projects}
\textbf{Project Title} — Academic/Personal \hfill Year
\begin{itemize}
  \item Brief point explaining the system or purpose.
  \item Tech stack used and your contribution.
\end{itemize}

\section*{Certifications}
\begin{itemize}
  \item Certification Name — Platform/Institute, Year
\end{itemize}

\section*{Languages}
English — Fluent \\
Hindi — Fluent \\
Tamil — Intermediate

\section*{Portfolio (QR code)}
% Display a QR code linking to your portfolio. Comment out the next line if qrcode package is not available.
\qrcode[height=2.0cm]{https://ai.studio/apps/drive/1ub8RIf_MMcOhuhW5UMujDlRVAPn4Qoub}

% If qrcode doesn't work in your LaTeX environment, replace the above with:
% \begin{center}
%   \fbox{\parbox{0.9\linewidth}{\small Portfolio: \url{https://ai.studio/apps/drive/1ub8RIf_MMcOhuhW5UMujDlRVAPn4Qoub}}}
% \end{center}

\end{document}
