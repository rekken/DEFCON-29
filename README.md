
## Talk

**"Caught you - reveal and exploit IPC logic bugs inside Apple"**

Speakers: Zhipeng Huo([@R3dF09](https://twitter.com/R3dF09)), Yuebin Sun([@yuebinsun2020](https://twitter.com/yuebinsun2020)), Chuanda Ding([@FlowerCode_](https://twitter.com/FlowerCode_)) of Tencent Security Xuanwu Lab

Apple's iOS, macOS and other OS have existed for a long time. There are numerous interesting logic bugs hidden for many years. We demonstrated the world's first public 0day exploit running natively on Apple M1 on a MacBook Air (M1, 2020). Without any modification, we exploited an iPhone 12 Pro with the same bug.

In this talk, we will show you the advantage and beauty of the IPC logic bugs, how we rule all Apple platforms, Intel and Apple Silicon alike, even with all the latest hardware mitigations enabled, without changing one line of code. We would talk about the security features introduced by Apple M1, like Pointer Authentication Code (PAC), System Integrity, and Data Protection. How did they make exploiting much harder to provide better security and protect user's privacy. We will talk about different IPC mechanisms like Mach Message, XPC, and NSXPC. They are widely used on Apple platforms which could be abused to break the well designed security boundaries.

We will walk you through some incredibly fun logic bugs we have discovered, share the stories behind them and methods of finding them, and also talk about how to exploit these logic bugs to achieve privilege escalation.


## Slides
<https://media.defcon.org/DEF%20CON%2029/DEF%20CON%2029%20presentations/Zhipeng%20Huo%20Yuebin%20Sun%20Chuanda%20Ding%20-%20Caught%20you%20-%20reveal%20and%20exploit%20IPC%20logic%20bugs%20inside%20Apple.pdf>

## Video

[![Video of YouTube](https://img.youtube.com/vi/oAMZxKsZQp0/maxresdefault.jpg)](https://www.youtube.com/watch?v=oAMZxKsZQp0)


