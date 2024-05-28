---
layout: post
title: a post with pseudo code
date: 2024-04-15 00:01:00
description: this is what included pseudo code could look like
tags: formatting code
categories: sample-posts
pseudocode: true
---

```pseudocode
 \begin{algorithm}
        \caption{Test text-style}
        \begin{algorithmic}
        \REQUIRE some preconditions
        \ENSURE some postconditions
        \INPUT some inputs
        \OUTPUT some outputs
        \PROCEDURE{Test-Declarations}{}
            \STATE font families: {\sffamily sffamily, \ttfamily ttfamily, \normalfont normalfont, \rmfamily rmfamily.}
            \STATE font weights: {normal weight, \bfseries bold, \mdseries
            medium, \lfseries lighter. }
            \STATE font shapes: {\itshape itshape \scshape Small-Caps \slshape slshape \upshape upshape.}
            \STATE font sizes: \tiny tiny \scriptsize scriptsize \footnotesize
            footnotesize \small small \normalsize normal \large large \Large Large
            \LARGE LARGE \huge huge \Huge Huge \normalsize
        \ENDPROCEDURE
        \PROCEDURE{Test-Commands}{}
            \STATE \textnormal{textnormal,} \textrm{textrm,} \textsf{textsf,} \texttt{texttt.}
            \STATE \textbf{textbf,} \textmd{textmd,} \textlf{textlf.}
            \STATE \textup{textup,} \textit{textit,} \textsc{textsc,} \textsl{textsl.}
            \STATE \uppercase{uppercase,} \lowercase{LOWERCASE.}
        \ENDPROCEDURE
        \PROCEDURE{Test-Colors}{}
            \STATE colors: $\color{red}{red}$, $\color{green}{green}$, $\color{blue}{blue}$
            \STATE colors: $\color{yellow}{yellow}$, $\color{cyan}{cyan}$, $\color{magenta}{magenta}$
        \ENDPROCEDURE
        \end{algorithmic}
        \end{algorithm}




```