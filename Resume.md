%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{document}

\namesection{Gokil}{P}{%
  \href{mailto:gokilp25@gmail.com}{gokilp25@gmail.com} | 866.761.9938 | \href{https://www.linkedin.com/in/gokilp}{LinkedIn: Gokilp}
}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{KG College of Arts and \\ Science}

\descript{B.Sc. Computer Science}
\location{Expected 2024  July| CGPA: 81.63}
\sectionsep

\subsection{AMMA MATRIC HR SEC SCHOOL}
\descript{HSc - Computer Application}
\location{Grad May 2021| percentage 79.33}
\sectionsep
\subsection{AMMA MATRIC HR SEC SCHOOL}
\descript{SSLC}
\location{Grad May 2019| percentage 65.00}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links}  \\
GitHub:// \href{https://github.com/Gokilp}{\bf  Gokilp} \\
Linked In://  \href{https://www.linkedin.com/in/gokilp/}{\bf Gokilp} \\
Twitter://  \href{https://x.com/Gokilp_25}{\bf @Gokilp\_25} \\
 Hash node://  \href{https://gokilp.co/}{\bf Gokilp}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\section{Skills}

\subsection{Languages}
\textbullet{} C++ \textbullet{} Java \textbullet{} JavaScript \\
\textbullet{} HTML \textbullet{} CSS \textbullet{} MySQL

\vspace{1em} % Add some space after the section
\subsection{Tools and Technologies}
\vspace{0.2em}
\textbullet{} LINUX \textbullet{} GIT 
 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Tech profle 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Tech profile Link}

GitHub:// \href{https://github.com/Gokilp}{\bf  Gokilp} \\
Coding profile://\href{https://www.geeksforgeeks.org/user/gokil/}{\bf gokil} \\
\vspace{1em}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%    Area of Interest
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\section{Area of Interest } 
\subsection{Technical}
\textbullet{} Full Stack Web development \textbullet{} Block Chain \textbullet{} Artificial Intelligence \\
\vspace{1em} % Add some space after the section
\subsection{Non -Technical}
\vspace{0.2em}
\textbullet{} Designing \textbullet{} Networking \textbullet{} Content Creation

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%   Course Woe
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\section{ course WOrk}
\subsection{Undergraduate}
\textbullet{} Object Oriented Programming \\
\textbullet{} NPTEL Python for Data Science \\
\textbullet{} Java Programing \\
\textbullet{} C++  Programing \\




%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience}
\runsubsection{GirlScript Summer of Code}
\descript{| Open source  Contributor }
\location{May 2024 - Present }
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item  Flipkart clone open-source project  
 increasing codebase efficiency by \textbf{25 percentage} and engaging a community 
\item  Enhanced the user interface, resulting in an \textbf{85 percentage} improve  in visual appeal and user engagement.
\item Git for version control, managing code changes and\textbf{ collaborating effectively} with the development team.
\end{tightemize}
\sectionsep

\runsubsection{ Jwoc}
\descript{| Open source Contributor |
\descript{\href{https://drive.google.com/file/d/1Jc7P1G_j96CvxS8CT5sEWKV4rP8gnKEM/view?usp=sharing}{\bf Live Link}}}
\location{Jan 2024  – Feb 2024 | Remote}
\begin{tightemize}
\item  contributed to an \textbf{openpedia} project  open-source   increasing \textbf{codebase efficiency by 30 percentage}  
\item Revamped the user interface, achieving an\textbf{ 90 percentage increase} in visual appeal and user engagement.
\item Utilized Git to manage code changes and \textbf{facilitate seamless collaboration} within the development team.
\end{tightemize}
\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%    Projects
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{Amazon Clone}
\descript{\href{https://amazon-theta-gray.vercel.app/}{\bf Live Link}}
\descript{ HTML | CSS }
\begin{tightemize}
\item Enhanced the user interface, improving performance by 75 percentage.
\item Contributed to the \textbf{Open Source Peerlist Community}, furthering open-source development and \textbf{GSSoC} initiatives.
\item Git for version control, managing code changes and \textbf{collaborating effectively} with the development team.
\end{tightemize}
\sectionsep

\runsubsection{Weather }
\descript{\href{https://weather-app-two-mu-61.vercel.app/}{\bf Live Link}}
\descript{ HTML | Css | Java Script }
\begin{tightemize}
\item Enhanced the user interface, resulting in an \textbf{90 percentage improve} in visual
appeal and user engagement
\item Utilized a \textbf{public API} to display weather details on screen
\end{tightemize}
\sectionsep
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Achievement
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Achievement}

\textbullet{} Published the \href{https://www.amazon.in/7-Generation-memory-Googol-Gokil-ebook/dp/B0B74T279D/ref=sr_1_1?sr=8-1}{\textbf{7th Generation Memory Book}} on Amazon Kindle

\textbullet{} Co-authored the insightful publication 
\href{https://www.linkedin.com/feed/update/urn:li:activity:6944838457504456704/originTrackingId=FNO9BGfDRMOIeLtiqVPfNw%3D%3D}{\textbf{Average Student}} in association with the respected.\textbf{KG College of Arts and Science} \\

 \textbullet{}Actively participated and contributed valuable \href{https://www.linkedin.com/feed/update/urn:li:activity:7186056032618471425/}{\textbf{FOSSASIA Asia Primer}} Open Source Conference  Showcased commitment to continuous learning and development in open source\\

\textbullet{} \href{https://www.linkedin.com/feed/update/urn:li:activity:7054709760079663104/}{\textbf{EUPHORIA}} Quiz competition in \textbf{PSG College of Arts and Science}\\
\textbullet{} Teaching coding on \textbf{open source communities}
\sectionsep
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Organization
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Organization}
\runsubsection{Girl Script Summer of Code}
\descript{| Campus Ambassador|
\descript{\href{https://drive.google.com/file/d/1qMJ50FkA9s4XifTdWQYQKmexDbQLdbr3/view?usp=sharing}{\bf Live Link}}}
\location{May 2024 - Present}
\textbullet{}\textbf{ GirlScript Summer of Code} Campus Ambassador for a 
  \textbf{open Source   communities} , facilitating the dissemination of their solutions to a wider audience 
\sectionsep



\renewcommand\refname{\vskip -1.5em} % Couldn't get this working from the .cls file
\bibliographystyle{abbrev}
\bibliography{publications}
\nocite{*}

\end{minipage} 
\end{document}  \documentclass[]{article}
