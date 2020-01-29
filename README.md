![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# SQL Standard Edition Supports AlwaysOn
**Post Date: May 18, 2016**        



## Contents    
- [About Process](##About-Process)  
- [SQL Logic](#SQL-Logic)  
- [Build Info](#Build-Info)  
- [Author](#Author)  
- [License](#License)       

## About-Process

<p>A common question that comes up from time to time is… What SQL Server Edition supports AlwaysOn? The answer is YES IT DOES. There is some confusion around this topic as Microsoft has traditionally kept it's Cluster (High Availability Solutions) reserved as a premium or 'Enterprise Level' feature. However; in this case SQL Server 2012 Standard does support the AlwaysOn configurations:
MSDN Reference: https://msdn.microsoft.com/en-us/library/cc645993(v=sql.110).aspx
See the image below:</p>

![Standard Edition Supports AlwaysOn]( https://mikesdatawork.files.wordpress.com/2016/05/image001.jpg "AlwaysOn Support For Standard Edition")
 
Another common follow-up question to this is… What Windows Server Edition supports AlwaysOn? The answer to this is Server 2012 STANDARD. Yes. Thats right! I said Server 2012 Standard. Microsoft has included the Failover Cluster feature in Windows Standard editions.
Here's some screenshot to further illustrate the point.
Here's a garden variety Windows Server R2 installation.

![Windows Server]( https://mikesdatawork.files.wordpress.com/2016/05/sql-server-2012-r2-standard.png "2012 Windows Server")
 
If you go to features…

![Go To Features]( https://mikesdatawork.files.wordpress.com/2016/05/add-roles-and-features.png "Go To Features")
 
You'll see the Failover feature exists, and has already been selected. I selected it and installed it to be sure it's functional and it is.

![Select Failover Clustering]( https://mikesdatawork.files.wordpress.com/2016/05/failover-cluster-feature.png "Click Failover Clustering")
 

[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)


## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

