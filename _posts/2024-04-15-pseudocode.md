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
\PROCEDURE{CheckProbabilities}{$sample\_space, event\_A, event\_B$}
    \STATE $total\_images \gets$ \CALL{Length}{$sample\_space$}
    \STATE $prob\_A \gets$ \CALL{Length}{$event\_A$} / $total\_images$
    \STATE $prob\_B \gets$ \CALL{Length}{$event\_B$} / $total\_images$

    \PROCEDURE{NonNegativity}{$prob$}
        \IF{$prob \geq 0$}
            \STATE \textbf{return} True
        \ELSE
            \STATE \textbf{return} False
        \ENDIF
    \ENDPROCEDURE

    \PROCEDURE{Normalisation}{$prob\_A, prob\_B$}
        \IF{$prob\_A + prob\_B = 1$}
            \STATE \textbf{return} True
        \ELSE
            \STATE \textbf{return} False
        \ENDIF
    \ENDPROCEDURE

    \PROCEDURE{Additivity}{$prob\_A, prob\_B$}
        \IF{$prob\_A + prob\_B \leq 1$}
            \STATE \textbf{return} True
        \ELSE
            \STATE \textbf{return} False
        \ENDIF
    \ENDPROCEDURE

    \STATE $is\_non\_negative \gets$ \CALL{NonNegativity}{$prob\_A$} \AND \CALL{NonNegativity}{$prob\_B$}
    \STATE $is\_normalised \gets$ \CALL{Normalisation}{$prob\_A, prob\_B$}
    \STATE $is\_additive \gets$ \CALL{Additivity}{$prob\_A, prob\_B$}

    \IF{$is\_non\_negative$}
        \STATE \textbf{print}("Non-negativity check passed")
    \ELSE
        \STATE \textbf{print}("Non-negativity check failed")
    \ENDIF

    \IF{$is\_normalised$}
        \STATE \textbf{print}("Normalisation check passed")
    \ELSE
        \STATE \textbf{print}("Normalisation check failed")
    \ENDIF

    \IF{$is\_additive$}
        \STATE \textbf{print}("Additivity check passed")
    \ELSE
        \STATE \textbf{print}("Additivity check failed")
    \ENDIF

    \STATE \textbf{print}("Probability of image being a cat: ", $prob\_A$)
    \STATE \textbf{print}("Probability of image being a dog: ", $prob\_B$)

\ENDPROCEDURE
\end{algorithmic}
\end{algorithm}

```