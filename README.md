# Bra formler för SF1626 (Flervariabelanalys)
Va fri och skriv in valfria satser på A nivå som inte tas med på kursens föreläsningar.
Länken till PDF:n finns [här](https://github.com/INDA22PlusPlus/plusplus-multivariable-calculus/blob/master/extra_theory.pdf).

## Compile?
Om du använder CLI latex compiler på UNIX du behöver installera följande paket så att dokumentet kompileras:
- texlive
- texlive-latex-base
- texlive-latex-extra
- texlive-fonts-extra
- texlive-science

För att kompilera PDF:n glöm inte template filerna och själva main tex filen:
- **extra_theory.tex** (main filen)
- letterfonts.tex
- macros.tex
- preamble.tex

## Formatting?
Template filerna ger en möjlighet att använda boxes för att skriva in satserna så att dokumentet blir strukturerat. Kolla exemplet nedan:

```tex
\thm{INFO OM DIN SATS KORTFATTAT}
{
SKRIV IN SJÄLVA SATSEN HÄR
}

\dfn{INFO OM DIN DEFINITION KORTFATTAT}
{
SKRIV IN SJÄLVA DEFINITIONEN HÄR
}

\nt{EN LITEN NOTE HÄR}

\ex{INFO OM DITT EXEMPEL KORTFATTAT}
{
SKRIV IN SJÄLVA EXEMPLET HÄR
}

\bt{INFO OM DIN BEVISTEKNIK HÄR}
{
SKRIV IN SJÄLVA BEVISTEKNIKEN HÄR
}

\tip{DIN TIPS HÄR}
{
SKRIV IN DIN TIPS HÄR
}
```

