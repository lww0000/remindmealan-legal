# Integritetspolicy

**Ikraftträdandedatum:** 2026-10-02

Denna integritetspolicy förklarar hur mobilappen Remind Me Alan ("Appen"), utgiven av John-Christian Wahlberg ("vi", "oss", "vår"), hanterar din information. John-Christian Wahlberg är personuppgiftsansvarig för den behandling av personuppgifter som beskrivs i denna policy. Vi har byggt Appen utifrån en enkel princip: **dina påminnelser och personliga inställningar stannar på din enhet.** Det enda undantaget är hanteringen av prenumerationer — den information som krävs för att hantera och verifiera prenumerationer, tillsammans med teknisk information om din enhet som skickas automatiskt vid varje anrop, som beskrivs i avsnitt 5.

## 1. Vilken information Appen lagrar

För att kunna erbjuda sina funktioner lagrar Appen följande enbart på din enhet, med hjälp av enhetens lokala lagring (AsyncStorage):

- Ditt förnamn och vald avatarfärg
- De påminnelser du skapar (namn, ikon, tid, upprepningsregel samt eventuellt eget ljud eller enstaka dagsundantag du ställer in)
- Dina inställningar (notisljud, vibrationsinställning, språk, färgtema och om påminnelser är påslagna)
- En lokal kopia av din prenumerationsstatus (aktiv eller inte, plan och förnyelsedatum), samt tekniska flaggor som om introduktionen är klar

RevenueCats komponent sparar även sitt slumpmässiga ID och din prenumerationsstatus på enheten. Det är hela mängden personlig information som Appen lagrar på din enhet. Dessutom kontaktar Appen RevenueCat varje gång den startar för att kontrollera din prenumerationsstatus. Det gäller alla användare, oavsett om du prenumererar; se avsnitt 5. Vi ber inte om din e-postadress, ditt telefonnummer, dina kontakter, din plats, dina foton eller någon annan personlig information utöver det som listas ovan, och det finns inget konto eller någon inloggning av något slag.

## 2. Var informationen lagras — och var den inte lagras

All information som listas ovan lagras **lokalt på din enhet** och **överförs aldrig till oss eller till någon server**. Vi driver ingen backend, databas eller molnlagring för Appen, så vi tar aldrig emot, ser eller har tillgång till dina påminnelser, ditt namn eller dina inställningar. Det finns inget för oss att förlora, läcka eller sälja, eftersom vi aldrig tar emot det från första början. Om du använder iCloud-säkerhetskopiering kan Apple ta med denna data i säkerhetskopian av din enhet, enligt Apples villkor.

## 3. Ingen reklam eller spårning

Appen innehåller ingen reklam eller reklamnätverk och spårar dig inte mellan andra företags appar eller webbplatser i reklamsyfte ("spårning" enligt Apples definition). Den enda tredjepartstjänst som Appen skickar data till är RevenueCat, som beskrivs i avsnitt 5, och som behandlar köphistorik för att hantera prenumerationer och för grundläggande prenumerationsanalys — den spårar dig inte och används inte för reklam. Utöver det samlar Appen inte in någon annan analysdata och profilerar inte ditt beteende.

## 4. Notiser

Appen schemalägger lokala notiser direkt på din enhet via iOS:s eget notissystem, baserat på de påminnelser du skapar. Dessa notiser genereras och levereras helt på enheten; inget notisinnehåll skickas genom eller hanteras av någon extern server som drivs av oss.

## 5. Betalningar, prenumerationer och RevenueCat

Om du köper en prenumeration hanteras hela betalningstransaktionen av Apple via App Store och ditt Apple-ID. Vi tar aldrig emot, ser eller lagrar dina kortuppgifter, faktureringsadress eller annan betalningsinformation — den informationen hanteras uteslutande av Apple, i enlighet med Apples egen integritetspraxis.

Vi använder RevenueCat (RevenueCat, Inc., med säte i USA) för att hantera och verifiera din prenumeration samt för att stödja funktionen "Återställ köp". RevenueCat behandlar denna information för vår räkning som vårt personuppgiftsbiträde, enligt våra instruktioner.

RevenueCat tar emot ett slumpmässigt ID som Appen skapar, din köphistorik om du har någon (till exempel vilken prenumeration du köpt, när, och dess aktuella status), samt teknisk information som skickas automatiskt vid varje anrop: enhetens leverantörs-ID (ett ID från Apple som bara gäller våra appar på din enhet), enhetsmodell, iOS-version, appversion, föredragna språk, App Store-land och din IP-adress. Dessa ID:n räknas som personuppgifter enligt GDPR, även om de inte är ditt namn, din e-postadress eller någon annan direkt identifierande uppgift. RevenueCat tar inte emot dina kortuppgifter; de stannar uteslutande hos Apple, som beskrivs ovan.

Den rättsliga grunden för att behandla din köphistorik är att fullgöra ditt prenumerationsavtal med oss. För den tekniska informationen som beskrivs ovan är den rättsliga grunden vårt berättigade intresse av att kontrollera om en prenumeration är aktiv och av att den kontrollen fungerar korrekt och säkert — även innan du prenumererar, eller om du aldrig gör det, då det inte finns något avtal att fullgöra. Vi sparar denna köphistorik så länge din prenumeration är aktiv, och därefter bara så länge lag kräver (till exempel bokförings- och skattelagstiftningens krav på arkivering). Den tekniska informationen som beskrivs ovan sparas av RevenueCat som en del av samma uppgifter, inte längre än vad dessa ändamål kräver. Om du aldrig prenumererar finns ingen köphistorik — bara den tekniska informationen, som sparas på samma sätt.

Denna information överförs till och lagras i USA, med lämpliga skyddsåtgärder såsom EU-kommissionens standardavtalsklausuler. RevenueCat använder den inte för reklam eller spårning mellan appar. Dina påminnelser, ditt namn och dina övriga appinställningar fortsätter att sparas bara på din enhet och skickas aldrig till RevenueCat eller någon annanstans. Du kan läsa RevenueCats egen integritetspolicy på https://www.revenuecat.com/privacy.

## 6. Barns integritet

Appen riktar sig inte till barn och är inte avsedd att samla in personlig information från barn. Bortsett från den begränsade prenumerationsinformationen som beskrivs i avsnitt 5 — som gäller på samma sätt för alla användare, oavsett ålder — för Appen aldrig över någon annan information från din enhet, så ingen annan personlig information om ett barn (eller någon annan) tas någonsin emot eller lagras av oss. Om du är förälder eller vårdnadshavare och tror att ett barn har använt Appen kan du när som helst ta bort all lokalt lagrad information med hjälp av raderingsmetoderna nedan.

## 7. Så här raderar du din data

Du kan:

- Radera enskilda påminnelser direkt i Appen, eller
- Använda "Radera alla påminnelser" i Appens inställningar för att ta bort alla påminnelser på en gång, eller
- Avinstallera Appen, vilket omedelbart tar bort all dess lokalt lagrade data (påminnelser, namn och inställningar) från din enhet.

Att avinstallera Appen raderar inte din köphistorik hos RevenueCat — den sparas enligt beskrivningen i avsnitt 5. Om du vill att din köphistorik hos RevenueCat raderas, mejla oss på remindmealan@gmail.com så vidarebefordrar vi din begäran till RevenueCat.

## 8. Dina rättigheter (GDPR och andra dataskyddslagar)

Om du befinner dig inom EES, Storbritannien eller en annan jurisdiktion med liknande dataskyddslagstiftning kan du ha rättigheter såsom rätt till tillgång, rättelse, radering eller dataportabilitet av dina personuppgifter, samt rätt att invända mot eller begränsa viss behandling. Dina påminnelser, ditt namn och dina övriga appinställningar sparas enbart på din enhet, under din egen kontroll, hela tiden, så det finns i regel ingen sådan data hos oss som dessa rättigheter kan utövas mot. Dessa rättigheter gäller även köphistorikdata som behandlas via RevenueCat enligt beskrivningen i avsnitt 5 — för att utöva dem, kontakta oss via uppgifterna nedan, precis som för andra integritetsfrågor. Du har även rätt att klaga till en tillsynsmyndighet för dataskydd — i Sverige Integritetsskyddsmyndigheten (IMY), imy.se.

## 9. Ändringar av denna policy

Vi kan uppdatera denna integritetspolicy från tid till annan för att spegla ändringar i Appen eller av juridiska eller regulatoriska skäl. Om vi gör väsentliga ändringar kommer vi vidta rimliga åtgärder för att meddela dig (till exempel i Appen). "Ikraftträdandedatum" ovan anger när denna policy senast uppdaterades.

## 10. Kontakt

Om du har frågor om denna integritetspolicy, kontakta oss på: remindmealan@gmail.com
