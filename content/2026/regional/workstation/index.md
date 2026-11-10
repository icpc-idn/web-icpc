+++
title = 'ICPC Jakarta Workstation'
date = '2026-11-07T00:00:00+07:00'
weight = 42

[params]
menuTitle = 'Workstation'
+++


Each team will be provided with one workstation, shared between team members.
All teams will have the same PC specification.


### Hardware

  * **System unit**: Lenovo Desktop TC Neo 50q
    * CPU: 13th Gen Intel(R) Core(TM) i5-13420H
    * GPU: Intel(R) UHD Graphics
    * RAM: 8GB DDR5-5600MHz SODIMM
    * Disk: 1TB SSD M.2 PCIe Gen4
  * **External screen**: Lenovo ThinkVision E22-30 (21.5-inch)
  * **External keyboard**: [Lenovo 300 USB Keyboard](https://support.lenovo.com/id/en/accessories/acc100331-lenovo-300-usb-keyboard-overview-and-service-parts)
  * **Mouse**: [Lenovo Essential USB Mouse](https://support.lenovo.com/id/en/accessories/acc500073-lenovo-essential-usb-mouse-overview-and-service-parts)

{{< technical/hardware
    workstation=""
    monitor=""
    keyboard="assets/keyboard.png"
    mouse="assets/mouse.jpg"
    >}}

{{< text/alert "warning" "text-dark" >}}
  **No hardware substitutions will be allowed** (that is, teams may not bring their own equipment onto the contest floor).
  This includes that teams may not substitute keyboards or other peripherals;
  all teams will use identical equipment, as described above, during the contest.
{{< /text/alert >}}


### Software

  * **OS**: Ubuntu 24.04 (64-bit) with Linux kernel 6.8.0-45-generic
  * **Desktop**: GNOME
  * **Editors**:
    * vi/vim
    * gvim
    * emacs
    * gedit
    * geany
    * kate
  * **IDEs**:
    * Eclipse
    * Visual Studio Code
    * Sublime Text 4

{{< text/alert "warning" "text-dark" >}}
  Note regarding IDEs: all IDEs will have any internal “AI” tools disabled.
{{< /text/alert >}}


### Command-line Usage

To compile and execute your code with following commands:

{{< technical/compiler-cli src="regional-jakarta" finalized=true bodyClass="table-group-divider" >}}
  c
  cpp
  java
  py3
  kotlin
{{< /technical/compiler-cli >}}

Note that for Python3, the compilation process checks the syntax correctness only.

All given scripts will invoke respective compiler with the [same options](../judging#programming-languages) as those used by the judges.
You are free to execute (test) your programs on your machine using any method you choose.


### Printing

There will be runners who will deliver printed output to your team workstation (teams will not
have direct access to the printers).

Print jobs are limited to a few pages long; printing excessively long output will be deemed an
activity detrimental to the contest and subject to disqualification.

Details will be announced during technical meeting.


### Backups

Files under home directory (including subdirectories) are backed-up to an external machines for recovery purposes.
The backup process will be executed **every 5 minutes**.
