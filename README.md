# nissepedia
Nissepedia


Här ligger alla artiklar.
Artiklarna är formaterade med LaTeX som är ett typsättningsprogram.

Alla artiklar börjar med
```latex
\ditem[ACDC Lane]\label{acdclane}
```
Där `ACDC Lane` är artikelnamnet som står i fetstil och `acdclane` är namnet som man kan referera till från andra artiklar (det får inte innehålla specialtecken så det är lite modifierat).
För att vara petig så är `å`, `ä`, `ö`, `ü` utbytt mot `aa`, `ae`, `oe`, `u` och så vidare.

Fet stil skriver man såhär `bla bla \textbf{detta blir fet text} bla bla`.
Kursiv stil gör man såhär `bla bla \textit{Taurotragus oryx} bla bla`
Citat såhär `bla bla \quotetext{detta är ett citat} bla bla`
Understuken text `bla bla \underline{detta är understruket} bla bla`
Överstuken text `bla bla \sout{detta är överstruket} bla bla`
Referenser är bara fet stil `bla bla \textbf{AC/DC}` eller om referensen inte sitter ihop med ordet som referensen pekar på så sätter man det inom parentes `Fan vad fint med lite rock'n'roll! (\\textbf{AC/DC})`

Listor gör man såhär
```latex
\begin{itemize}
 \item Rad ett
 \item Rad två
 \item Rad tre
 \end{itemize}
```

Numrerade listor gör man såhär
```latex
\begin{enumerate}
 \item Rad ett
 \item Rad två
 \item Rad tre
 \end{enumerate}
```

Subtitlar gör man såhär `\subtitle{Detta är en undertitel}`

Vissa tecken får man inte skriva utan att ha ett `\` före dom. 
text `_`, `#`, `\`, `%`, `&`, `<`, `>`, `\` måste alltså skrivas `\_`, `\#`, `\\`, `\%`, `\&`, `\<`, `\>`, `\\` eftersom dom har andra  betydelser i LaTeX.

