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
\lastupdated

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
\location{Grad May 2018| percentage 65.00}
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
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Tech profile Link}

GitHub:// \href{https://github.com/Gokilp}{\bf  Gokilp} \\
Coding profile://\href{https://www.geeksforgeeks.org/user/gokil/}{\bf gokil} \\
\vspace{1em}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%    Achievement
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\subsection{Achievement}

\textbullet{}\href{https://www.amazon.in/7-Generation-memory-Googol-Gokil-ebook/dp/B0B74T279D/ref=sr_1_1?sr=8-1} 
{\bf \textbf{7th Generation Memory Book}\textbf{ }} Published in Amazon Kindle 
\\
\textbullet{}\href{https://www.linkedin.com/feed/update/urn:li:activity:6944838457504456704/?originTrackingId=FNO9BGfDRMOIeLtiqVPfNw%3D%3D}{\bf Average Student}published associated  with  KG college of Arts and Science   \\
\textbullet{} \href{https://www.linkedin.com/feed/update/urn:li:activity:7186056032618471425/} 
{\bf \textbf{FOSSASIA Asia primer}\textbf{ }}open Source Conference \\
\textbullet{} \href{https://www.linkedin.com/feed/update/urn:li:activity:7054709760079663104/} 
{\bf \textbf{EUPHORIA }\textbf }Quizz competion in PSG college of Arts and Science
\\
\textbullet{} Teaching coding on open Source communities
\\
\sectionsep





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
\item Flipkart clone  project  Contribute open source  an front end project
\item  Enhanced the user interface, resulting in an 85 percentage improve  in visual appeal and user engagement.
\item Git for version control, managing code changes and collaborating effectively with the development team.
\end{tightemize}
\sectionsep

\runsubsection{ Jwoc}
\descript{| Open source Contributor }
\location{Jan 2024  – Feb 2024 | Remote}
\begin{tightemize}
\item openpedia project  Contribute open source  an front end project
\item Revamped the user interface, achieving an 90 percentage increase in visual appeal and user engagement.
\item Utilized Git to manage code changes and facilitate seamless collaboration within the development team.
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{Amazon Clone}
\descript{\href{https://github.com/Gokilp}{\bf Live Link}}
\descript{ HTML | Css }
\begin{tightemize}
\item Enhanced the user interface,improve 75 percentage better 
\item  Given Open Source Peerlist Community in Open Source and GSSoC Contributor Project
\item Git for version control, managing code changes and collaborating effectively with the development team.
\end{tightemize}

\sectionsep

\runsubsection{Cornell Phonetics Lab}
\descript{| Head Undergraduate Researcher}
\location{Mar 2012 – May 2013 | Ithaca, NY}
Led the development of \textbf{QuickTongue}, the first ever breakthrough tongue-controlled game with \textbf{\href{http://conf.ling.cornell.edu/~tilsen/}{Prof Sam Tilsen}} to aid in Linguistics research. 
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Awards} 
\begin{tabular}{rll}
2014	     & top 52/2500  & KPCB Engineering Fellow\\
2014	     & 1\textsuperscript{st}/50  & Microsoft Coding Competition, Cornell\\
2013	     & National  & Jump Trading Challenge Finalist\\
2013     & 7\textsuperscript{th}/120 & CS 3410 Cache Race Bot Tournament  \\
2012     & 2\textsuperscript{nd}/150 & CS 3110 Biannual Intra-Class Bot Tournament \\
2011     & National & Indian National Mathematics Olympiad (INMO) Finalist \\
\end{tabular}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Publications} 
\renewcommand\refname{\vskip -1.5em} % Couldn't get this working from the .cls file
\bibliographystyle{abbrv}
\bibliography{publications}
\nocite{*}

\end{minipage} 
\end{document}  \documentclass[]{article}
