## Hi there 👋 Thank you for visiting @LearningKijo
<a href="https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/"><img src="https://img.shields.io/badge/Azure-KQL-00B2FF.svg?logo=microsoftazure&style=popout"></a>
<a href="https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/"><img src="https://img.shields.io/badge/Azure%20Data%20Explorer-%230078D4.svg?&style=popout&logo=azure%20data%20explorer&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/kijo-niimura/"><img src="https://img.shields.io/badge/-Linkedin-0077B5.svg?logo=linkedin&style=popout"></a>

I’m @LearningKijo and I am mainly going to cover two topics: 1) KQL and 2) Malware analysis.<br>
Regarding KQL, providing KQL learning process & tips and "out-of-the-box KQL queries" for hunting advanced cyber-attacks. <br>
In the malware analysis section, observing malware activities - basic static analysis and basic dynamic analysis.

#### Here is my focus <br>
```
# Kusto query language(KQL) 
# Cyberattack - APT29, AiTM, Ransomeware
# Microsoft Security solution <Defenders> against cyberattack
# Incident Response, API, Automation
# Malware analysis
      - Statis analysis
      - Dynamic analysis
      - Reverse engineering 
      
# Experience
let MicrosoftProducts = datatable(id: int, value: string)
[
      1, "Microsoft Defender for Endpoints", 
      2, "Microsoft Defender for Office 365", 
      3, "Microsoft Defender for Cloud Apps", 
      4, "Microsoft Defender for Identity", 
      5, "Microsoft Defender Antivirus", 
      6, "Microsoft Sentinel"
];
MicrosoftProducts
| project id, value

```

#### Disclaimer 
The views and opinions expressed herein are those of the author and do not necessarily reflect the views of company.
