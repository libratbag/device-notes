---
layout: architect
title: Notes by libratbag
subtitle: foo bar
---

# Devices notes gathered from the libratbag project

This site keeps tracks of the various features of the devices we are supporting
in [libratbag](https://github.com/libratbag/libratbag).

It does not contain protocol information for legal reasons.
Please keep it to only general observations and public data (like the number of
supported profiles, the DPI capabilities, the number of buttons, etc...).

## Etekcity devices
- Scroll 6E
- Scroll Alpha

## Logitech devices

#### Gaming
These mice are listed as supported by LGS. This suggests onboard profiles and programmable buttons.

| Year | Model               | Driver | ID   |
| ---- | ------------------- | ------ | ---- |
| 2007 | [G9](G9.html)       | 1.0    | c048 |
| 2008 | G9x                 | 1.0    | c066 |
| 2009 | [G500](G500.html)   | 1.0    | c068 |
| 2010 | G700                |        |      |
| 2011 | G300                | ?      | c246 |
| 2011 | G400                |        |      |
| 2012 | G9X: CoD            | 1.0    | c249 |
| 2012 | [G600](G600.html)   | ?      |      |
| 2013 | [G100s](G100s.html) |        |      |
| 2013 | G400s               |        |      |
| 2013 | [G500s](G500s.html) | 1.0    | c24e |
| 2013 | G602                |        |      |
| 2013 | [G700s](G700s.html) |        |      |
| 2014 | G302                |        |      |
| 2014 | G402                |        |      |
| 2014 | G502                | 2.0    | c07d |
| 2015 | G300s               |        |      |
| 2015 | G303                | 2.0    | c080 |

#### Other
Other devices that support hid++ protocols. Supported by set point.

- G5
- [G5 2007](G5-2007.html)
- M325
- M570
- M705
- MX Master
- T650

## Razer devices
The EULA of the Razer configuration tool prevents us to reverse engineer their
protocol. Until we have legal access (or maybe a clean room implementation), we
can not support those devices in libratbag.

## Roccat devices
- Kone XTD
