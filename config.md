@def author = "Fabian Greimel"

\newcommand{\circularimage}[2]{
    ~~~
    <img class="circular--square" src=!#1 style="max-width:35%;min-width:40px;float:right;" alt="!#2" />
    ~~~
}

\newcommand{\details}[2]{
    ~~~
    <details> <summary> #1 </summary>
     #2
    </details>
    ~~~
}

\newcommand{\abstract}[1]{\details{[Abstract]}{<i>#1</i>}}

\newcommand{\paper}[4]{
    **!#1** (!#2) ~~~<br>~~~
    with #3 #4
    }

@def generate_rss = false
