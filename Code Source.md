\documentclass[12pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[arabic,french]{babel}
\usepackage{lipsum}
\usepackage{graphicx,wrapfig,lipsum}
\usepackage{caption} 
\usepackage{amsfonts}
\usepackage{enumitem}
\usepackage{pifont}
\usepackage{float}
\usepackage{amsmath}
\usepackage{shorttoc}
\usepackage{lmodern}
\usepackage{enumitem}
\usepackage{fancyhdr}
\usepackage{xcolor}
\usepackage{tikz}
\renewcommand{\baselinestretch}{2} % 1.5 denotes double spacing. 
\usepackage[width=18.00cm, height=26.00cm]{geometry}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\newcommand{\titlebox}[2]{%
	\tikzstyle{titlebox}=[rectangle,inner sep=20pt,inner ysep=30pt,draw]%
	\tikzstyle{title}=[fill=white]%
	%
	\bigskip\noindent\begin{tikzpicture}
	\node[titlebox] (box){%
		\begin{minipage}{0.7\textwidth}
		#2
		\end{minipage}
	};
	%\draw (box.north west)--(box.north east);
	\node[title] at (box.north) {#1};
	\end{tikzpicture}\bigskip%
}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{document}

		
		\begin{otherlanguage}{arabic}
			\begin{center}
				
		
	الجـــمـــهوريـــة الجــــزائــــريـــة الديـــمــوقراطـــيــة\\
		\textLR{RÉPUBLIQUE ALGÉRIENNE DÉMOCRATIQUE ET POPULAIRE} \\
	وزارة التـــــعـــــــيـــم العـــالي و الــبـــحث البــعـــلـــمي \\
		\textLR {Ministère de l’Enseignement Supérieur et de la Recherche Scientifique} \\
	جـــامـــعـــة أبو بــكـــر بلقـــــــايــد – تـــــــلمســـان – \\
		\textLR	{Université Aboubakr Belkaïd– Tlemcen } \\	\textLR	{Faculté de TECHNOLOGIE } \\
		
		\end{center}
		\end{otherlanguage}
	\begin{otherlanguage}{french}
		\begin{figure}[H]
			\centering
			\includegraphics[width=0.1\linewidth]{Logo-Univ_Tlemcen}
		\end{figure}
		\begin{center}
		$ \LARGE {\textbf{ Mémoire}}   $ \\
					\textbf{Présenté} pour l’obtention du \textbf{diplôme} de\textbf{ MASTER }\\
		\textbf {En} : \textbf {É}lectrotechnique \\
		\textbf {Spécialité :}  \textbf{C}ommande de \textbf{m}achine  \\
		\textbf{Par :}  ??????????? \\
		\titlebox{\textbf{Thème}}{\textbf{............................................................................................}} \\
		Soutenu publiquement, le \textbf{../../....}, devant le jury composé de :
	\end{center}
	\end{otherlanguage}

\begin{minipage}[c]{1\linewidth}
	\begin{center}
	\begin{tabular}{llll}
		
		Mr ....................... & Maître de Conférences -A-   &	 Univ. Tlemcen &	 Président \\ 
		Mr ....................... & Maître de Conférences -A-  &	 Univ. Tlemcen &	 Encadreur \\
		Mr ....................... & Maître de Conférences -A-  &	 Univ. Tlemcen  &	Examinateur  \\ 
		Mr ....................... & Maître de Conférences -A-   &	 Univ. Tlemcen &	 Examinateur \\ 
	\end{tabular}
\end{center}

\end{minipage}


		
	\end{document}
