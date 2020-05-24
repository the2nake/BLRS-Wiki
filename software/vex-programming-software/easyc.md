# EasyC

## EasyC

| Platforms: |
| :--- |
| Windows |
| OSS \(Partial\) |

* [VEX-supported](https://phabricator.purduesigbots.com/w/)
* Native code compilation
* 32- and 64-bit types
* Partial multitasking
* Proprietary libraries
* Works out-of-box, built-in IDE
* **Superseded by** [**Midnight C**](https://phabricator.purduesigbots.com/w/cs/midnight_c/)

**EasyC** is a programming language for the [VEX Cortex](https://phabricator.purduesigbots.com/w/ee/vex_cortex/). It initially appears to sport a drag-and-drop interface designed for beginners, but hides a full C text editor and compiler underneath that can compile to native code for the Cortex.

### Features

* Native code compilation \(thus fast execution\)
* Built-in library is a good compromise between ease of use and granularity
* VEX-supported with strong community following, especially among high school teams
* IDE integrates firmware updates, code authoring, compilation, and flashing into one program
* Extensive documentation and help files

### Shortcomings

* Not all C features are available, including pointers and the standard library. However, the early versions of [Midnight C](https://phabricator.purduesigbots.com/w/midnight_c/) are completely backwards-compatible with EasyC and unlock said functionality
* Not free and works only on Windows
* Advanced C editor has been somewhat neglected and does not feature code completion
* Flash utility does not cooperate with [powered programming adapters](https://phabricator.purduesigbots.com/w/ee/powered_programming_adapters/)
* Low-level code performance poor, with buggy library functions and unpredictable timing [Jitter](https://phabricator.purduesigbots.com/w/ee/jitter/)

## History

EasyC was first used in [VEX Gateway](https://phabricator.purduesigbots.com/w/eng/vex_gateway/) for [Coby's](https://phabricator.purduesigbots.com/w/eng/gateway_coby/) driver control code. Competition code began to require the advanced features of Midnight C and later [PROS](https://phabricator.purduesigbots.com/w/pros/), but some beginning programmers used EasyC for a few months afterwards to ease the transition. As of [VEX Toss Up](https://phabricator.purduesigbots.com/w/eng/vex_toss_up/), all use of EasyC has been completely discontinued.
