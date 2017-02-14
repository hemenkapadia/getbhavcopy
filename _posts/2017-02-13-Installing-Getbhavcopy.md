---
layout: post
title: Installing Getbhavcopy
excerpt: This blog post explains the steps to install Getbhavcopy.
comments: true
tags: 
    - Documentation
    - 'Install Getbhavcopy'
    - 'Getbhavcopy Options'
---

Getbhavcopy is a FREE NSE and BSE 'End of Day' data downloader. This post explains the steps to [Install and Configure][1] Getbhavcopy.

### Download directories

Throughout the [Documentation][2], I assume that 

* `C:\Getbhavcopy` is your Getbhavcopy installation directory, i.e. the one containing Getbhavcopy.exe
* `C:\Getbhavcopy\data\NSE-EOD` is your NSE Equity and Indices data download directory.
* `C:\Getbhavcopy\data\NSE-Futures` is your NSE Futures data download directory, and
* `C:\Getbhavcopy\data\BSE-EOD` is your BSE Equity and Indices data download directory.

![Getbhavcopy data directories](/assets/images/Install_1.gif)

### .Net Framework dependency

Starting version 2.1.4a, Getbhavcopy requires [.Net Framework 4.0][3] to be installed for it to work. I recommend using the [.Net Framework 4.0 standalone installer][3] for the same.

### Download Getbhavcopy

Next download the latest version of Getbhavcopy from [Getbhavcopy Download page][4]. Getbhavcopy is distributed as a simple portable zip file. Download the zip file and extract it to `C:\Getbhavcopy` directory you created earlier.

![Getbhavcopy extract zip file](/assets/images/Install_2.gif)

### Configuring Getbhavcopy options

When you start Getbhavcopy for the very first time, you will notice that the date selections and the 'Download' button are disabled. This is because [Getbhavcopy Options][5] are not yet configured. Setup [Getbhavcopy Options][5]. Once the options are set, the date range selections and 'Download' buttons will be enabled, and you will be able to download bhavcopy data.

![Getbhavcopy Configuration](/assets/images/Install_3.gif)

Hope this post helps you. Thanks for your continued support to Getbhavcopy.


[1]: http://www.getbhavcopy.com/tags.html#install-getbhavcopy
[2]: http://www.getbhavcopy.com/tags.html#documentation
[3]: https://www.microsoft.com/en-in/download/details.aspx?id=17718
[4]: https://github.com/hemenkapadia/getbhavcopy/releases
[5]: http://www.getbhavcopy.com/tags.html#getbhavcopy-options