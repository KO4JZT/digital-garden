---
title: US General Class License 
tags: radio-licenses, radio
type: seed
---

# US General Class License

Notes based on The ARRL General Class License Manual For Ham Radio (9th Edition).
- [US General Class License](#us-general-class-license)
  - [Chapter 1: Introduction](#chapter-1-introduction)
    - [Quick Privileges Table](#quick-privileges-table)
  - [Chapter 2: Procedures and Practices](#chapter-2-procedures-and-practices)
    - [HF Operating Techniques](#hf-operating-techniques)
    - [Modes of Operation](#modes-of-operation)
    - [Signal Separation Table](#signal-separation-table)
    - [HF Receiving](#hf-receiving)
    - [HF transmitting](#hf-transmitting)
  - [Chapter 2.2: Emergency Operation](#chapter-22-emergency-operation)
    - [ARES and Races](#ares-and-races)
    - [Distress Calls](#distress-calls)
  - [Q-Code and Prosign Glossary](#q-code-and-prosign-glossary)
  - [References](#references)


## Chapter 1: Introduction

* Once you have a CSCE you can transmit in general bands with /AG until FCC ULS updates.
* The CSCE is good/valid for 365 days (ex. in case of delays).

### Quick Privileges Table

* [ ] IDEA: Build a quick and easy way to input a frequency and see if you can legally transmit, and what modes you can use (phone, CW, data).

| Band   | Frequencies                                      |
| ------ | ------------------------------------------------ |
| 2,200m | 135.7 kHz - 137.8 kHz                            |
| 630m   | 472 kHz - 479 kHz                                |
| 160m   | 1.900 MHz - 2.000 MHz                            |
| 80m    | 3.525 MHz - 3.600 MHz, 3.800 MHz - 4.000 MHz     |
| 60m    | See [[Band Plan]]                                |
| 40m    | 7.025 MHz - 7.125 MHz, 7.175 MHz - 7.300 MHz     |
| 30m    | 10.100 MHz - 10.150 MHz                          |
| 20m    | 14.025 MHz - 14.150 MHz, 14.225 MHz - 14.350 MHz |
| 17m    | 18.068 MHz - 18.168 MHz                          |
| 15m    | 21.025 MHz - 21.200 MHz, 21.275 MHz - 21.450 MHz |
| 12m    | 24.890 MHz - 24.990 MHz                          |
| 10m    | 28.000 MHz - 29.700 MHz                          |

## Chapter 2: Procedures and Practices

* [ ] Copy HF Band Plan from Page 2-3 

### HF Operating Techniques
  * Differences From VHF/UHF
    * Not channelized at all (exclude 60m band)
    * Equipment for continuous tuning (changes by step size)
  * Most Common Modes - Simplex SSB, CW, Digital
  * Use NATO Phonetics
  * Choosing a Frequency
    * Be sure the frequency is under your privileges
    * Follow the band plan under normal circumstances
    * Listen to avoid interfering
  * Agree on how to solve interference or propagation changes together
  * Split Operation - listen on one frequency and transmit on another
    * Think of VHF/UHF repeaters 
    * allows callers to hear the station and keep "in sync"
    * ex. good for DX pileups
* What band should I use?
  * short-range regional contacts: 80m or 40m
  * long range / DX: 30m - 10m
* Calling CQ
  * Phone: "CQ CQ CQ, this is `CHARLIE ALPHA LIMA LIMA`."
  * CW: "CQ CQ CQ, DE `CALL`."
  * CQ Variations
    > Note: I don't love the way the book describes this section, it feels very restrictive on how you can call CQ. I really like [this](https://www.youtube.com/watch?v=_mXNpCnjUwA) video from KJ4YZI on how he calls CQ - it shows how flexible it is. Just get the point across: I'm calling CQ, here's my call, I'm SOTA/POTA/looking for DX/Contesting/whatever.
    * CQ DX - looking for stations outside the caller's country.
    * CQ Contest / CQ test / CQ from special event station
    * CQ "area" - ex. CQ North America
* Break In - say your callsign during a pause in conversation
  * CW - send "BK `CALL`"
* DX Windows - few kHz wide space for making DX contacts
  * In the US, DX Window for outside 48 contiguous states is 50.1 - 50.125 MHz
* Logging: time, date, freq./band, mode, callsign, signal report
  * If operating 60m, you are required to keep note of all antenna gain calculations.

### Modes of Operation

* CW 
  * Usually found in the lower portions of the bands, but can be transmitted everywhere
* SSB Phone
  * most common voice mode on the HF bands
  * less spectrum space than AM, increasing efficiency and range
  * **Upper Sideband >9 MHz, Lower Sideband <9MHz** (excluding 60m)
* Digital Voice
  * becoming more common due to being less affected by fading + less noise
  * FreeDV + G4GUO's protocol
* Digital Modes
  * FT8, PSK31, PSK36 - effective at low power levels
  * RTTY - oldest
  * PACTOR, WINMOR - semi-automatic/automatic message, transfer of small files
* Image Modes
  * permitted wherever voice is allowed except 60m
  * SSTV
  * ATV (fast-scan amateur television) - restricted to >=432 MHz
### Signal Separation Table

| Mode  | Separation   |
| ----- | ------------ |
| CW    | 150 - 500 Hz |
| PSK31 | 150 - 500 Hz |
| RTTY  | 250 - 500 Hz |
| SSB   | 2.5 - 3 kHz  |

### HF Receiving

* *Selectivity* is more important than *sensitivity* on HF
* Preamplifiers are rarely required except on 15m - 10m
* Signal Reports
  * RST - Readability (1-5), Strength (1-9), Tone (1-9, CW/Digital ONLY)
  * C = unstable signal or change in frequency at beginning of each dot or dash
* HF receivers use sharp filters based on quartz crystals, mechanical assemblies, or digital processing software to reject unwanted signals
* shifting frequencies without changing the other
  * receiver incremental tuning (RIT)
  * transmitter incremental tuning (XIT)
* To avoid overload or intermodulation, set gain to be just sensitive enough

### HF transmitting

* PTT vs. VOX
  * PTT - best when operating in noisy environments, can also use foot-switch during busy periods
  * VOX - voice-operated transmit, hands-free operation, better during long periods of operation
* CW
  * Most operators begin using a straight key, but eventually use electronic keyer
  * **CWops + Fists (see references) have programs for beginning CW operators**
  * electronic keyer - paddle used to automatically generate strings of Morse elements
  * semi break-in operation = VOX
  * full break-in operation = radio switches in a few milliseconds 

## Chapter 2.2: Emergency Operation

REGARDLESS of what is happening, all operators not in the situation should stand by and wait for emergency comms to occur/end. Be ready to help out in possible scenarios - you never know what could happen on the air.

### ARES and Races

* ARES
  * Organized and managed by ARRL [Field Organization](https://arrl.org/field-organization) Members
  * Provide communications assistance to local and regional government and relief agencies
  * Open to any licensed amateur
* RACES
  * Governed by FCC §97.407
  * provide communications for civil defense purposes during local, regional, or national civil emergencies
  * sponsored by FEMA, administered by local, county, state emergency management agencies
  * MUST register with local civil defense organization to participate

### Distress Calls

1. Immediately acknowledge the station.
2. Stand by to receive location and nature of assistance needed.
3. Relay to authorities + stay on frequency.

**IF you are making the distress call:**
1. On a voice mode, say "Mayday Mayday Mayday" (digital/CW "SOS SOS SOS") and "any station come in please."
2. Identify with callsign.
3. State location and nature of situation.
4. Describe assistance required and any other details.

**Any frequency may be used as long as the emergency exists.**

## Q-Code and Prosign Glossary

* [ ] Does this deserve its own note?

* AR = End of Message
* DE = from
* K = over
* QRQ = send faster
* QRS = send slower
* QRV = I am ready to receive messages
* QSK = full break-in CW operation
* QSL = I acknowledge receipt
* SK = contact is complete
## References

You can email questions not found in book or website to `newham (at) arrl (dot) org`!

* [ARRL's Book Companion Site](https://arr.org/general-class-license-manual)
* [Graphical Frequency Allocations](https://arrl.org/graphical-frequency-allocations)
* [ARRL Band Plan](https://arrl.org/band-plan)
* [HamStudy](https://hamstudy.org) - PRACTICE TESTS + EXAMS
* [ARRL Practice Tests](https://arrl.org/examreview)
* [Technical Information Service](https://arrl.org/technical-information-service)
* [ARRL: Learning Morse Code](https://arrl.org/learning-morse-code)
  * [CWops](https://cwops.org)
  * [FISTS](https://fists.org)
* [ARES/RACES FAQ](https://arrl.org/ares-races-faw)
* [Instructions for FCC ULS](https://arrl.org/universal-licensing-system)
* Radio/Contest Calendars
  * [ARRL Net Search](https://arrl.org/arrl-net-directory-search)
  * [ARRL Contest Corral](https://arrl.org/contest-calendar)
  * [Special Events List](https://arrl.org/special-event-stations)
  * [WA7BNM Contest Calendar](https://contestcalendar.com) 