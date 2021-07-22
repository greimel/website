@def author = "The Oracle"

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

@def generate_rss = false
