<h3 align=center><a href="#build-tools"><img src="https://raw.githubusercontent.com/armbian/build/master/.github/armbian-logo.png" alt="Armbian logo" width="144"></a><br>mirror sync</h3>
<p align=right>&nbsp;</p>

[![Sync mirror](https://github.com/armbian/mirror/actions/workflows/mirror-sync.yml/badge.svg)](https://github.com/armbian/mirror/actions/workflows/mirror-sync.yml) [![Rootfs sync](https://github.com/armbian/mirror/actions/workflows/rootfs-sync.yml/badge.svg)](https://github.com/armbian/mirror/actions/workflows/rootfs-sync.yml)
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


## Images

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|https://armbian.chi.auroradev.org/dl/|Cheyenne|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://armbian.hosthatch.com/dl/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|https://armbian.lv.auroradev.org/dl/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://armbian.site-meganet.com/dl/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|https://armbian.tnahosting.net/dl/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://github.com/armbian/mirror/releases/download/|San Francisco|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|https://imola.armbian.com/dl/|Maribor|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|https://mirror.12z.eu/pub/linux/armbian/dl/|Montreal|<img width=24 src=https://cdn.ipwhois.io/flags/ca.svg>|Canada|
|https://mirror.armbian.de/dl/|Nuremberg|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|https://mirrors.bfsu.edu.cn/armbian-releases/|Xicheng|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://mirrors.dotsrc.org/armbian-dl/|Kongens Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|https://mirrors.netix.net/armbian/dl/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|https://mirrors.nju.edu.cn/armbian-releases/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://mirrors.tuna.tsinghua.edu.cn/armbian-releases/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://mirrors.ustc.edu.cn/armbian-dl/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|https://stpete-mirror.armbian.com/dl/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|


## Packages

|URL &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  |City &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |Flag|Country &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|:--|:--|:--:|--:|
|http://armbian.12z.eu/apt/|Tarnowskie Gory|<img width=24 src=https://cdn.ipwhois.io/flags/pl.svg>|Poland|
|http://armbian.chi.auroradev.org/apt/|Cheyenne|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.hosthatch.com/apt/|Amsterdam|<img width=24 src=https://cdn.ipwhois.io/flags/nl.svg>|Netherlands|
|http://armbian.lv.auroradev.org/apt/|Las Vegas|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://armbian.site-meganet.com/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.systemonachip.net/apt/|Roubaix|<img width=24 src=https://cdn.ipwhois.io/flags/fr.svg>|France|
|http://armbian.tnahosting.net/apt/|Chicago|<img width=24 src=https://cdn.ipwhois.io/flags/us.svg>|United States|
|http://imola.armbian.com/apt/|Maribor|<img width=24 src=https://cdn.ipwhois.io/flags/si.svg>|Slovenia|
|http://mirror.12z.eu/pub/linux/armbian/apt/|Montreal|<img width=24 src=https://cdn.ipwhois.io/flags/ca.svg>|Canada|
|http://mirror.armbian.de/apt/|Nuremberg|<img width=24 src=https://cdn.ipwhois.io/flags/de.svg>|Germany|
|http://mirrors.aliyun.com/armbian/|Hangzhou|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.bfsu.edu.cn/armbian/|Xicheng|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.dotsrc.org/armbian-apt/|Kongens Lyngby|<img width=24 src=https://cdn.ipwhois.io/flags/dk.svg>|Denmark|
|http://mirrors.netix.net/armbian/apt/|Sofia|<img width=24 src=https://cdn.ipwhois.io/flags/bg.svg>|Bulgaria|
|http://mirrors.nju.edu.cn/armbian/|Nanjing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.tuna.tsinghua.edu.cn/armbian/|Beijing|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://mirrors.ustc.edu.cn/armbian/|Hefei|<img width=24 src=https://cdn.ipwhois.io/flags/cn.svg>|China|
|http://stpete-mirror.armbian.com/apt/|Saint Petersburg|<img width=24 src=https://cdn.ipwhois.io/flags/ru.svg>|Russia|

