# CBT165
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 165 IS THE ESG SECURITY SYSTEM FROM CRAIG YASUNA.         *   FILE 165
//*           THIS IS A FULLY IMPLEMENTABLE RACF-LIKE SECURITY      *   FILE 165
//*           SYSTEM AT THE LEVEL OF RACF 1.7.  THIS SYSTEM HAS     *   FILE 165
//*           BEEN OPERATIONAL AT A MEDIUM-SIZED MVS INSTALLATION.  *   FILE 165
//*           SINCE THIS SYSTEM IS VERY RACF-LIKE, CONVERSION FROM  *   FILE 165
//*           IT, TO "REAL RACF" IS QUITE PAINLESS.  HOWEVER, THIS  *   FILE 165
//*           SYSTEM MAY ELIMINATE THE NEED FOR "REAL RACF".        *   FILE 165
//*                                                                 *   FILE 165
//*           THE ESG SECURITY SYSTEM ROUTS ALL RACF CALLS THROUGH  *   FILE 165
//*           THE "RACROUTE" INTERFACE, AND ITS MODULE ICHRTX00     *   FILE 165
//*           DOES ALL THE VERIFICATIONS TO ALLOW OR DISALLOW       *   FILE 165
//*           ACCESS TO RESOURCES.  TWO IN-CORE TABLES CONTROL      *   FILE 165
//*           THE DECISIONS:  THERE IS A USERID TABLE AND A         *   FILE 165
//*           PROFILE TABLE.  THERE IS NO DATABASE, BUT UPDATES     *   FILE 165
//*           ARE EASILY AND QUICKLY MADE TO THE TABLES BY AN       *   FILE 165
//*           ADMINISTRATOR, WHO MAY NOT HAVE TO DO TOO MUCH WORK   *   FILE 165
//*           AFTER THE SYSTEM HAS BEEN INITIALLY SET UP.  USERID   *   FILE 165
//*           AND PROFILE TABLE RECORDS ARE NEARLY IDENTICAL IN     *   FILE 165
//*           FORMAT TO THOSE OF RACF ITSELF.                       *   FILE 165
//*                                                                 *   FILE 165
//*           TWO STANDARD RACF MANUALS MAY BE USED TO HELP IN      *   FILE 165
//*           SECURITY SETUP AND ADMINISTRATION.  THESE ARE:  RACF  *   FILE 165
//*           ADMINISTRATOR'S GUIDE (SC28-1340) AND SPL RACF        *   FILE 165
//*           (SC28-1343).                                          *   FILE 165
//*                                                                 *   FILE 165
//*           BASIC DOCUMENTATION FOR THE SECURITY PACKAGE IS       *   FILE 165
//*           SUPPLIED IN MEMBER $$$$$DOC OF THIS FILE.             *   FILE 165
//*                                                                 *   FILE 165
```
