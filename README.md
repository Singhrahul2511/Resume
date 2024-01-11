# Resume
Build an effective resume with Rahul
%-------------------------
% Resume in Latex
% Author : Abey George
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}



%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
      
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}


\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}



%----------HEADING----------


\begin{center}
    {\Huge \scshape Rahul Kumar} \\ \vspace{1pt}
    Aurangabad,Bihar \\ \vspace{1pt}
    \small \href{tel:#}{ \raisebox{-0.1\height}\faPhone\ \underline{+91-7033810323} ~} \href{mailto:yourname@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{99220042041@klu.ac.in}} ~ 
    \href{https://www.linkedin.com/in/rahul-kumar-8ab740268/}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{Linkedin}}  ~
    \href{https://github.com/Singhrahul2511}{\raisebox{-0.2\height}\faGithub\ \underline{Github}} ~ 
   \href{https://www.instagram.com/singhrahul2.0/}{\raisebox{-0.2\height}\faInstagram\ \underline{Instagram}}




    
\end{center}
 \vspace{0.5mm}



%-----------EDUCATION-----------
\section{EDUCATION}
  \resumeSubHeadingListStart
    \resumeSubheading
      {KARE, Kalasalingam Academy of Research and Education, Tamilnadu}{2022 – 2026}
      {B.Tech - Computer Science and Engineering - \textbf{CGPA} - \textbf{8.12}}{Krishnankovil, Tamilnadu}
  \resumeSubHeadingListEnd
  
%   \resumeSubHeadingListStart
%     \resumeSubheading
%       {College Name}{MM YYYY -- MM YYYY}
%       {Exam Name - Course Name  - \textbf{Percentage} - \textbf{xx\%}}{city, country}
%   \resumeSubHeadingListEnd

%------RELEVANT COURSEWORK-------
\section{COURSEWORK / SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item Basics of Data Structure and Algorithms (DSA)
                \item Basics of Database Management System (DBMS)
                \item Software Engineering
                \item Python
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-------------Experience-----------
\section{EXPERIENCE}
    \vspace{-5pt}
    \resumeSubHeadingListStart

      \resumeProjectHeading
          {\href{https://github.com/Singhrahul2511}{\textbf{\large{\underline{\textbf{No Work Experience}}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{}}}\\








          
          \resumeItemListStart 
          \vspace{-5pt}
    \resumeSubHeadingListEnd
\vspace{-12pt}





%-----------EXPERIENCE-----------
% \section{INTERNSHIP}
%   \resumeSubHeadingListStart

%     \resumeSubheading
%       {Company Name \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{MM YYYY -- MM YYYY} 
%       {\underline{Role Name}}{city, country}
%       \resumeItemListStart
%         \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
  
%       \resumeItemListEnd  
%   \resumeSubHeadingListEnd
% \vspace{-12pt}
%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Languages:}}{  \normalsize{Python,Basics of Java,}} \\
     \textbf{\normalsize{Developer Tools:}}{  \normalsize{VS Code, Android Studio}} \\
    }}
 \end{itemize}
 \vspace{-15pt}


%-----------INVOLVEMENT---------------
\section{Coding Platforms}
\resumeSubHeadingListStart
    \resumeItemListStart
        \resumeItem{\textbf{Hackerrank:} \textbf{50+} Rating, Solved \textbf{100+} Problems
        \href{https://www.hackerrank.com/dashboard}{\raisebox{-0.1\height}{\faExternalLink}}}
        \resumeItem{\textbf{Codechef:} Solved 50+ Problems
        \href{https://www.codechef.com/learn/course/kl-dbms-cs}{\raisebox{-0.1\height}{\faExternalLink}}}
        
        \href{https://codeforces.com/profile/abthecoder23}{\raisebox{-0.1\height}{\faExternalLink}}}
        % \resumeItem{\textbf{Participation Certificate}
        % \href{ParticipationCertificateLink.com}{\raisebox{-0.1\height}{\faExternalLink}}}
    \resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-11pt}


 
  %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}

$\sbullet[.75] \hspace{0.1cm}$ {\href{https://brm-certification.oracle.com/apex/f?p=1111:5:105606400901::NO:::}{Oracle Cloud Infrastructure 2023 AI Foundations Associate-Oracle}} \hspace{2.59cm}\\
$\sbullet[.75] \hspace{0.1cm}$ 
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com} {Placement Training - IIT Bombay}}\hspace{1.6cm}\\
$\sbullet[.75] \hspace{0.2cm}${\href{https://archive.nptel.ac.in/noc/B2C/candidate_login/main.php}{Soft Skill - NPTEL(IIT Roorkee)}} \hspace{1cm}\\






 \section{EXTRACURRICULAR}
    \resumeSubHeadingListStart
        % \resumeSubheading{Organization Name \href{Certificate Proof link}{\raisebox{-0.1\height}\faExternalLink } }{05-2021 -- 12-2021}{\underline{Role}}{Location}
        
            \resumeItemListStart
                \resumeItem{\normalsize{Taught basic Kotlin/DSA in offline Mode.          10-2023 -- 12-2023}}
                \resumeItem{\normalsize{Passionate to play cricket till 2015}}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
 \vspace{-11pt}
 
 \end{document}
 
