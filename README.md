%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sbrygrist/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article} % Restored to standard 11pt font for full-page look

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5} % Added for GitHub & Live Link symbols
\usepackage{lmodern} % Added for the beautiful crisp Serif Font matching the reference
\input{glyphtounicode}


%----------FONT OPTIONS----------
% Ensure Latin Modern Roman is used for the classic LaTeX serif look
\pdfgentounicode=1

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Slightly extended margins to fit new sections while keeping 11pt font size
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.0in}
\addtolength{\topmargin}{-0.65in} % Perfect top margin
\addtolength{\textheight}{1.4in} % Perfect printable height

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting (balanced spacing to fill the page height)
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands (standard spacing)
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-4pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-4pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-8pt}
}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-8pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Namra Sabhaya} \\ \vspace{2pt}
    \small \href{mailto:namrasabhaya@gmail.com}{namrasabhaya@gmail.com} $|$ +91 9913300755 \\ \vspace{2pt}
    \small 
    \href{https://github.com/namra-sabhaya}{\textbf{GitHub}} $|$ 
    \href{https://www.linkedin.com/in/namra-sabhaya-85ab60385/}{\textbf{LinkedIn}} $|$ 
    \href{https://codeforces.com/profile/namra_sabhaya}{\textbf{Codeforces}} $|$ 
    \href{https://leetcode.com/u/NamraSabhaya/}{\textbf{LeetCode}} $|$ 
    \href{https://www.codechef.com/users/namra_sabhaya}{\textbf{CodeChef}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Nirma University}{Ahmedabad, Gujarat}
      {Bachelor of Technology in Computer Science and Engineering (Current CGPA: 8.27 / 10.00)}{July 2024 -- May 2027}
    \resumeSubheading
      {Modi School}{Surat, Gujarat}
      {Higher Secondary Certificate (HSC) -- GSEB Science A-Group (10th: 96\%, JEE Main: 98.44\%ile)}{March 2024}
  \resumeSubHeadingListEnd


%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: C++, C, Python, Java, JavaScript, SQL} \\
     \textbf{Web Technologies}{: React.js, Node.js, Express.js, FastAPI, Tailwind CSS, HTML5, CSS3} \\
     \textbf{Databases \& Tools}{: MongoDB, MySQL, PostgreSQL, Git, GitHub, AWS, Linux} \\
     \textbf{Coursework}{: Data Structures \& Algorithms, Operating Systems, Database Management Systems, Computer Networks, Object-Oriented Programming, Computer Architecture}
    }}
 \end{itemize}


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \item
      \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
        \small\textbf{Client Finance Manager} $|$ \emph{React.js, Node.js, Express.js, MongoDB, Vite} & 
        \href{https://github.com/namra-sabhaya/Client-Finance-Manager}{\faGithub}
      \end{tabular*}\vspace{-8pt}
      \resumeItemListStart
        \resumeItem{Build a full-stack MERN application enabling financial advisors to track client net worth, income sources, and liabilities through an embedded-document client schema.}
        \resumeItem{Implement automated Old vs. New Indian Income Tax regime comparison logic to help advisors identify the more tax-efficient option for each client.}
        \resumeItem{Design RESTful API endpoints for managing FDs, SIPs, stocks, and loans, deployed as a serverless Vercel function alongside the frontend.}
      \resumeItemListEnd

      \item
      \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
        \small\textbf{MediCare HMS -- Hospital Management System} $|$ \emph{React.js, Node.js, Express.js, MongoDB, JWT} & 
        \href{https://github.com/namra-sabhaya/hospital-management-system}{\faGithub}
      \end{tabular*}\vspace{-8pt}
      \resumeItemListStart
        \resumeItem{Develop a full-stack hospital management system with JWT-based role authentication for admin, receptionist, and doctor accounts.}
        \resumeItem{Engineer an appointment booking flow that prevents doctor double-booking using a compound unique MongoDB index backed by application-level slot validation.}
        \resumeItem{Build an admin analytics dashboard computing patient/doctor counts, daily revenue, and top doctors using MongoDB aggregation pipelines.}
      \resumeItemListEnd

      \item
      \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
        \small\textbf{Smart Trip Planner} $|$ \emph{Python, Machine Learning, FastAPI, HTML/CSS/JS} & 
        \href{https://github.com/namra-sabhaya/smart-trip-planner}{\faGithub}
      \end{tabular*}\vspace{-8pt}
      \resumeItemListStart
        \resumeItem{Design an end-to-end machine learning trip-planning platform predicting flight fares with a RandomForestRegressor (R2 = 0.774) trained on Kaggle flight-price data.}
        \resumeItem{Implement a Traveling Salesman Problem route optimizer using haversine distance with nearest-neighbor and 2-opt local search to sequence multi-city itineraries.}
        \resumeItem{Build content-based hotel and place recommendation engines using cosine similarity over 1,100+ hotels and 325 tourist destinations, served via a FastAPI backend.}
      \resumeItemListEnd

      \item
      \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
        \small\textbf{CPU \& Disk Scheduling and Deadlock Detection} $|$ \emph{JavaScript, HTML5, CSS3} & 
        \href{https://github.com/namra-sabhaya/schedforge}{\faGithub}
      \end{tabular*}\vspace{-8pt}
      \resumeItemListStart
        \resumeItem{Create a browser-based simulator visualizing six CPU scheduling algorithms (FCFS, SJF, SRTF, Priority, Round Robin) through interactive Gantt charts.}
        \resumeItem{Build a disk scheduling module (FCFS, SSTF, SCAN, C-SCAN) with seek-sequence visualization and total head-movement comparison across algorithms.}
        \resumeItem{Implement DFS-based deadlock detection over a resource allocation graph, rendering cycle-highlighted graphs to distinguish deadlock from safe states.}
      \resumeItemListEnd
    \resumeSubHeadingListEnd


%-----------ACHIEVEMENTS-----------
\section{Achievements}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Problem Solving}{: Solved 1200+ problems across various algorithmic platforms (LeetCode, Codeforces, CodeChef)} \\
     \textbf{LeetCode Knight}{: Achieved Knight Badge; Rating 1900+, Best Global Rank 1140 / 40,000+ in weekly contests} \\
     \textbf{Codeforces Pupil}{: Max Rating 1287; active solver of competitive programming tasks} \\
     \textbf{CodeChef 3-Star}{: Regular division participant} \\
     \textbf{JEE Main Excellence}{: Scored 98.44 Percentile in Joint Entrance Examination Main} \\
     \textbf{Scholar Certificate}{: Recipient of the College Scholar Certificate for academic excellence}
    }}
 \end{itemize}


%-----------CERTIFICATIONS-----------
\section{Certifications}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Machine Learning Specialization}{: Stanford University \& DeepLearning.ai} \\
     \textbf{RAG \& Agentic AI Specialization}{: IBM} \\
     \textbf{C++ and DSA Certification}{: Physics Wallah (600+ Hours)}
    }}
 \end{itemize}

\end{document}
