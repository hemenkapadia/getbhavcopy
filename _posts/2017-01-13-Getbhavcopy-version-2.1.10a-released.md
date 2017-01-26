---
layout: post
title: Getbhavcopy version 2.1.10a released
excerpt: Release log for Getbhavcopy version 2.1.10a 
comments: true
tags: 
    - 'Hemen Kapadia'
    - Getbhavcopy
    - 'Version Updates'
    - 'News and Announcements'
---

Getbhavcopy version 2.1.9a, which i released couple of days back, did happen to resolve the issues with NSE data download for most of the users. However some users still using Windows XP were reporting the following error message while trying to download data with version 2.1.9a:

``` text
Message Error checking version support for Getbhavcopy using static file.
Message The underlying connection was closed: An unexpected error occurred on a send.
```

This version addresses the problem faced by Windows XP users and they will be able to use Getbhavcopy.

For those who would like to know the root cause behing the issue, with Microsoft no longer supporting Windows XP, most websites are implementing HTTPs certificates that remove support for the RC4 cipher - the best one in Windows XP. With the Github servers no longer supporting the RC4 cipher, XP was unable to communicate with Github over HTTPs.

Read more - [Github SSL changes](https://github.com/blog/1937-improving-github-s-ssl-setup)

It is a matter of time as other sites will also follow suite and if NSE/BSE do this upgrade, then there is no way Getbhavcopy will work on your machine.

<div class="message">
I request Windows XP users to upgrade their OS. Moreover in future versions of Getbhavcopy I cannot gurantee Windows XP support.
</div>

[Download Getbhavcopy version 2.1.10a](https://github.com/hemenkapadia/getbhavcopy/releases)

Thanks!
