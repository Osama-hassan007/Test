# Deployment Sessions

# Deployment Steps : 

   ## Prerequisites :
   - CRQ 
   - Jira ticket
   - mail
   - Remedy file
   ## Process :
   - backup from the latest deployment version
   - GH configuration per jira ticket
   - Jenkins pipeline  "[Old way:common-jenkins-job](https://jenkins.dxl-prod.aws.cps.vodafone.com/job/VF_AL_DXL/job/COMMON-JENKINS-JOB/) " or "[New way:Dxl-common-jenkins-job](https://jenkins.dxl-prod.aws.cps.vodafone.com/job/VF_AL_DXL/job/DXL-COMMON-JENKINS-JOB/)"       
  ## Logs : 
   - check logs from:
     **Splunk - instant - cluster**
 
### Notes :
             * number of deployments per day approximately 5 ~ 7 deployment case
             * not all MS migrated to separate repos 
             * Access for :GH ,Instana,Splunk,PagerDuty,Jenkins - Requested 
             * List of approvers -Requested
             * Mail format granted
             * CAP details & Operational support model -Requested
 
 
 
## Board approver :
 
- ovidiu.nemes1@vodafone.com
- eva.ringertzpolaskova@vodafone.com
- tarek.hashem@vodafone.com
  
**we usually reach out to the above two we only reach to the rest is in case they are on leave**
 
 
 
# Mail details:
 
To: Global Service Desk, Vodafone Group <GSD@Vodafone.com>; Applications Monitoring <Applications.Monitoring@vodafone.com>; DL-VISPL_TSSC_CONSUMER <DL-VISPL_TSSC_CONSUMER@vodafone.com>; 1stLevelApplicationOperationSupport, Vodafone Group <1stLevelApplicationOperationSupport@vodafone.com>; 'Gongolidis, Evangelos, Vodafone Greece' <evangelos.gongolidis@vodafone.com>; 'Nagi, Amira, Vodafone Egypt' <Amira.Nagi@vodafone.com>; Luis Monteiro, Vodafone (External) <luis.monteiro@vodafone.com>; 'AbdElGhaffar, Doaa, Vodafone Egypt' <Doaa.AbdElGhaffar@vodafone.com>; Mostafa Taher, Vodafone <mustafa.abdelhalim@vodafone.com>; Christos Sotiriou, Vodafone <christos.sotiriou@vodafone.com>; Georgios Kontogiannis, Vodafone <Georgios.Kontogiannis@vodafone.com>; 'Abdelghafar, Doaa, Vodafone Group' <doaa.abdelghaffar1@vodafone.com>; 'Michalopoulos, Ioannis, Vodafone Greece' <ioannis.michalopoulos@vodafone.com>; DL-DXL-DEVOPS <dl-dxl-devops@vodafone.com>
 
CC: DL-MTC-TC-GW <DL-MTC-TC-GW@vodafone.com>; DL-MTC-TC-EP <DL-MTC-TC-EP@vodafone.com>; DL-GT_Info_Partner <DL-GT_Info_Partner@vodafone.com>; DL-CP&S-DeviceProducts <DL-P&S-ET-DeviceApps-DeviceManagement@internal.vodafone.com>; Change Mgmt GA for VT P&S <ga-for-vtps.changemanagement@vodafone.com>; DL-MTC-TC-GW-MICROSERVICE <DL-MTC-TC-GW-MICROSERVICE@vodafone.com>; Giazitzoglou, Nikolaos, INTRASOFT <nikolaos.giazitzoglou@vodafone.com>; 'Tziris, Nikolaos, Vodafone Greece' <nikolaos.tziris@vodafone.com>; 'Magdy, Shireen, Vodafone Group' <shireen.magdy1@vodafone.com>; 'Dina Mohammad, Vodafone' <dina.mohammad1@vodafone.com>; Shereen ElSebai, Vodafone <Shereen.ElSebai@vodafone.com>; Leivadara, Vanessa, Vodafone <vanessa.leivadara@vodafone.com>; 'Filippis, Chris, Vodafone Greece' <chris.filippis@vodafone.com>; 'Athanasiou, Konstantinos, Vodafone' <konstantinos.athanasiou@vodafone.com>; 'Pitsios, Vlasis, Vodafone' <vlasis.pitsios@vodafone.com>; Gelmpesis, Alexandros, INTRASOFT <alexandros.gelmpesis@vodafone.com>; Serkid Brahimaj, Vodafone <serkid.brahimaj@vodafone.com>; Georgios Lamprinakos, Vodafone <Georgios.Lamprinakos@vodafone.com>; Deregibus, Giordano, Vodafone <giordano.deregibus1@vodafone.com>; Fatma Fahim, Vodafone <fatma.fahim@vodafone.com>; Orfanos, Spiros, Vodafone Greece (External) <Spiros.ORFANOS@intrasoft-intl.com>; Spentzas, Theocharis, Vodafone <theocharis.spentzas@vodafone.com>; Vanessa Tzialla, Vodafone <vanessa.tzialla@vodafone.com>; Seirlis, Konstantinos, Vodafone <konstantinos.seirlis@vodafone.com>; Muhammed, Emam, Vodafone <imam.muhammed@vodafone.com>; 'Dina Mohammad, Vodafone' <dina.mohammad1@vodafone.com>; Siarras, Theocharis, Vodafone <theocharis.siarras@vodafone.com>; Makrynakis, Nikiforos, Vodafone <nikiforos.makrynakis@vodafone.com>; 'Kontogeorgos, Ioannis, Vodafone' <ioannis.kontogeorgos@vodafone.com>; Alexandros Kazantzidis, Vodafone (External) <alexandros.kazantzidis@vodafone.com>; Gelmpesis, Alexandros, INTRASOFT <alexandros.gelmpesis@vodafone.com>; Paraskakis, Ioannis, Vodafone Greece <ioannis.paraskakis@vodafone.com>; Gkoros, Christos, Vodafone <christos.gkoros@vodafone.com>; Makrynakis, Nikiforos, Vodafone <nikiforos.makrynakis@vodafone.com>; Orestis Giannakopoulos-Karakontis, Vodafone <orestis.giannakopouloskarakontis@vodafone.com>; 'Sdongos, Thomas, Vodafone' <thomas.sdongos@vodafone.com>; Vanessa Tzialla, Vodafone <vanessa.tzialla@vodafone.com>; Palladinos, Apostolos, INTRASOFT <apostolos.palladinos@vodafone.com>; DL-DXL-DEVOPS <dl-dxl-devops@vodafone.com>; Mahmoud Maghraby, Vodafone <mahmoud.maghraby@vodafone.com>; Marian Maher, Vodafone <Marian.Maher@vodafone.com>; Serkid Brahimaj, Vodafone <serkid.brahimaj@vodafone.com>

**Subject: CRQ000030804919 will start at {{9:00 AM IST }}**

|CRQ| CRQ000030804919|
|-----|--------|
|Class|Normal|
|0OpCo|DXL_GR|
|Subject|DXL-7283/payment-js-v2,DXL-7286/ott-order-listener-fs|
|Deployment contact|Chinmayi Dhole (+91 7387454348)|
|Requester|Hickson, Michael|
|Component|payment-js-v2 ott-order-listener|
|Servers affected|DxL cluster :- dxl-prod-gr|
|Priority|Low|
|Impact|4-Minor/Localized|
|Downtime|None|
|Verification||
|Result||

## CRQ Format
<img width="956" alt="MicrosoftTeams-image" src="https://github.com/Osama-hassan007/Test/assets/119705658/8330b732-f3a3-4440-9982-f808ca7306c6">

#### Summery:- 
- jira/name of ms
  
#### Notes:- 
      
```bash
*There are a form for notes at CRQ*
     
        --- Begin of required information ---
 
 ---------------------------------------------------------------------------
 | Reason for Change 
 | # enter the reason for the change including a short description of it
 ---------------------------------------------------------------------------
<DXL-7253/[LIVE] digital-identity-management-fs release>
-----------------------------------------
 | Negative effects if change is not implemented
 | # describe impact if change is not implemented 
 ---------------------------------------------------------------------------
<DXL-7253/[LIVE] digital-identity-management-fs release will not be possible>
 ---------------------------------------------------------------------------
 | General Impact
 | # describe the impact of the change in regards to the service
 ---------------------------------------------------------------------------
 < none >
 
 ---------------------------------------------------------------------------
 | Test Scenario
 | # provide information about the executed test
 | 
 | possible choices: (one of them is sufficient)
 |  - a) describe executed test: description of test, result, used environment
 |  - b) attach the test report (must include information of a) )
 |  - c) provide a CRQ Number of a change, which was successfully implemented with the same change/test scenario
 |  - d) point out that no test environment is available
 ---------------------------------------------------------------------------
 < a) Tested in preprod>
 
 ---------------------------------------------------------------------------
 | Affected Configuration items
 | # Which configuration items are affected
 ---------------------------------------------------------------------------
 < DXL-cluster: dxl-prod-gr name space >
 
 ---------------------------------------------------------------------------
 | Affected OpCo/customers
 | # Which OpCo is affected please use abbreviations like ES, UK, NL, DE
 ---------------------------------------------------------------------------
 <GR>
 
 ---------------------------------------------------------------------------
 | Plan and Prerequisite 
 | # Confirm that Implementation Procedure, Fallback Procedure, Sercurity Prerequisities
 | and a Recent backup are all available
 |
 |Possible choices:
 | - Yes
 | - No with an explanation below  
 ---------------------------------------------------------------------------
 < Yes> 

--- End of required information ---
```
## Links for deployment Shadowing sessions :
  - [GR Shadowing - Prod Actual Deployment 1](https://vodafone.sharepoint.com/sites/DevOpsAsAService/_layouts/15/stream.aspx?id=%2Fsites%2FDevOpsAsAService%2FShared%20Documents%2FOnboarding%20%2D%20All%20OPCOS%2FOnboarding%20Plan%2FGR%20DXL%2FDXL%20Prod%20Shadowing%20Sessions%2F1%2DGR%20Shadowing%20%2D%20Prod%20Actual%20Deployment%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)
  - [GR Shadowing - Prod Actual Deployment 2](https://vodafone.sharepoint.com/sites/DevOpsAsAService/_layouts/15/stream.aspx?id=%2Fsites%2FDevOpsAsAService%2FShared%20Documents%2FOnboarding%20%2D%20All%20OPCOS%2FOnboarding%20Plan%2FGR%20DXL%2FDXL%20Prod%20Shadowing%20Sessions%2F2%2DGR%20Shadowing%20%2D%20Prod%20Actual%20Deployment%202%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)
  - [GR Shadowing - CRQ Details](https://vodafone.sharepoint.com/sites/DevOpsAsAService/_layouts/15/stream.aspx?id=%2Fsites%2FDevOpsAsAService%2FShared%20Documents%2FOnboarding%20%2D%20All%20OPCOS%2FOnboarding%20Plan%2FGR%20DXL%2FDXL%20Prod%20Shadowing%20Sessions%2F3%2DGR%20Shadowing%20%2D%20CRQ%20Details%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)
## Links :
  - [Jenkins](https://jenkins.dxl-prod.aws.cps.vodafone.com/)
  - [Jira](https://cps.jira.agile.vodafone.com/secure/RapidBoard.jspa?rapidView=32491&quickFilter=47545)
  - [Mongodp](https://cloud.mongodb.com/v2/5b02b4140bd66b26e1d1ac3e#/clusters/detail/DXL-GR-PROD)
  - [Remedy](https://oneitsm.onbmc.com/arsys/forms/onbmc-s/SHR%3ALandingConsole/Default+Administrator+View/?cacheid=744a04ca)
  - [Instana](https://vodafone-vodafone.instana.io/#/home)
  - [Splunk](https://opsanalytics.vodafone.com/en-US/app/launcher/home)
    
