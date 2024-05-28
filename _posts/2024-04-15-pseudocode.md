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
        \caption{Classical Euclidean Algorithm}
        \begin{algorithmic}
            \PROCEDURE{Euclid}{$$a,b$$}
                \WHILE{$$a \neq b$$}
                    \IF{$$a > b$$}
                        \STATE $$a \gets a - b$$
                    \ELSE
                        \STATE $$b \gets b - a$$
                    \ENDIF
                \ENDWHILE
                \RETURN $$a$$
            \ENDPROCEDURE
        \end{algorithmic}
        \end{algorithm}
```