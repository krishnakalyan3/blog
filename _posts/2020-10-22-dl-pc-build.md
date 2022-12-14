---
toc: true
layout: post
comments: true
description: My hardware setup with all the juicy details
categories: [markdown]
title: Building a PC for Deep Learning
---

## Hardware
Since I live in Germany, I bought all my parts from Mindfactory. Building a PC for the first time can be overwhelming and a dauting task. (Spoiler: It might be easier that you think)

| Parts | Company | Price (Euros)
--- | --- | ---:
Mother Board | Gigabyte Z390 AORUS PRO | 170.81
Processor | Intel Core i9-9900 3.1 GHz 8-Core Processor | 346.89
Cooler | be quiet! Dark Rock Pro 4 50.5 CFM CPU Cooler | 67.22
PSU | be quiet! Straight Power 11 750 W 80+ Gold | 115.85
RAM | G.Skill Aegis 16 GB (4 x 8 GB) DDR4-3000 CL16 Memory | 97.5
Storage | 	Crucial P1 1 TB M.2-2280 NVME Solid State Drive | 94.00
Case | 	be quiet! Silent Base 601 ATX Mid Tower Case | 106.68
Gold Service | Mindfactory | 10
GPU | 8GB Gigabyte GeForce RTX 3070  | 649
Grand Total| | 1647.95

## Motivation
Q: Why would you build a PC when you can do everything on the Cloud?.

A: I wanted to build a PC that could be used for `Machine Learning`. I also wanted to have complete control over hardware for upgradability and predicatble hardware performance. That's what I want you to believe, the truth is that I want to play computer games ;).

## Basic setup
Use PC PartPicker. This helps you to choose your parts wisely, you will be will warned that you are building a PC with `incompatible` parts.

### Motherboard
Choose your motherboard first. Make sure that it fits your requirements (You will need to decide if you want to go for an AMD or an Intel Motherboard). I needed a motherboard with atleast `4` RAM slots and atleast `2` PCIe lanes for GPUs. 

Just buy any decent motherboard in the market. There are lot of companies that sell motherboards that can be overclocked. You might not need it for deep learning.

> Deep Learning on an overclocked machine does not lead to performance improvements.

### CPU
Intel CPU i9 comes with hyperthreading. (Basically two threads per CPU [core](https://www.intel.com/content/www/us/en/products/processors/core/i9-processors/i9-9900.html) instead of one per core). This is useful if you want to process data in parallel. I also got a great deal on Intel CPU because I know someone working there.

### RAM
I choose 16 GB RAM begin with. I intend to expand to 32GB later. That's the reason why I needed a Motherboard with `4` RAM slots. Incase you intend to get 24GB GPU (RTX 3090) make sure you have at least 32GB RAM.

> Just buy the cheapest DDR4 RAM available out there with a clock frequency greater than 2400.

### Cooling
You need to choose if you need to Liquid Cool or Air Cool. In would recommend that you Air cool your PC. Some Advantages

- They do not leak
- Easier to upgrade
- Much Cheaper

I needed a single GPU for my needs (games / deep learning experiments). At worst, I would use `2` GPUs.

### NVMe
I needed hot storage for reading data quickly. NVMe SSDs are perfect for this. Some motherboards do not have this option. I went for the cheaper NVMe from `Crucial` instead of `Samsung`. There is minor difference in performance according to the benchmark tests.

### GPU
Right now there is a [shortage of GPUs](https://hothardware.com/news/nvidia-posts-expanded-qa-following-geforce-rtx-3080-launch-fiasco) in the Market. The new `RTX 30xx` series is cheaper and faster than the `RTX 20xx` series. 

I am currently testing `8GB Gigabyte GeForce RTX 3070`. I has `3` fans which keeps the GPU temprature manageable. Games run flawlesly. I have no complaints related to performance of my ML experiments. 

> Make sure you install your GPU in the first PCIe slot to get the best perfomance.

### Power Supply
PC PartPicker will help you with that based on the configuration you have chosen. Suppose my configuration required 600W. I would keep an extra headroom for another 100-150W (Making it a total of 750W).

### Storage / Cabinet and Other Parts
Make sure you already have an `External Monitor`, `Mouse`, `Keyboard`. You might also need to buy a good `power strip` for powering up your monitors and PSU. Keep screwdrivers handy.

### Assembling
I would first check if all parts are working before installing the part to the Cabinet. This way you can check for defects and order replacements quickly if required.

- Motherboard lies on its box
- Install RAM
- Install NVMe
- Install CPU
- Install Cooler
- Install GPU
- Connect PSU to the Motherboard
- Connect Cabinet Power to the Motherboard
- Connect Keyboard, Monitor to the Motherboard

Once you have connected everything so far, switch on the PSU and press the power button. If things are setup correctly, you will see a BIOS screen and Congratulations!. Now all you need to do is to move everything into the cabinet. Be gentle / accurate while plugging in different components, Try not bending the `pin(s)` like I did.

## Final Thoughts
If you are doing this for the first time make sure you have a friend who has already done this. Be prepared to spend at least half a day if you have everything right. You can save yourself the pain of assembling by requesting Mindfactory or your local PC store will do it for you (Approx `100-200???`). I sold my [Macbook Air](mresell.de) for `262???`.

![]({{site.baseurl}}/_posts_/images/pc_final.jpg)

## Links
- [My Build on PC Part Picker](https://pcpartpicker.com/list/3WFqsX)
- [Tim Dettmers Blog](https://timdettmers.com/2020/09/07/which-gpu-for-deep-learning/)
- [Build your deep learning box Fast AI thread](https://forums.fast.ai/t/build-your-deep-learning-box-wiki-thread/13536/155)
- [Mindfactory](https://www.mindfactory.de/)