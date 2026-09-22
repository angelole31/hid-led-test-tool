**HID LED Test Tool — macOS Keyboard Automation**

A macOS HID project exploring keyboard LED control through Apple’s I/O Kit and IOHID Manager APIs.

**Overview**

This project is based on a legacy Mac OS X command-line HID LED test tool. It demonstrates how connected USB keyboards can be detected and their LED states controlled programmatically.

I explored and adapted the project to address a practical keyboard-lighting issue on macOS, where the keyboard’s LED control conflicted with the system’s handling of the Scroll Lock key.

**What I Worked On**
* Reviewed the existing C source code and project structure
* Examined how macOS communicates with USB HID devices
* Worked with the IOKit and IOHIDManager APIs
* Modified the program logic for the desired keyboard LED behavior
* Compiled the source code into an executable
* Tested the resulting application with a USB keyboard
* Created a simple macOS automation workflow for easier use

**Technologies**
* C
* macOS
* IOKit
* IOHIDManager
* CoreFoundation
* Xcode
* Terminal
* Automator

**Project Structure**

hid-led-test-tool/

├── main.c

├── project.pbxproj

└── README.md

**Purpose**

This project demonstrates practical troubleshooting, technical research, automation, and documentation.

Rather than treating a hardware/software compatibility issue as a dead end, I investigated how the device communicated with macOS, explored the existing implementation, modified the behavior, and created a more convenient workflow for repeated use.

**Note**

This project is based on a legacy Mac OS X HID example and was adapted for personal testing and learning. It is presented as a technical work sample demonstrating problem-solving and automation.
