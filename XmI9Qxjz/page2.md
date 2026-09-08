# Inject Keys with Default options : 
<br>
<inject key="AzureAdUserEmail"  defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<grouped-questions source="page2_Group_RRkmkDUd" />


<inject key="**AzureAdUserEmail**" defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="Sample" defaultvalue="Defaultemail@example.com">     // output shows default value since key is invalid

<inject key="AzureAdUserEmail" defaultvalue="">     // output shows Key value since its valid  

<inject key="" defaultvalue="Defaultemail@example.com">      // output shows default value since key is blank

<inject key="" defaultvalue="">   // no output as Key and default values are blank 


<grouped-questions source="page2_Group_RRkmkDUd" />



<validation step="a43678ce-cb7c-4a7f-9087-fc73a4148d46" />

