# OpenWrt-OS-Patch
---
1. Modify batman-adv timeout interval:

    in batman-adv main.h 

    `#define BATADV_PURGE_IMEOUT 5000 /* 5 seconds */`

2. Patch for OpenWrt Chaos Calmer:

    nexfi.patch 
