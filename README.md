# Övningar med HTTP och webbserver

## Instruktioner

1. Bygg en webbserver som när man går in på webbsidan (exempelvis localhost:8000) returnerar och visar texten **Stop, stop stop! You're going to take someone's eye out. Besides, you're saying it wrong. It's Levi-o-sa, not Levio-sar.**

2. Ändra nu så att istället för ovanstående text så returneras en HTML-fil istället när man går in på webbsidan.

3. Lägg nu till så att även en css-fil läses in.

4. Gör det möjligt att navigera på webbsidan mellan olika HTML-sidor.

5. Lägg till en 404-sida om en användare försöker gå till en url som inte finns.

6. Ifall man skriver i url:en **?givemesecret** så ska webbservern returnera ett slumpat lösenord till klienten. Detta ska man sedan kunna validera mot webbservern genom att skriva **/password=DITTLÖSENORD** och få ett svar från webbservern om det är korrekt. (Observera att man aldrig ska skriva lösenord i url:en detta är enbart för övning :) ).