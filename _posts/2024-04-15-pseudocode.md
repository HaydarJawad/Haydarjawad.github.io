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
% This algorithm checks the axioms of probability for an AI image classification model
\begin{algorithm}
\caption{Check Probabilities of Image Classification Model}
\begin{algorithmic}
\PROCEDURE{CheckProbabilities}{$$sample\_space, event\_A, event\_B$$}
    \STATE $$total\_images \gets$$ \CALL{Length}{$$sample\_space$$}
    \STATE $$prob\_A \gets$$ \CALL{Length}{$$event\_A$$} / $$total\_images$$
    \STATE $$prob\_B \gets$$ \CALL{Length}{$$event\_B$$} / $$total\_images$$

    \PROCEDURE{NonNegativity}{$$prob$$}
        \IF{$$prob \geq 0$$}
            \STATE \textbf{return} True
        \ELSE
            \STATE \textbf{return} False
        \ENDIF
    \ENDPROCEDURE

    \STATE $$is\_non\_negative \gets$$ \CALL{NonNegativity}{$$prob\_A$$} \AND \CALL{NonNegativity}{$$prob\_B$$}

    \IF{$$is\_non\_negative$$}
        \STATE \textbf{print}("Non-negativity check passed")
    \ELSE
        \STATE \textbf{print}("Non-negativity check failed")
    \ENDIF
\ENDPROCEDURE
\end{algorithmic}
\end{algorithm}

```