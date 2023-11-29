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

Nu måste jag överföra den ändrade koden från indexC.html till alla andra indexfiler.

Commit 7: Nu har jag fixat det.

Commit 8: Kopierat lite passande karaktärsbeskrivningar från google och klistrat in dem som figcaptions under varje image. Jag lade till divs för varje image i character-main-diven så att jag kunde sätta max-width till 300px. Detta är för att jag vill att texten ska se kompakt ut och inte ta upp hela sidan när den ökar i width. Och för att divarna ska kunna wrapa.

Commit 9: Lagt till en bild på home-sidan och ändrat .img gränsen för bilder från 300px till unlimited och istället specifikt ändrat .header img gränsen till 300px och sedan .bcsdesc till max 500px.

Commit 10: Nu har jag gjort klart plot-sidan. Jag klistrade in en text och importerade två images som jag sedan lade in. Jag kopierade all kod från styles.css och gjorde en ny css-fil som indexP.html länkar till. Detta är för att jag skapade en grid i main. Där gjorde jag en media query som gäller när enheten är i stående läge eller när width är under 500px. Media queryn flyttar upp de två bilderna ovanför texten med hjälp av grid-template-areas. Detta är i syftet att man inte skulle ha sett bilderna direkt om man hade kollat på sidan med en mobil då texten är så lång. Jag vill att man ska se dem direkt, och det kan man även göra i landscape-läge.

Commit 11: Jag städade kodraderna lite, så att det ser snyggare ut. Jag lade även till en länk på miscellaneous-sidan, ett dåligt skämt. Nu ska jag kommentera koden.

Commit 12: Kommenterat kod. Ändrat font family till en med sans-serif för att fler webbläsare stödjer den fonten.

Commit 13: Ändrade font för anchors i .nav-diven.

Commit 14: Lade till h1 och h3-rubriker, ändrade paddingen i media queryn för anchors i nav så att de har en större yta som de reagerar på, vilket är mer tillgängligt för ex. mobilanvändare.

Commit 15: Tog bort h3-rubriken och lade till h2 istället då det ser mer estetiskt tillfredsställande ut.