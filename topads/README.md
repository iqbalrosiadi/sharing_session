# shinyapps-data-analyst
an Accio Repository for Data Analyst Team.

## What is Accio?
Accio is an R-Shiny based web application that allows users to download raw data directly from BigQuery. It is deployed on top of Albus platform.

## Why Accio?
Since R-Shiny is open source, it will not charge the license of a user account. It is different from Tableau which charges per user account with various licensing types (view, explorer, creator). Accio will only charge BigQuery costs that users pull. To conclude, we only pay as we use.

## How Accio works?
Basically, accio is a query builder. Input from the user is used to build the logic of the query (query string manipulation) to pull data. The generated query will result in an R dataframe. When users click the download button, R-Shiny will export it into csv. There are actually many ways to do this in R-Shiny and this tutorial gives you one of the basic examples (kindly please share to us if you have a better approach 😊).

### Useful Link
- Current best practice to develop Accio, you can read the material here :  [How to develop Accio]
- Basic Concept of Github, created by DA github team can be accessed here : [Github Concept]
- You can learn how to push to github by reading this link [How to Git]
- If you're new on github, you need to install gitbash application by following the steps on this link [How to Install]
- If something happened, then you can try to troubleshoot it by following the steps here [How to Troubleshoot]

### Naming convention
Your Github Branch  **must follow** this naming convention :

``
[accio_id_production]_[Tribe Name]_[Project_name]
``

Example :
``51_sample_project_satu``\
You can ask **Accio ID** Production to DA Governance team 

This is naming convention for tribe that you can use on folder and github branch :
| Tribe | Tribe name folder |
| ------ | ------ |
| Analytics Platform - Engineering | analytics_platform |
| Analytics Governance | analytics_governance |
| COE | coe |
| TopAds | topads |
| Ads Sales | ads_sales |
| IM (Strategist, Specialist, Partnership) | internet_marketing |
| OM (Offline media, Brand) | offline_media |
| Risk | risk |
| PGSO (PGC Campaign Insight, PGC Category Insight, PGC Insight, PGC Sales & Marketing, PGC Campaign Operations, RGX, MBKF & HL, Fashions, FMCG, HEL, ASH) | pg_so |
| Logistic and Fullfilment | logistic_fullfilment |
| New Retail | new_retail |
| PGP (Seller Platform {Order, Growth, IMS, Seller Home}, Shop and Analytics {Shop, Price Competitiveness, Seller Stats}, Category and Browse {CLP, Trade In Money In, Category Experience}, RAD ,C&PS, GM, Edu, Salam Experience) | pg_product |
| Content (Play, Feed, Affiliate) | content |
| ComMed (Comms Service, Comms Platform & CM, SEO, W2A, Deeplink, Sharing Experience) | commed |
| Search (Keyword, Ranking, Search Content, Product List, Annotation) | search |
| Home & Personalization (Home, Disco Page, Perso Front Funnel, Perso Back Funnel, Perso Content) | home_personalization |
| Purchase Platform (Purchase Experience, Purchase Engine, Order Management Platform) | purchase_platform |
| PDP (Integration, Features, Eligibility Validation) | pdp |
| Account & User (Account, User Platform) | account_user |
| BGP (Retention & Loyalty, Engagement & Gamification, Promotion Platform) | bgp |
| Fintech | fintech |
| Payment | payment |
| DG | digital |
| LS | local_service |
| Operation & CeX | ops_cex |




[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [How to develop Accio]: <https://tokopedia.atlassian.net/wiki/spaces/DAS/pages/1377568136/How+to+develop+Accio#What-is-Accio%3F>
   [How to Git]: <https://tokopedia.atlassian.net/wiki/spaces/DAS/pages/1431834998/Step+for+Data+Analyst+to+Push+Accio+to+Github>
   [How to Install]: <https://tokopedia.atlassian.net/wiki/spaces/DAS/pages/1431769881/Install+Gitbash+Initial+Configuration>
   [How to Troubleshoot]: <https://tokopedia.atlassian.net/wiki/spaces/DAS/pages/1431442924/Github+Troubleshooting>
   [Github Concept]: <https://docs.google.com/presentation/d/19tGwYHbOSb-l5GOV5yAKo0xPDH_Dtds7f8C07X_l-Lw/edit?ts=6010ddb5#slide=id.g8ffe6315f1_5_1176>



