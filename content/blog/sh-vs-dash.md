---
external: false
title: The Difference Between sh and dash
description: A quick comparison of sh and dash shells.
date: 2023-02-14
---

If you've spent any time in a Unix or Unix-like environment, you've probably encountered the sh and dash shells. While these two shells may seem similar at first glance, there are actually some key differences between them that are important to understand.

## sh

sh, which stands for "Bourne shell," is one of the oldest Unix shells still in use today. It was originally developed by Stephen Bourne in the 1970s and has since become a standard on most Unix and Unix-like systems. In fact, many scripts that are written for sh will run on just about any Unix-like system, making it a popular choice for scripting.

## dash

dash, on the other hand, is a newer shell that was developed specifically for Debian-based systems in order to provide a faster, more efficient alternative to sh. It is designed to be a POSIX-compliant replacement for sh, and it is used by default as the /bin/sh on Debian-based systems.

## Key Differences

So what are the key differences between these two shells?

Speed: dash is generally considered to be faster than sh, making it a good choice for systems with limited resources or for scripts that need to be run frequently.

Size: dash is also much smaller than sh, which can be an advantage on systems with limited storage space.

Compatibility: While sh is more widely used and scripts written for sh will generally work on any Unix-like system, dash is designed to be a POSIX-compliant replacement for sh, which means that scripts written specifically for dash may not work as expected on other systems.

Features: dash is a stripped-down shell that does not include many of the advanced features found in more modern shells like bash or zsh. While this can be an advantage in terms of speed and simplicity, it also means that scripts that rely on advanced features may not work with dash.

## Conclusion

In summary, while sh and dash may seem similar, there are some key differences between them that can have an impact on the performance and compatibility of scripts. If you're working on a system with limited resources or need to run scripts frequently, dash may be a better choice due to its speed and small size. However, if you need to ensure maximum compatibility with other Unix-like systems, sh may be the better option.
