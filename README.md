# Simple template of latex for Koszalin University 


MiKTeX for Windows
=> faster TeX Live for Linux and other UNIX-like systems

## Install on ubuntu: 
```sh
sudo apt install texlive-full
```


## command 

add image
```tex
\begin{figure}[!htb]
    \centering
    \includegraphics[width=0.5\textwidth]{pi}
    \caption{Płytka rasebrry Pi.}
\end{figure}
```

add code snippets from file:

```tex
\lstinputlisting{./src/code_snippets/hello.cpp}
```

