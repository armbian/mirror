<p align="center">
  <a href="#build-framework">
  <img src="https://raw.githubusercontent.com/armbian/build/master/.github/armbian-logo.png" alt="Armbian logo" width="144">
  </a><br>
  <strong>Armbian Linux Mirror Infrastructure</strong><br>
<br>
<a href=https://github.com/armbian/mirror/actions/workflows/update-list.yml><img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/armbian/mirror/Sync%20mirror?logo=googlecloud&label=List%20update&style=for-the-badge"></a>
 <br>

<br>
<a href=https://twitter.com/armbian><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/armbian?logo=twitter&style=flat-square"></a>
<a href=http://discord.armbian.com/><img alt="Discord" src="https://img.shields.io/discord/854735915313659944?label=Discord&logo=discord&style=flat-square"></a>
<a href=https://liberapay.com/armbian><img alt="Liberapay patrons" src="https://img.shields.io/liberapay/patrons/armbian?logo=liberapay&style=flat-square"></a>
</p>


## Mirroring Armbian?

We are providing rsync service for stable images (dl), repository (apt), beta , root cache and archive at:

    rsync -av rsync://rsync.armbian.com/

Alternatively you can sync most valuable date from one of our mirror that provides rsync and will probably sync faster: 

    rsync -av rsync://mirrors.dotsrc.org/armbian-dl
    rsync -av rsync://mirrors.dotsrc.org/armbian-apt

Space needs: 500Gb (images), 100Gb (packages), 200Gb (rootfs cache) and (optional) 3TB for archives

1. Setup HTTP and HTTPS hostname
2. Setup cron to sync every 2-4 hours
3. [Inform us](https://www.armbian.com/#contact)


## Images (dl.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.astra.in.ua/|Lviv|<img width=24 src=https://cdn.ipwhois.io/flags/ua.svg>|Ukraine|
|http://armbian.chi.auroradev.org/dl/|Cheyenne|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/dl/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/dl/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/dl/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/dl/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/dl/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://es-mirror.bret.dk/armbian/dl/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://fi.mirror.armbian.de/dl/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://imola.armbian.com/dl/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://mia-mirror.bret.dk/dl/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.iscas.ac.cn/armbian-releases/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian-releases/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian-releases/|Xicheng|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-dl/|Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/dl/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/dl/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian-releases/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian-releases/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian-dl/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://sg-mirror.bret.dk/armbian/dl/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://stpete-mirror.armbian.com/dl/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/dl/|Dallas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Packages (apt.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.12z.eu/apt/|Tarnowskie Gory|<img width=24 src=https://cdn.ipwhois.io/flags/pl.svg>|Poland|
|http://armbian.chi.auroradev.org/apt/|Cheyenne|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/apt/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/apt/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.systemonachip.net/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/apt/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://au-mirror.bret.dk/armbian/apt/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://es-mirror.bret.dk/armbian/apt/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://fi.mirror.armbian.de/apt/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|http://imola.armbian.com/apt/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://mia-mirror.bret.dk/apt/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.albony.xyz/armbian/|San Francisco|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirror.iscas.ac.cn/armbian/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirror.sjtu.edu.cn/armbian/|Shanghai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.aliyun.com/armbian/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian/|Xicheng|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-apt/|Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.jevincanders.net/armbian/apt/|Albany|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://mirrors.netix.net/armbian/apt/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.sustech.edu.cn/armbian/|Zhuhai|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian/|Wuhai Shi|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.xtom.de/armbian/|Düsseldorf|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://sg-mirror.bret.dk/armbian/apt/|Ashburn|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://stpete-mirror.armbian.com/apt/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/apt/|Dallas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Archive (archive.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.hosthatch.com/archive/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.systemonachip.net/archive/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/archive/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://imola.armbian.com/archive/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://stpete-mirror.armbian.com/archive/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|
|http://xogium.performanceservers.nl/archive/|Dallas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|


## Beta (beta.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|https://imola.armbian.com/beta/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://stpete-mirror.armbian.com/beta/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Cache (cache.armbian.com)

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|https://armbian.tnahosting.net/cache/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://fi.mirror.armbian.de/cache/|Helsinki|<img width=24 src=https://cdn.ipwhois.io/flags/fi.svg>|Finland|
|https://imola.armbian.com/cache/|Ljubljana|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://stpete-mirror.armbian.com/cache/|Moscow|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|

