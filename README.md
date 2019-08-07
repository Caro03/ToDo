# ToDo app #

## Level 1 ##

* Registreren & inloggen
    * gebruik bcrypt + kunnen uitleggen
    waarom bcrypt veiliger dan md5/sha
* Lijsten toevoegen & verwijderen
* Taken toevoegen aan lijst
    * titel + werkuren
    * deadline datum
* Commenten op taken via **Ajax**
* Taken markeren als done via **Ajax**
* Zien of taak voorbij is of hoeveel dagen resteren
* Taken worden getoond volgens deadline

## Level 2 ##

* Realistisch aantal werkuren toekennen aan deadline
* Deadlines sorteren obv werkuren
* Eigen deadlines verwijderen/aanpassen

* Admin
    * gebruiker die je manueel aanmaakt + kan inloggen
        * in database extra veld "isAdmin"
    * kan bijkomende admins aanmaken/verwijderen
    * kan per week zien welke werkdruk gepland staat obv deadlines & geschatte werkuren
    * kan zien hoeveel users & hoeveel lijsten in app zitten

## Level 3 ##

* Bestand opladen & aan taak koppelen (pdf of afb)
* Gekoppelde bestanden verwijderen
* Geen dubbele taken opladen binnen zelfde lijst => foutboodschap

