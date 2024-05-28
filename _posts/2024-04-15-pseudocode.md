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
% Incremental test algorithm with an arithmetic operation and a call
\begin{algorithm}
\caption{Check Probabilities}
\begin{algorithmic}
\PROCEDURE{CheckProbabilities}{$$A, B$$}
    \IF{$$A > B$$}
        \STATE $$C \gets A - B$$
        \STATE \CALL{ExampleCall}{$$C$$}
    \ENDIF
\ENDPROCEDURE
\end{algorithmic}
\end{algorithm}

```