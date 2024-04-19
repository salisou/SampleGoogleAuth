.NET 8 💥 - Identity and Google Authentition
## Creazione del progetto 
⦁	dotnet new mvc -au Individual -n SampleGoogleAuth 

### Pachetti da installare:

    Microsoft.AspNetCore.Authentication.Google
    Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore    
    Microsoft.AspNetCore.Identity.EntityFrameworkCore    
    Microsoft.AspNetCore.Identity.UI
    Microsoft.EntityFrameworkCore
    Microsoft.EntityFrameworkCore.Design      
    Microsoft.EntityFrameworkCore.Sqlite
    Microsoft.EntityFrameworkCore.Tools
    Microsoft.VisualStudio.Web.CodeGeneration.Design
    
### Comando per genera le pagine e i modelli necessari per la gestione dell'identità
        dotnet aspnet-codegenerator identity -dc ApplicationDbContext Contesto aggiuntivo per il commento:
<p>Questo comando ti aiuta a creare velocemente il codice base per l'autenticazione e della gestione degli utenti, inclusi login, registrazione, gestione delle password e profili utente.
  <br/>
  <br/>
Andare sul sito https://console.cloud.google.com/welcome?project=netgoorleauth per creare un progetto selezionando 

![image](https://github.com/salisou/SampleGoogleAuth/assets/61307355/0c853910-f87d-4d59-b7be-6b92cdf192bc)
![image](https://github.com/salisou/SampleGoogleAuth/assets/61307355/a0fb346d-61d8-47cb-846e-3306331b5bc3)

![image](https://github.com/salisou/SampleGoogleAuth/assets/61307355/072a222f-2734-49bf-b6ce-cb96317ea16a)

Una volta il progetto creato. Seleziona il progetto:
<br/>
![image](https://github.com/salisou/SampleGoogleAuth/assets/61307355/000f0ccc-305f-4e08-894d-028c88ff7906)

</p>

