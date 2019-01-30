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

| Year | Model                   | ID   |
| ---- | ----------------------- | ---- |
| 2014 | Scroll Alpha            | 4011 |


## G.Skill devices

| Year | Model                   | ID   |
| ---- | ----------------------- | ---- |
| 2013 | MX-780                  | 3101 |

## Logitech devices

#### Gaming
These mice are listed as supported by LGS. This suggests onboard profiles and programmable buttons.

| Year | Model                   | Driver | ID   |
| ---- | ----------------------- | ------ | ---- |
| 2005 | G5                      | 1.0    | c041 |
| 2005 | G7                      | 1.0    | c51a |
| 2007 | [G5 2007](G5-2007.html) | 1.0    | c041 |
| 2007 | [G9](G9.html)           | 1.0    | c048 |
| 2008 | G9x                     | 1.0    | c066 |
| 2009 | [G500](G500.html)       | 1.0    | c068 |
| 2010 | [G700](G700.html)       | 1.0    | c06b + c531 |
| 2011 | G300                    | G300   | c246 |
| 2012 | G9X: CoD                | 1.0    | c249 |
| 2012 | [G600](G600.html)       | G600   | c24a |
| 2013 | [G500s](G500s.html)     | 1.0    | c24e |
| 2013 | G602                    | 2.0    | c537 |
| 2013 | [G700s](G700s.html)     | 1.0    | c07c + c531 |
| 2014 | G302                    | 2.0    | c07f |
| 2014 | G402                    | 2.0    | c07e |
| 2014 | G502                    | 2.0    | c07d |
| 2015 | G300s                   | G300   | c246 |
| 2015 | G303                    | 2.0    | c080 |
| 2016 | G502 P. Spectrum        | 2.0    | c332 |
| 2016 | G900                    | 2.0    | c539 + c081 |
| 2016 | G403 Wireless           | 2.0    | c081 |
| 2016 | G403                    | 2.0    | c082 |
| 2016 | G Pro                   | 2.0    | c085 |
| 2017 | G102/G203               | 2.0    | c084 |
| 2017 | G603                    | 2.0    | b01c + c081 |
| 2017 | G903                    | 2.0    | c086 + c081 |
| 2017 | G703                    | 2.0    | c087 |
| 2018 | G Pro Wireles           | 2.0    | c539 + c088 |

#### Other
Other devices that support hid++ protocols. Supported by set point.

| Year | Model               | Driver | ID   |
| ---- | ------------------- | ------ | ---- |
| 2010 | M705                | 1.0    | 101b |
| 2010 | M570                | 1.0    | 1028 |
| 2010 | Wireless Touchpad   | 2.0    | 4011 |
| 2012 | T650                | 2.0    | 4101 |
| 2015 | M325                | 2.0    | 400a |
| 2015 | MX Master           | 2.0    | 4041 + 4060 + b012 |
| 2015 | MX Anywhere 2       | 2.0    | 404a + b013 |
| 2017 | MX Master 2S        | 2.0    | 4069 + b019 |
| 2017 | MX Anywhere 2S      | 2.0    | 406a |

## Razer devices
The EULA of the Razer configuration tool prevents us to reverse engineer their
protocol. Until we have legal access (or maybe a clean room implementation), we
can not support those devices in libratbag.

## Roccat devices

| Year | Model               | ID   |
| ---- | ------------------- | ---- |
| 2014 | Kone XTD            | 2e22 |

## Steelseries devices

| Year | Model               | Protocol Version | ID   |
| ---- | ------------------- | ---------------- | ---- |
| 2012 | Sensei Raw          | 1                | 1369 |
| 2012 | Kinzu V2            | 1                | 1378 |
| 2018 | Rival 310           | 2                | 1720 |
| 2018 | Sensei 310          | 2                | 1722 |
| 2018 | Rival 600           | 3                | 1724 |


## Device owners

| Model                                 | Owner    |
| ------------------------------------- | -------- |
| Etekcity Scroll 6E                    | @bentiss |
| Etekcity Scroll Alpha                 | @dvdhrm  |
| Logitech G9                           | @phomes  |
| Logitech G100s                        | @phomes  |
| Logitech G300                         | @phomes  |
| Logitech G303                         | @whot    |
| Logitech G500s                        | @whot    |
| Logitech G400s                        | @phomes  |
| Logitech G502                         | @bentiss |
| Logitech G600                         | @bentiss |
| Logitech G603                         | @FFY00  |
| Logitech G700                         | @bentiss |
| Logitech G900                         | @bentiss |
| Logitech MX Master                    | @bentiss |
| Logitech T650                         | @whot / @bentiss |
| Logitech T651                         | @bentiss |
| Logitech Wireless Touchpad            | @whot / @bentiss |
| Razer DeathAdder Chroma               | @whot    |
| Razer Imperator 2012                  | @bentiss |
| Roccat Kone XTD                       | @whot    |
| Steelseries Rival 310                 | @FFY00   |
| Steelseries Sensei 310                | @phomes  |
| Steelseries Rival 600                 | @ergor   |
