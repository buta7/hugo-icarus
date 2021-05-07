+++
categories = []
date = "2017-05-20T12:00:23+02:00"
description = ""
images = []
menu = ""
tags = []
title = "Using the gallery shortcode"
banner = "https://picsum.photos/id/1016/800/400"
+++

This way you can easily include a gallery into your page. Copy the code below into your content file and enter the relative paths to your images.

<!--more-->


    {{< gallery
        "https://picsum.photos/id/1016/800/400"
        "https://picsum.photos/id/1028/800/400"
        "https://picsum.photos/id/1041/800/400"
    >}}

