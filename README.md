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

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.astra.in.ua/|Lviv|<img width=24 src=https://cdn.ipwhois.io/flags/ua.svg>|Ukraine|
|http://armbian.chi.auroradev.org/dl/|West Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/dl/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/dl/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/dl/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/dl/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/dl/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://es-mirror.bret.dk/armbian/dl/|Madrid|<img width=24 src=https://cdn.ipwhois.io/flags/es.svg>|Spain|
|http://fi.mirror.armbian.de/dl/|Tuusula|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://mirror.iscas.ac.cn/armbian-releases/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian-releases/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian-releases/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-dl/|Copenhagen|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/dl/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/dl/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian-releases/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian-releases/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian-dl/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://sg-mirror.bret.dk/armbian/dl/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/dl/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/dl/|Newark|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Packages (apt.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.chi.auroradev.org/apt/|West Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/apt/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/apt/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.systemonachip.net/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/apt/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/apt/|Sydney|<img width=24 src=https://cdn.ipwhois.io/flags/au.svg>|Australia|
|http://es-mirror.bret.dk/armbian/apt/|Madrid|<img width=24 src=https://cdn.ipwhois.io/flags/es.svg>|Spain|
|http://fi.mirror.armbian.de/apt/|Tuusula|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://mirror.iscas.ac.cn/armbian/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirror.sjtu.edu.cn/armbian/|Shanghai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-apt/|Copenhagen|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/apt/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/apt/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.sustech.edu.cn/armbian/|Zhuhai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.xtom.de/armbian/|Düsseldorf|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://sg-mirror.bret.dk/armbian/apt/|Singapore|<img width=24 src=https://cdn.ipwhois.io/flags/sg.svg>|Singapore|
|http://stpete-mirror.armbian.com/apt/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/apt/|Newark|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Archive (archive.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.hosthatch.com/archive/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.systemonachip.net/archive/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/archive/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://imola.armbian.com/archive/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://stpete-mirror.armbian.com/archive/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/archive/|Newark|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Beta (beta.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|https://imola.armbian.com/beta/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://stpete-mirror.armbian.com/beta/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Cache (cache.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|https://armbian.tnahosting.net/cache/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://fi.mirror.armbian.de/cache/|Tuusula|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://imola.armbian.com/cache/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://stpete-mirror.armbian.com/cache/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|

