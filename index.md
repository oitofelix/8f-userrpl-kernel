---
title: oitofelix - 8F UserRPL Kernel
description: >
  HP 50g extension library for UserRPL programming
tags: >
  HP 50g, UserRPL,
license: CC BY-SA 4.0
layout: oitofelix-homepage
#base: http://oitofelix.github.io
#base_local: http://localhost:4001
---
<div id="markdown" markdown="1">
## 8F UserRPL Kernel

![8F UserRPL Kernel logo]({{ page.base_local }}{{ site.baseurl }}/8f-userrpl-kernel.png)

The 8F UserRPL Kernel is an extension library for the HP 50g
calculator.  It's intended to provide a versatile and powerful set of
functions spanning an wide range of general programming domains to
ease and empower UserRPL software development.  The kernel itself is
written in the UserRPL language and built using the `CRLIB` command.

For the list of available functionality and documentation on its usage
see its
[source code](https://github.com/oitofelix/8f-userrpl-kernel/blob/master/kernel.rpl).
To ease development the kernel code is capable of building and
installing itself as a library when sent to and evaluated on the
calculator (or emulator).  However, before it can be rebuilt and
installed again it must be first uninstalled.  The
(uninstal.rpl)[https://github.com/oitofelix/8f-userrpl-kernel/blob/master/uninstall.rpl]
is meant for that.  Keep in mind a couple of things: for technical
reasons the kernel (and any UserRPL library for that matter) must be
built and installed before any other library that may depend on it can
be successfully built, and the first kernel build usually fails with a
harmless error (retrying fixes it).

For now no binaries are provided.  You can build the kernel and other
libraries by using the physical calculator or an emulator.  Just grab
the code below:

- [VCS repository](https://github.com/oitofelix/8f-userrpl-kernel/)


### Buchberger's algorithm library


</div>
