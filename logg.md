Commit 1: Jag var sjuk förra veckan så jag har gjort planeringen hemma och börjat på hemsidan denna vecka. Jag har gjort ganska mycket idag, så jag kommer dela upp det.
Jag började med att importera en png med seriens logga och la in den som en header. Sedan skaffade jag borders och gav dem samma färg som "BETTER CALL" i titeln. Efter det jobbade jag mycket för att försöka få till griden men lyckades inte. Jag hade glömt att jag inte kan skriva "display: grid" för alla grid items då det skapar en ny grid. Jag tog bort det och då löstes problemet.

Måste kommentera kod
Måste importera bilder och göra main till flexbox
Lagt till en folder för imgs

Commit 2: Jag har tweakat lite på paddings och tagit bort lorem ipsum i nav och main, lagt in bilder och nav hyperlinks. Sedan så fixade jag så alla images inte blev capped på 300px width genom att jag använde mig av .header img för att selecta Better Call Saul-loggan.

Commit 3: Jag har lärt mig att commita lite oftare då en stor del av mitt arbete idag gick förlorat på grund av någonting, och då hade jag bara en commit som var ganska länge sedan att använda. Men, jag har skapat andra index-filer för de olika sidorna i hemsidan och de använder sig av samma styles.css-fil och samma img filer. Jag kommer bara ändra innehållet i main för att skapa illusionen av att bara main ändras.

Commit 4: Jag har ändrat grid-template-areas lite då 3 rader inte behövdes. Sedan har jag gjort så att hyperlinksen i nav byter färg till vit när man hoverar över dem med musen och att det finns en padding mellan dem när media queryn inte är aktiv, och att den paddingen tas bort när media queryn är aktiv.

Commit 5: Nu har jag lagt till padding mellan länkarna i nav och gjort så att det inte finns någon padding när media queryn är aktiv. Jag försöker leta efter ett sätt för .nav diven att fylla upp hela tomma området.

Commit 6: Jag har nu gjort så att diven tar upp hela tomma området genom att sätta min-height till 100%. Men jag märkte att den överskred .main diven så då satte jag box-sizing till border-box, vilket gör så att storleken på containern begränsas till kanterna av containern. Men nu vidrörde .nav diven .main diven, så jag fixade även det.