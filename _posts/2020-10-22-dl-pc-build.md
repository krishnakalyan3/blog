---
toc: true
layout: post
comments: true
description: My hardware setup with all the Juicy details
categories: [markdown]
title: Building a PC for Deep Learning in 2020
---

## Hardware
Since I live in Germany, I bought all my parts from Mindfactory. I sold my [Macbook Air](mresell.de) for 262€. Building a PC for the first time can be overwhelming and a dauting task. (Spoiler: Its easier that you think) My PC parts below.

| Parts | Company | Price (Euros)
--- | --- | ---:
Mother Board | Gigabyte Z390 AORUS PRO | 170.81
Processor | Intel Core i9-9900 3.1 GHz 8-Core Processor | 346.89
Cooler | be quiet! Dark Rock Pro 4 50.5 CFM CPU Cooler | 67.22
PSU | be quiet! Straight Power 11 750 W 80+ Gold | 115.85
RAM | G.Skill Aegis 16 GB (2 x 8 GB) DDR4-3000 CL16 Memory | 45.80
Storage | 	Crucial P1 1 TB M.2-2280 NVME Solid State Drive | 94.00
Case | 	be quiet! Silent Base 601 ATX Mid Tower Case | 106.68
Gold Service | Mindfactory | 4.90
GPU | RTX 30xx | NA
Grand Total| | 952.15

## Motivation
Q: Why would you build a PC when you can do everything on the Cloud?.
A: I wanted to build a PC that could be used for `Deep Learning` and for playing strategy games on `steam`. I also wanted to have complete control over all the part so that I can upgrade later easily.

- Wanted to play Computer Games on Windows.
- Did I forget to `stop` the EC2 instance I was working on?.
- Wanted to do something creative at Home. (Thanks to a Pandemic)
- Complete control over my PC and configuration.

## Basic setup
Use PC PartPicker. Choose your parts wisely, if not you will be will warned that you are building a PC with `incompatible` parts.

### Motherboard
Choose your motherboard first. Make sure that it fits your requirements. I needed a motherboard with atleast `4` RAM slots and atleast `2` PCIe lanes for GPUs. The type of motherboard changes based on the processor you choose `AMD / Intel`. I got a great deal on Intel CPU and hence my current configuration.

### CPU
Intel CPU i9 comes with hyperthreading. (Basically two threads per CPU [core](https://www.intel.com/content/www/us/en/products/processors/core/i9-processors/i9-9900.html) instead of one per core). This is useful if you want to process data in parallel. Hence, based on my budget I choose `Intel Core i9-9900`.

### Power Supply

### RAM

### CPU Cooling

### NVMe

### GPU
Right now there is a [shortage of GPUs](https://hothardware.com/news/nvidia-posts-expanded-qa-following-geforce-rtx-3080-launch-fiasco) in the Market. I decided to wait it out. The new `RTX 30xx` series is cheaper and faster than the `RTX 20xx` series. The downsides being that there might be issues / bugs in hardware as it not been tried and tested by users in the market.

### Storage / Cabinet and Other Parts
Make sure you already have an `External Monitor`, `Mouse`, `Keyboard`. You might also need to buy a good `power strip` for powering up your monitors and PSU. Keep screwdrivers handy.

### Assembling
I would first check if all parts are working before installing the part to the Cabinet. This way you can check for defects and order replacements quickly if required.

- Motherboard lies on its box
- Install RAM
- Install NVMe
- Install CPU
- Install Cooler
- Connect PSU to the Motherboard
- Connect Cabinet Power to the Motherboard
- Connect Keyboard, Monitor to the Motherboard

Once you have connect everything so far, switch on the PSU and press the power button. If everything is setup correctly, you will see a BIOS screen and Congratulations!. Now all you need to do is to move everything into the cabinet. Be gentle / accurate while plugging in different components, Do not bend the `pin(s)` like I did.

## Mindfactory
I found Mindfactory to be the best in terms of the prices offered / customer service. I had an issue with my Motherboard (Completely my fault). They found out the root cause (Bent Pin) and replace it with a new one. Make sure that you also buy gold service level so that they can prioritise your order requests.

Hacks:
- Order after 00:00 hrs (Free shipping)
- Order All parts together (Gold service - valid per invoice)
- Check out their deals (Deals on a part that you are interested in?)

## Final Thoughts
If you are doing this for the first time make sure you have a friend who has already done this. Incase you are doing this alone make sure that you prepared to invest the time and the patience to figure out why things are not working. Be prepared to spend at least half a day if you have everything right. You can save yourself the pain of assembling it by asking Mindfactory to do it for you / your local PC store will do it for you too (Approx 100 to 200 €).

## Links
- [https://pcpartpicker.com/list/3WFqsX](My Build on PC Part Picker)
- [https://timdettmers.com/2020/09/07/which-gpu-for-deep-learning/](Tim Dettmers Blog)
- [https://forums.fast.ai/t/build-your-deep-learning-box-wiki-thread/13536/155](Build your deep learning box Fast AI thread)
- [https://www.mindfactory.de/](Mindfactory)
