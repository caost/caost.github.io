---
title: "create swap"
date: 2018-09-05 11:23:28 -0800
categories: linux
---

```bash
# fallocate -l 2G swap.img
# chmod 600 swap.img
# swapon swap.img
# swapon
# swapoff swap.img
# swapon
# vi /etc/fstab
```
