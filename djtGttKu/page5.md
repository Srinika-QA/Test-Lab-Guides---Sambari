# Code block syntax :
<br>
1. Any sentence starts with space or Tab key shows as code block

         Example for code block using space or Tab key//
   
2. Code block using Backticks

```
public class PrimeExample
{    
 public static void main(String args[])
{    
  int i,m=0,flag=0;      
  int n=3;//it is the number to be checked    
  m=n/2;      
  if(n==0||n==1){  
   System.out.println(n+" is not prime number");      
  }else{  
   for(i=2;i<=m;i++){      
    if(n%i==0){      
     System.out.println(n+" is not prime number");      
     flag=1;      
     break;      
    }      
   }      
   if(flag==0)  { System.out.println(n+" is prime number"); }  
  }//end of else  
}    
}   
```
3. Code block without copy icon

```
<inject key="DeploymentID" enableCopy="false" />** 

```

4. code block with coloured content
   ```
   <span style="color: Blue">
   <inject key="AzureAdUserEmail"></inject>
   <inject key="AzureAdUserPassword"></inject>
   </span>
    ```

5.  Test
    ```
    <inject key="AzureAdUserPassword" style="color:blue"></inject>
    ```
