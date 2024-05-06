# salesforce-developer1
declarative / programatically app
1-to create a new app go to app manager

2-
====================================================create apex code
global class TestPageController {
    global Account[] accountList{
        get{
            return [SELECT Id, Name FROM Account];
        }
    }
}
==================================================create visualforce page
<apex:page controller="TestPageController">
  <apex:pageBlock title="Accounts">
      <apex:pageBlockTable value="{!accountList}" var="account">
         <apex:column value="{!account.Name}"/>
      </apex:pageBlockTable>
   </apex:pageBlock>
</apex:page>
               
