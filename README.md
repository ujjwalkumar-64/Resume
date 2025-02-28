%-------------------------
% Resume in Latex
% Author - Ujjwal
% License : MIT
%------------------------

%---- Required Packages and Functions ----

\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{Ujjwal Kumar} % Your Name
\newcommand{\course}{B.Tech} % Your Course
\newcommand{\roll}{22cs3064} % Your Roll No.
\newcommand{\phone}{8084327504} % Your Phone Number
\newcommand{\emaila}{ujjwalkumar6281@gmail.com} %Email 1
\newcommand{\emailb}{22cs3064@rgipt.ac.in} %Email 2
\newcommand{\github}{ujjwalkumar-64} %Github
\newcommand{\leetcode}{u/ujjwal_808} %Website
\newcommand{\linkedin}{ujjwal-kumar-2aba15238/} %linkedin




\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------
 
\begin{tabularx}{\linewidth}{L r}
  \textbf{\LARGE \name} & +91-\phone\\
  {Roll No.:\roll} & \href{mailto:\emaila}{\emaila} \\
  \course &  \href{mailto:\emailb}{\emailb}\\
  {Computer Science and Engineering} &  \href{https://github.com/\github}{Github} $|$  \href{https://www.leetcode.com/\leetcode/}{LeetCode} \\
  {Rajiv Gandhi Institute of Petroleum Technology} & \href{https://www.linkedin.com/in/\linkedin/}{linkedin.com/in/\linkedin}
\end{tabularx}
 



%-----------EDUCATION-----------------
 
\section{Education}
\setlength{\tabcolsep}{5pt} % Default value: 6pt
% \renewcommand{\arraystretch}{1.1} % Default value: 1https://www.overleaf.com/project/61fc166d7eab8975b2ab74d0
\small{\begin{tabularx}
{\dimexpr\textwidth-3mm\relax}{|c|C|c|c|}
  \hline
  \textbf{Degree/Certificate } & \textbf{Institute/Board} & \textbf{CGPA/Percentage} & \textbf{Year}\\
  \hline
  B.Tech. (CSE) & Rajiv Gandhi Institute of Petroleum Technology & 7.87 (Current) & 2022-Present\\

  \hline
  Senior Secondary & CBSE Board & 82.0\% & 2021 \\
  \hline
  Secondary & CBSE Board & 94.0\% & 2019 \\
  \hline
\end{tabularx}}
\vspace{-2mm}

%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Procyl Theraputics}{Remote, India}
      {Website Developer}{Jan. 2025 - Feb. 2025}
      \resumeItemListStart
        \item {Developed and launched a fully responsive website for Procyl Theraputics, collaborating with cross-functional teams to enhance the brand’s digital presence.}
        \item {Optimized website performance by integrating modern web frameworks and best practices, significantly improving load times and ensuring a consistent user experience.}
      \resumeItemListEnd
    
    \resumeSubheading
      {SharpCareer Technologies}{Remote, India}
      {Back-end Developer Intern}{Jun. 2024 - Jul. 2024}
      \resumeItemListStart
        \item {Designed and implemented RESTful APIs, ensuring smooth integration with the frontend team and enhancing scalability.}
        \item {Addressed complex challenges, including database indexing and query optimization, thereby improving service availability and reliability.}
      \resumeItemListEnd
      
  \resumeSubHeadingListEnd
\vspace{-5.5mm}

%-----------PROJECTS-----------------
\section{Projects}
\resumeSubHeadingListStart

\resumeSubheading
  {Dev Tinder}{\href{http://13.232.143.33/}{Live Url} | {\href{https://github.com/ujjwalkumar-64/DevTinder-Frontend}{Github}}}
  {Microservice-based Platform for Developer Connections}{Jan. 2025}
  \resumeItemListStart
    \item {Developed a platform enabling developer connections with features including profile management, connection requests, activity feeds, real-time chat, and email notifications.}
    \item {Engineered RESTful APIs using Node.js and Express.js, implementing JWT for secure authentication.}
    \item {\textbf{Tech Stack:} React, Node.js, Express.js, AWS EC2, MongoDB, Tailwind CSS, Redux Toolkit, Axios, Socket.io.}
  \resumeItemListEnd

\resumeSubheading
  {Electro Repair Services}{\href{https://sharpcareer-solutions.netlify.app/}{Live Url} | {\href{https://github.com/ujjwalkumar-64/AMMRUY-1}{Github}}}
  {Responsive Website for Electronics Repair Services}{Nov. 2024 - Dec. 2024}
  \resumeItemListStart
    \item {Implemented features such as service browsing, feedback submission, and customer engagement tools.}
    \item {Built backend functionality with Node.js, Express, and MongoDB to manage service listings, customer feedback, and ensure secure interactions.}
    \item {Designed user-friendly interfaces with Figma to enhance the overall user experience.}
    \item {\textbf{Tech Stack:} React, Vite, Tailwind CSS, Redux, Figma, Node.js, Express, MongoDB.}
  \resumeItemListEnd
 
\resumeSubHeadingListEnd
\vspace{-5.5mm}




\section{Key Courses Taken}
 \resumeHeadingSkillStart
  \resumeSubItem{} % Category
   {Data Structures, Algorithms, DBMS, Deep Learning, Computer Networks, Operating Systems}

%  \resumeSubItem{Operating Systems}
%  {Windows, Linux*} 
% \hfill \textit{\footnotesize{* Elementary proficiency}} \hspace{3mm}
 \resumeHeadingSkillEnd

\section{Technical Skills}
 \resumeHeadingSkillStart
  \resumeSubItem{Programming: } % Category
    {C/C++, JavaScript, SQL}
 \resumeSubItem{Tools \& OS: } % Category
     {Git, Postman, VS Code, Google Colab, Linux, Windows} % Skills
 % \resumeSubItem{Libraries/Frameworks: } % Category
 %    {Pandas, Numpy, scikit-learn, JQuery}
    
     \resumeSubItem{Web Skills: } % Category
        {HTML/CSS/JS, ReactJS, Node.js/Express.js, MongoDB/MySQL}
%  \resumeSubItem{Operating Systems}
%  {Windows, Linux*} 
% \hfill \textit{\footnotesize{* Elementary proficiency}} \hspace{3mm}
 \resumeHeadingSkillEnd


\section{Positions of Responsibility}
\vspace{-0.4mm}
\resumeSubHeadingListStart

\resumePOR{Overall Event Head, } % Position
    {OWASP RGIPT Student Chapter} %Club,Event
    {Present} %Tenure Period
    
\resumePOR{Teaching Volunteer, } % Position
    {Gyanarpan, Project Amethi} %Club,Event
    {Sep. 2023 - Jan. 2025} %Tenure Period
\resumeSubHeadingListEnd
\vspace{-4mm}

\section{Achievements}
\vspace{-0.4mm}
\resumeSubHeadingListStart

\resumePOR{Selected in GSSOC}{\hspace{0.5em}as a Contributor}{2024}

\resumePOR{MCM Scholarship Received}{\hspace{0.5em}from RGIPT}{2022}

\resumePOR{Qualified}{\hspace{0.5em}IIT-JEE Advanced}{2022}

\resumeSubHeadingListEnd

\vspace{-4mm}
\section{Certifications}
\vspace{-0.2mm}
\resumeSubHeadingListStart

\resumePOR{}{
    Internship Certificate (Credential ID: BDCS-0008) by SharpCareer Technologies 
    \href{https://drive.google.com/file/d/19qHxc6tTsgSWSIAN-L6vSnpkLvgM-n_t/view?usp=sharing}{\faExternalLink}
}{Jul. 2024}

\resumePOR{}{
    Cyber Security (Credential ID: 1533/327802/CG/(15)/2024) by CDAC, NOIDA 
    \href{https://drive.google.com/file/d/1ZKSiYm65X4YZXoxi5rnifvRoTtariCsF/view?usp=sharing}{\faExternalLink}
}{Jun. 2024}

\resumeSubHeadingListEnd



\hspace*{-5mm}\rule{1.035\textwidth}{0.1mm}

%-------------------------------------------
\end{document}
