---
sidebar_position: 1
---

# Intro

Linux is an operating system, much like Windows and MacOs. It is fundamental in learning ROS as Linux is typiaclly used to develop ROS projects. 

## Installation

To install Linux, in theory you would want a computer that doesn't already have an operating system. Think of it like installing iOS on an Android phone, while it already has Android! Of course this might not be the easiest case, as you are probably reading this from your own work computer, however there are a few options.

1. Using a virtual machine
2. WSL (Windows Subsystem for Linux)
3. Dual booting Linux
4. Use Linux as the primary OS

### WSL

The simplest route for many people involves the Windows Subsytem for Linux. This allows users to have a Linux environment with their Windows operating system. It is the quickest solution for Windows users, but will limit the options for graphical user interfaces. In other words, you will only be able to interact using the terminal, and there will be no desktop or windows or any graphical representation of the operating system. 

To install Ubuntu, a common variant (distro) of Linux, you can use the wsl command line interface. 

```
wsl --install
```

Then download Ubuntu in the Microsoft Store. There may be multiple options, but you can either choose the latest version or the one with the most downloads. 

Now you can run Ubuntu through the Windows start menu, or by typing `ubuntu` in a Windows terminal. 

Some people believe that there is no use for a graphical user interface, as the terminal is capable of doing everything you need to build ROS projects, but it might be nice to have for new Linux users, which leads into our other options

### Virtual Machines

You can also use Virtual Machines to have a virtual Linux installation. This uses your computer's hardware to run Linux in a seperate window, that you can interact with visually and through Windows. This is the most noob-friendly way of starting off with Linux, as you can use both the graphical user interfaces and the terminal. 

Refer to a seperate tutorial installing your favorite VM. It's a whole other can of worms so use ChatGPT or Google for this!

### Dual Booting

You can also save a poriton of your computers storage to hold an installation of Linux, which you can then boot up. This is known as dual booting, and can be a really nice way to have Linux on your system. You also get access to the graphical interface, assuming your comupter is connected to a monitor and other peripherals. This method is extremely satisfying to use as you are fully immersed in Linux, since it is just Linux! However, this is the slowest, and trickiest method to getting Linux. It can also be slow to switch between your other OS and Linux as you need to shut down your system each time. Not practical if you only need Linux for short bursts of work, or you really love your other OS. 

Refer to other online tutorials for installation. This depends on your system and which distribution you want. 

### Just using Linux

The final method, similar to dual booting, is just straight up using Linux as your operating system. This requires dedicating an entire computer to running Linux, and potentially nothing else (unless you dual boot of course). This means that there will be no other junk on your system; it's just you and Linux. Knowing this, you will have the cleanest experiene possible. No having to jump through the BIOS, or menus or anything else, just start your PC and go. Of course the downsides are quite extreme, but this can be a complex task to complete, as it requires accessing your computer's BIOS. If you can manage the advanced stuff, then this will be an excellent option for running Linux and being fully immersed in this world. 

And again, refer to the internet for this one. I'm just here to relay your options. Now it is up to you to pick whichever method suites your needs. 