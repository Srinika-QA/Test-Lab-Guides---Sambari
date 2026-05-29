# Inject Keys with Default options : 
<br>
<inject key="AzureAdUserEmail"  defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="**AzureAdUserEmail**" defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="Sample" defaultvalue="Defaultemail@example.com">     // output shows default value since key is invalid

<inject key="AzureAdUserEmail" defaultvalue="">     // output shows Key value since its valid  

<inject key="" defaultvalue="Defaultemail@example.com">      // output shows default value since key is blank

<inject key="" defaultvalue="">   // no output as Key and default values are blank 


# Inject Keys With Static Values :
<br>
<inject key="testKey2" value="StaticValue2" key="testkay1"  value="StaticValue1" />  //Output should include value+value with copy icon

<inject key="AzureAdUserPassword" value="StaticValue3" key="testkay2"  value="StaticValue2" />  //Output should include azure password+value+value with copy icon

<inject key="AzureAdUserPassword" value="StaticValue2" key="AzureAdUserEmail" value="StaticValue1" enableCopy="false" /> // Output should include azure password+value+azure email+value without copy icon 

**Inject Keys with and without Copy icons :**
<br>
   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="true" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="true" />.

   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="false" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="false" />.
   
   
<validation step="99d5261d-60c5-4b4a-9055-705f688ffa93" />



<grouped-questions source="page2_Group_U2Zp2ae5" />
