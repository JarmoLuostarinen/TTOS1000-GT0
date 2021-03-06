# Versionhallintahaara (Branch)

Kuvauksen kirjoitti: Rami Ojala, K8412

## Lyhyt kuvaus

Versionhallinnassa, Haara, eli Branch on kopio jostain toisesta haarasta (tai Master Branch), johon ollaan vapaita tekemään muutoksia vaikuttamatta haaraan joka ollaan kopioitu. Brancheja käytetään, jotta voidaan koodata useita ominaisuuksia samanaikaisesti (tai debugata ja korjata useita virheitä samanaikaisesti). Yksinkertaisessa Git Workflow:ssa,  kun aletaan tehdä uutta ominaisuutta, haaraudutaan suoraan Masterista ja kun ominaisuus on valmis, pullataan Masteri vielä uudestaan siltä varalta, että Masteriin on tullut muutoksia, sitten testataan että mikään ei mennyt rikki ja pusketaan ominaisuus haara takaisin Masteriin.

## Esimerkkejä

Master Branch, sisältää testatun ja toimivaksi todetun koodin. Joissain Git Workflow:ssa tästä haarasta, haaraudutaan Release 1.0, 1.1, ... n, 2.0 haaroihin.

Test Branch, Tämä haara sisältää koodin, joka on valmiina Hyväksyntä testaukseen. Hyväksyntä testauksen läpäistyä tämä mergetään Masteriin.

Development Branch, Tämä haara sisältää testaamattoman valmiin koodin.

Feature Branch, Tämä haara vedetään Development Branchista, kun aletaan tekemään uutta ominaisuutta ohjelmistoon ja haaran elinkaaren lopussa Mergetään takaisin development branchiin odottamaan testausta.

Issue (Hotfix) Branch, Tämä haara, riippuen Workflow:sta vedetään Master Branchista ja korjauksen löydyttyä pusketaan, sekä Master branchiin, että Development branchiin

## Lähteitä liittyen aiheeseen

* [Git Branching and Merging Strategies (24:16))](https://www.youtube.com/watch?v=to6tIdy5rNc)
* [Atlassian Stash - Git workflows in the Enterprise (36:05))](https://youtu.be/gLWSJXBbJuE)
* [Wikipedia artikkeli](https://en.wikipedia.org/wiki/Branching_(version_control))

## Linkit wikin muihin sivuihin

* [Etsi tähän linkki toiseen wikin sisällä olevaan sivuun, joka liittyy oleellisesti omaan aiheeseesi]()
