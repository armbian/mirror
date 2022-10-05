<h3 align=center><a href="#build-tools"><img src="https://raw.githubusercontent.com/armbian/build/master/.github/armbian-logo.png" alt="Armbian logo" width="144"></a><br>mirror sync</h3>
<p align=right>&nbsp;</p>

## Mirroring Armbian?

We are providing rsync service for stable images (dl), repository (apt), beta (beta) and archive (archive) at:

    rsync -av rsync://rsync.armbian.com/

Alternatively you can sync most valuable date from one of our mirror that provides rsync and is much faster: 

    rsync -av rsync://mirrors.dotsrc.org/armbian-dl
    rsync -av rsync://mirrors.dotsrc.org/armbian-apt

Space needs: 500Gb (images), 100Gb (packages) and (optional) 3TB for archives

1. Setup HTTP and HTTPS hostname
2. Setup cron to sync every 2-4 hours
3. [Inform us](https://www.armbian.com/#contact)


## Images (dl.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.astra.in.ua/|Lviv|<img width=24 src=https://cdn.ipwhois.io/flags/ua.svg>|Ukraine|
|http://armbian.chi.auroradev.org/dl/|Washington|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/dl/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/dl/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/dl/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/dl/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/dl/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://es-mirror.bret.dk/armbian/dl/|Madrid|<img width=24 src=https://cdn.ipwhois.io/flags/es.svg>|Spain|
|http://fi.mirror.armbian.de/dl/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://kr.mirrors.naho.moe/armbian/dl/|Seoul|<img width=24 src=https://cdn.ipwhois.io/flags/kr.svg>|Korea|
|http://mirror-eu-de1.armbian.airframes.io/dl/|Munich|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://mirror-us-phx1.armbian.airframes.io/dl/|Phoenix|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-sea1.armbian.airframes.io/dl/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-sea2.armbian.airframes.io/dl/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-stl1.armbian.airframes.io/dl/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.iscas.ac.cn/armbian-releases/|Mentougou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian-releases/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian-releases/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-dl/|Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/dl/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/dl/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian-releases/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian-releases/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian-dl/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://sg-mirror.bret.dk/armbian/dl/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/dl/|Malaya|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/dl/|Haarlem|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|


## Packages (apt.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.chi.auroradev.org/apt/|Washington|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/apt/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/apt/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.systemonachip.net/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/apt/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/apt/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://es-mirror.bret.dk/armbian/apt/|Madrid|<img width=24 src=https://cdn.ipwhois.io/flags/es.svg>|Spain|
|http://fi.mirror.armbian.de/apt/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://ftp.ubuntu-tw.org/mirror/armbian/apt/|Taichung|<img width=24 src=https://cdn.ipwhois.io/flags/tw.svg>|Taiwan|
|http://kr.mirrors.naho.moe/armbian/apt/|Seoul|<img width=24 src=https://cdn.ipwhois.io/flags/kr.svg>|Korea|
|http://mirror-eu-de1.armbian.airframes.io/apt/|Munich|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://mirror-us-phx1.armbian.airframes.io/apt/|Phoenix|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-sea1.armbian.airframes.io/apt/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-sea2.armbian.airframes.io/apt/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror-us-stl1.armbian.airframes.io/apt/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.albony.xyz/armbian/|Sao Paulo|<img width=24 src=https://cdn.ipwhois.io/flags/br.svg>|Brasil|
|http://mirror.iscas.ac.cn/armbian/|Mentougou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirror.ossplanet.net/armbian/apt/|Taichung|<img width=24 src=https://cdn.ipwhois.io/flags/tw.svg>|Taiwan|
|http://mirror.sjtu.edu.cn/armbian/|Shanghai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-apt/|Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/apt/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/apt/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.sustech.edu.cn/armbian/|Zhuhai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.xtom.de/armbian/|Düsseldorf|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://sg-mirror.bret.dk/armbian/apt/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/apt/|Malaya|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/apt/|Haarlem|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|


## Archive (archive.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|http://armbian.hosthatch.com/archive/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.systemonachip.net/archive/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/archive/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://fi.mirror.armbian.de/archive/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://ftp.yandex.ru/mirrors/armbian/archive/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://imola.armbian.com/archive/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://stpete-mirror.armbian.com/archive/|Malaya|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/archive/|Haarlem|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|


## Beta (beta.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|https://fi.mirror.armbian.de/beta/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://imola.armbian.com/beta/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://stpete-mirror.armbian.com/beta/|Malaya|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Cache (cache.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country|
|:--|:--|:--:|--:|
|https://armbian.tnahosting.net/cache/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://fi.mirror.armbian.de/cache/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://imola.armbian.com/cache/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://kr.mirrors.naho.moe/armbian/cache/|Seoul|<img width=24 src=https://cdn.ipwhois.io/flags/kr.svg>|Korea|
|https://mirror-eu-de1.armbian.airframes.io/cache/|Munich|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|https://mirror-us-phx1.armbian.airframes.io/cache/|Phoenix|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-sea1.armbian.airframes.io/cache/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-sea2.armbian.airframes.io/cache/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirror-us-stl1.armbian.airframes.io/cache/|Saint Louis|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://mirrors.aliyun.com/armbian-cache/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://stpete-mirror.armbian.com/cache/|Malaya|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|

