# Svitlo GNU/Linux is an independent distribution created in Ukraine
<p><a href="example-uk.md"> ➡️ Українською </a></p>



**The basic system is created using docker
We start the assembly of the docker system**

[![Build Docker Container](https://res.cloudinary.com/marcomontalbano/image/upload/v1679222804/video_to_markdown/images/youtube--DtVHRhtbbnA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=DtVHRhtbbnA&t=24s "Build Docker Container")


**We start the docker to assemble the operating system**

[![Run Container - Svitlo Independent GNU/Linux Distribution](https://res.cloudinary.com/marcomontalbano/image/upload/v1679222729/video_to_markdown/images/youtube--MA8ZIM1aWFw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=MA8ZIM1aWFw&t=24s "Run Container - Svitlo Independent GNU/Linux Distribution")


**A basic system is created**

[![Build code - Svitlo Independent GNU/Linux Distribution](https://res.cloudinary.com/marcomontalbano/image/upload/v1679222546/video_to_markdown/images/youtube--3LAz1xeGp3g-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=3LAz1xeGp3g&t=71s "Build code - Svitlo Independent GNU/Linux Distribution")


**We check the login to the new system and the Internet connection**

[![Run - Svitlo Independent GNU/Linux Distribution ](https://res.cloudinary.com/marcomontalbano/image/upload/v1679222653/video_to_markdown/images/youtube--ONv6p2ZQTZY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ONv6p2ZQTZY&t=24s "Run - Svitlo Independent GNU/Linux Distribution ")




### Download svitlo.img.zs (2.8 GB) then extract file svitlo.img (10 GB)
<p><a href="https://svitlo-source.kachanyuk.com/download/linux/svitlo/img/v0.2/svitlo.img.zst"> ➡️ svitlo.img </a></p>


### Install zstd
<p><a href="https://github.com/facebook/zstd/releases/tag/v1.5.4"> ➡️ zstd </a></p>

### Verify 

**sha512sum svitlo.img**
1e89e38e42497ceb4e981148f3608bdcbdc4b3d00bf387eae3ebd2916e5e6dbf182a25b54438398e7978243055f859488771b0edb5c7edb0ddf6708fbbd5d21f

**sha512sum svitlo.img.zst**
5840bd1762231b1fd96d66a7f48dbcdb0ec93897d18e0d7f17191d6df98e3f71e462f144cccbad1541e6e2a36364d41dd328592d32de1549d8a41ab338b4e250


#### Launch option
qemu-system-x86_64 -drive format=raw,file=svitlo.img -net nic -net user

`login: root
password: password`





> #### Copyright (C) 2023 Yurii Kachaniuk - Ukraine <wku@ukr.net>
