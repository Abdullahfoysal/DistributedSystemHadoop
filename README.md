# DistributedSystemHadoop

# Question1: Output

```
  root@4b935d6781d0:/# hadoop jar FileCount.jar input finalFileCount
  2021-11-14 09:21:20,673 INFO sasl.SaslDataTransferClient: SASL encryption trust check: localHostTrusted = false, remoteHostTrusted = false
  10.99.99.186	6

```


# Question2: Output

```
  root@4b935d6781d0:/# hdfs dfs -cat finalFileCount/part-r-00000
  2021-11-14 09:25:42,440 INFO sasl.SaslDataTransferClient: SASL encryption trust check: localHostTrusted = false, remoteHostTrusted = false
  /assets/js/the-associates.js	2456


```


# Question3: Output
```
  root@4b935d6781d0:/# hdfs dfs -head sorted2/output/part-r-00000

  117352	/assets/css/combined.css
  106818	/assets/js/javascript_combined.js
  99308	/
  98744	/assets/img/home-logo.png
  93162	/assets/css/printstyles.css
  91934	/images/filmpics/0000/3695/Pelican_Blood_2D_Pack.jpg
  66835	/favicon.ico
  51975	/robots.txt
  39591	/images/filmpics/0000/3139/SBX476_Vanquisher_2d.jpg
  38990	/assets/img/search-button.gif
  34151	/assets/img/play_icon.png
  32533	/images/filmmediablock/290/Harpoon_2d.JPG
  29377	/assets/img/x.gif
  29243	/images/filmpics/0000/1421/RagingPhoenix_2DSleeve.jpeg
  25955	/release-schedule/
  24292	/assets/img/release-schedule-logo.png
  23055	/search/
  22129	/assets/img/banner/ten-years-banner-grey.jpg
  22121	/assets/img/banner/ten-years-banner-white.jpg
  21930	/assets/img/banner/ten-years-banner.png
  18940	/release-schedule
  17208	/assets/img/banner/ten-years-banner-black.jpg
  13466	/images/filmmediablock/293/NewsMakers_2DBluRay.jpeg
  11503	/images/clientlogos/0000/0010/Manga.jpg
  11318	/images/filmmediablock/39/bluray_pontypool2d_new.jpg
```


# Question4: Output
```
  root@4b935d6781d0:/# hdfs dfs -head sorted2/output/part-r-00000

  117352	/assets/css/combined.css
  106818	/assets/js/javascript_combined.js
  99308	/
  98744	/assets/img/home-logo.png
  93162	/assets/css/printstyles.css
  91934	/images/filmpics/0000/3695/Pelican_Blood_2D_Pack.jpg
  66835	/favicon.ico
  51975	/robots.txt
  39591	/images/filmpics/0000/3139/SBX476_Vanquisher_2d.jpg
  38990	/assets/img/search-button.gif
  34151	/assets/img/play_icon.png
  32533	/images/filmmediablock/290/Harpoon_2d.JPG
  29377	/assets/img/x.gif
  29243	/images/filmpics/0000/1421/RagingPhoenix_2DSleeve.jpeg
  25955	/release-schedule/
  24292	/assets/img/release-schedule-logo.png
  23055	/search/
  22129	/assets/img/banner/ten-years-banner-grey.jpg
  22121	/assets/img/banner/ten-years-banner-white.jpg
  21930	/assets/img/banner/ten-years-banner.png
  18940	/release-schedule
  17208	/assets/img/banner/ten-years-banner-black.jpg
  13466	/images/filmmediablock/293/NewsMakers_2DBluRay.jpeg
  11503	/images/clientlogos/0000/0010/Manga.jpg
  11318	/images/filmmediablock/39/bluray_pontypool2d_new.jpg
```
