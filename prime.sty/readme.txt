%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%    this is a readme file which means you   %%%%%
%%%%%       should probably pay attention!       %%%%%
%%%%%  you need everything in this folder to be  %%%%%
%%%%%  in your directory if you want to use the  %%%%%
%%%%% style file (besides the readme, of course) %%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% some stuff you can use: 
% NOTE: BASICALLY EVERY ENVIRONMENT HAS ITS OWN COLOR! PLEASE CHECK THEM ALL OUT :D :D 

\prob{Source}{Problem}

\begin{question}{(source)} % must use parentheses around the source! also replace question with theorem and definition. 
% Problem
\end{question}

\begin{proofX} % replace X with either A,C,G,N. 
% Red solution environment % A = red; C=yellow; G=green; N=blue
\end{proofX}
% replace proof with lemma or claim
% end lemma with \endlem for empty square and end proof with \endpro or \endsol for blacksquare at the end of line


% you can put environments like itemize, lemmaX, etc. inside the proofX environments! how cool

% here's what your preamble should look like :)

\documentclass[10pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage{prime}

\backgroundsetup{
scale=1,
color=black,
opacity=0.4,
angle=0,
contents={%
  \includegraphics[width=\paperwidth,height=\paperheight]{bk7.png} 
  }%
}

\author{}
\title{}
\date{}
\begin{document}
\maketitle
\BgThispage
\begin{flushleft}

\toc
\newpage

%main document begins

\end{flushleft}
\end{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%% large amount of credits to dennis chen, %%%%%
%%%%%   who basically created this sty (with  %%%%%
%%%%%   modifications by myself) and you can  %%%%%
%%%%% probably tell by visual similarities :) %%%%%
%%%%%  by the way, i hope what i'm doing does %%%%%
%%%%%             indeed work :)              %%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
