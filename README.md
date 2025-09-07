# Internship-Certificate

[Internship Certificate_AyushTiwari.pdf](https://github.com/user-attachments/files/21995068/Internship.Certificate_AyushTiwari.pdf)





%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.3 (22/9/2018)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% v1.3 author:
% Zachary Taylor
%
% v1.3 repository:
% https://github.com/ZDTaylor/Deedy-Resume-Reversed
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
% 1. Add various styling and section options and allow for multiple pages smoothly.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.3:
% 1. Removed MacFonts version as I have no desire to maintain it nor access to macOS
% 2. Switched column ordering
% 3. Changed font styles/colors for easier human readability
% 4. Added, removed, and rearranged sections to reflect my own experience
% 5. Hid last updated
%
% v1.2:
% 1. Added publications in place of societies.
% 2. Collapsed a portion of education.
% 3. Fixed a bug with alignment of overflowing long last updated dates on the top right.
%
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
% 1. Overflows onto second page if any column's contents are more than the vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-reversed}
\usepackage{fancyhdr}

\pagestyle{fancy}
\fancyhf{}

\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% \lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Ayush Tiwari}{ %\urlstyle{same}\href{http://example.com}{example.com}| \href{http://example2.co}{example2.co}\\
\href{mailto:john.doe@example.com}{ayushtiwari7473@gmail.com} | \href{tel:11111111111}{7415497473}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.60\textwidth}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience}
\runsubsection{Ninjafram Services Pvt. Ltd.}
\descript{| Android Developer + Team Lead }
\location{March 2024 – Current | Remote}
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Developed Android features using Kotlin Coroutines}, Dependency Injection}, and GitHub Hooks to automate code checks (e.g., detecting unwanted imports like ).
\item Led a 7-member contract-based development team for a high-impact startup app.
\item Built and launched two interconnected Android apps Poultrywala Trader} and Poultrywala Contractor}, enabling farmers, traders, and businesses to seamlessly connect.
\item Designed scalable end-to-end architecture using Kotlin, Coroutines, Dependency Injection, DSL, Firebase, and Clean Architecture.

\end{tightemize}
\sectionsep

\runsubsection{Dollop Infotech Pvt. Ltd.}
\descript{|  Android Developer  }
\location{March 2024 – May 2025 | Indore,India}
\begin{tightemize}
\item  Designed and developed scalable Android applications using \textbf{Kotlin}, \textbf{MVVM}, and \textbf{Coroutines}.
\item Automated build and deployment pipelines with \textbf{GitHub Hooks}, \textbf{CI/CD}, and \textbf{Jenkins}, reducing manual errors and release cycle times.
\item Implemented a secure authentication system and custom shell scripts to enforce coding standards (e.g., removing unwanted imports).
\item Built a robust push-notification system using \textbf{Firebase Cloud Messaging}, improving user retention by 25\%.
\item Collaborated with senior developers to adopt \textbf{Docker} and DevOps workflows within Android projects.

\end{tightemize}
\sectionsep

\runsubsection{Dollop Infotech Pvt. Ltd.}
\descript{| Intern }
\location{Jan 2024 – March 2024 |Location- Indore, India \newline Project  |   Vestragrow,OpenNetwork}
\begin{tightemize}
\item Interacted with clients to assess their problems and implement a solution in an efficient, friendly manner.
\item Integrated Retrofit, OkHttp, Gson, and Room Database for efficient API handling and local data persistence.
\item Customized Android Gallery APIs for improved media handling
\item Reduced runtime dependencies by 10% with custom DSL & sealed class usage.
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PROJECTS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{WhatsApp Clone}
\descript{| Jetpack Compose}
\begin{tightemize}
\item Implemented a WhatsApp-like chat app UI fully in Jetpack Compose, demonstrating proficiency in modern Android UI toolkits
\item Applied Hilt for dependency injection, Coroutines for async tasks, and Room for local data persistence
\end{tightemize}
\sectionsep

\runsubsection{Linux Project}
\descript{|Linux Clock with SMTP Alert System}
\begin{tightemize}
\item Developed a Linux-based clock utility with automation features. Integrated an SMTP server to send email alerts when shell script build processes failed, ensuring proactive monitoring and quick resolution..
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Research}
% \runsubsection{Cornell Robot Learning Lab}
% \descript{| Researcher}
% \location{Jan 2014 – Jan 2015 | Ithaca, NY}
% Worked with \textbf{\href{http://www.cs.cornell.edu/~ashesh/}{Ashesh Jain}} and \textbf{\href{http://www.cs.cornell.edu/~asaxena/}{Prof Ashutosh Saxena}} to create \textbf{PlanIt}, a tool which  learns from large scale user preference feedback to plan robot trajectories in human environments.
% \sectionsep

% \runsubsection{Cornell Phonetics Lab}
% \descript{| Head Undergraduate Researcher}
% \location{Mar 2012 – May 2013 | Ithaca, NY}
% Led the development of \textbf{QuickTongue}, the first ever breakthrough tongue-controlled game with \textbf{\href{http://conf.ling.cornell.edu/~tilsen/}{Prof Sam Tilsen}} to aid in Linguistics research.
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COMMUNITY SERVICE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Community Service}

% \begin{tabular}{rll}
% 2013 -- 2018    & Tennessee     & St. Baldrick's Foundation\\
% 2014 -- 2017	& Tennessee     & American Cancer Society's Hope Lodge\\
% 2013 -- 2015    & Tennessee     & Habitat for Humanity\\
% 2011 -- 2015    & Tennessee     & Special Olympics\\
% \end{tabular}
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SOCIETIES
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Societies}

% \begin{tabular}{rll}
% 2018 -- 2018    & National      & Association of Computing Machinery (ACM)\\
% 2017 -- 2019	& National      & Scrum Alliance Certified ScrumMaster\\
% 2015 -- 2019    & University    & Shackouls Honors College\\
% \end{tabular}
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Awards}
% \begin{tabular}{rll}
% 2015        & 99\textsuperscript{th} percentile & National Merit Scholarship Finalist\\
% \end{tabular}
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Publications}
% \renewcommand\refname{\vskip -1.5cm} % Couldn't get this working from the .cls file
% \bibliographystyle{abbrv}
% \bibliography{publications}
% \nocite{*}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage}
\hfill
\begin{minipage}[t]{0.33\textwidth}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education}

\subsection{Jawaharlal Nehru College Of Technology Rewa}
\descript{Bachelor of Technology in Computer Science }
\location{Expected Dec 2026 | Rewa (M.P), India}
% College of Engineering \\
\location{ CGPA : 7}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\subsection{Programming}
\location{3+ years:}
Java ,Kotlin,C ,YAML,Sql \\
\location{1.8+ years:}
 Android ,JETPACK Compose ,FireBase,DI, Coroutines,XMl,Json,Retrofit \\
\location{6+ Month:}
 Linux ,Shell Scripting,Docker,Aws,Jenkins,CI/CD,Terraform, GitHub Actions \\
 \location{Tools}
  Git,Github,GitLab,Trivy,Sonarqube,
\sectionsep

\subsection{Technology}
 Robotic \textbullet{} AWS \textbullet{} Linux \\
 Windows \textbullet{} ROS \\
 N8n \textbullet{} Automation \\
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\subsection{Achievements}
227 plus contributions across\n
across 70+ repositories in the last year.\n
Published open-source projects\n
RecyclerView with Motion Layout
\sectionsep



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Societies
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Technical Content Creator }
Co-founded and managed a technical Instagram page focused on daily posts tech updates, and project showcases.\\
Grew engagement by sharing practical coding tips, Android development insights, and collaborative projects.\\

\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links}
Github:// \href{https://github.com/}{\bf mrAyush1804} \\
LinkedIn://  \href{https://www.linkedin.com/}{\bf ayush-tiwari-59b179296}
\sectionsep

\end{minipage}
\end{document}  \documentclass[]{article}
