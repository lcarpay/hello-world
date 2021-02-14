Ik tik nu even de git commando's die je nodig hebt

Op F:\Git (de centrale remote map of, optioneel, in Github):
* md dieren.git
* cd dieren.git
* git init --bare .

Je hebt dan een centrale Git

Ergens op C: kan je nu doen
* git clone f:\Git\dieren.git
* cd dieren

Nu kan je in deze map code gaan plaatsen.
Je kan status zien met volgende 2 commano's:
* git status
* gitk

Je kan code code committen in 1 stap maar ik raad het aan in 2 stappen te doen:
* git add .
of
* git commit -m "My first commit"

Wij doen zelfs voor ons zelf alles in het Engels want dan kan je later makelijk code overdragen.

- Martin
  (komt de wijziging aan?)