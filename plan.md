# workflow
Her står huskeregler og instruksjoner på hvordan å jobbe.

## github
Oppgaver fordeles på GitHub.
* issues: ting som må gjøres legges inn som issues
* fikse issue: når du har fikset et *issue*, kan du trykke "close issue" eller *commite* med f.eks. teksten "fixed #3", så blir *issue 3* *closed*
* projects: her får du en oversikt over alt som må gjøres

## clean code
Moduler: funksjoner og klasser som er selvstendige:
* input -> output

Memory management: bruk std::vector

Globale variabler (som kan endres av alle): ikke greit!  

## google test
Skal ikke tvinge noen til å bruke unit testing, men det er ihvertfall en mulighet.

## debug-funksjoner
Debug-mode ligger oppå programmet, i separate filer, og kan skrus av ved compiling. 
* Dear ImGui: visuell debugging
* cout/cerr: må huske å fjerne

# stil
typer (class og typedef): CamelCase
variabelnavn og funksjoner: snake_case
