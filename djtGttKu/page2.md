## # Inject Keys with Default options : 
<br>
<inject key="AzureAdUserEmail"  defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="**AzureAdUserEmail**" defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="Sample" defaultvalue="Defaultemail@example.com">     // output shows default value since key is invalid

<inject key="AzureAdUserEmail" defaultvalue="">     // output shows Key value since its valid  

<inject key="" defaultvalue="Defaultemail@example.com">      // output shows default value since key is blank

<inject key="" defaultvalue="">   // no output as Key and default values are blank 
