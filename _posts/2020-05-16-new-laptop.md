---
title: "I can't win with a new laptop!!!"
date: 2020-05-16
permalink: /posts/2020/05/blog-post-2/
tags:
  - Windows
  - macOS
  - Linux
  - AKSHUALLY ITS GNU/LINUX
  - laptop
---

So I'm probably going to get a new laptop for grad school, but I've been having a pretty tough time deciding which one based on my requirements because you can't have everything.

This is like that cringey but mostly true venn diagram that every engineering meme page likes to recycle:

![Venn Diagram](/images/cheap_fast_good.png)

**On the software side of things:**

1. Native unix-like shell (Linux, macOS)
1. Definite support for industry standard electrical engineering tools (Windows mostly...but it seems like both Linux and mac are growing?)
1. Extensively customizable user experience and interface (Linux)
1. Ability to play most modern games, and do some hobbyist game dev (Windows)
1. Texting people without my phone (macOS, I love iMessage)


**And for hardware:**

1. Relatively small form factor (mid-2015 Macbook Pro is SO heavy)
1. Good battery life (Windows still has catching up to do for systems with displays > FHD)
1. 1080p unless it's a mac
1. Decent selection of ports, almost everyone is an offender of this

And I want all of this without having to dual-boot a system or use any virtual machines, which is impossible!

As much as I love my mac, I think the best compromise at the moment that hits the important requirements seems to be running WSL2 on a nice powerful Windows machine. Although it is highly annoying since the filesystem is separate from Windows, and I'd like to use the shell to manage my entire system. I realize Cygwin and PowerShell exist, but I just want everything to be unified instead of having several systems cobbled together.

The top candidate at the moment is the [ASUS ROG Zephyrus G14](https://www.asus.com/Laptops/ROG-Zephyrus-G14/), and there doesn't really seem to be any competitors in its form factor/power/value ratio (unfortunately). Even more unfortunately: dual-booting Linux (specifically Ubuntu) support seems really poor, meaning I would have to run WSL.

You can never win, oh well.