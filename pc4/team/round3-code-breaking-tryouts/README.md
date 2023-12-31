# Code Breaking Tryouts

Perform code breaking, recovery, and reconstruction of data messages to uncover vital threat information.

**NICE Work Roles**
- [Cyber Defense Forensics Analyst](https://niccs.cisa.gov/workforce-development/nice-framework)

**NICE Tasks**
- [T0027](https://niccs.cisa.gov/workforce-development/nice-framework) of a network intrusion.
- [T0049](https://niccs.cisa.gov/workforce-development/nice-framework)- Decrypt seized data using technical means.
- [T0167](https://niccs.cisa.gov/workforce-development/nice-framework)- Perform file signature analysis.
- [T0240](https://niccs.cisa.gov/workforce-development/nice-framework)- Capture and analyze network traffic associated with malicious activities using network monitoring tools.

## Background

Intelligence operatives have intercepted and collected competition data sent between space pirate faction members and **Space Pirate Command's Cyber Operations Group** (SP-COG). The contents of the recovered data allude to an upcoming meetup event where the best and brightest pirate code breakers will attend (assuming, of course, that they can break or recover the files to learn the location and time). The data recovered contains this vital information but it has been encoded, scrambled, obfuscated, or corrupted.

If we can learn the location of this event, we can capture members of the SP-COG high command and any up-and-coming space pirate code breakers who could jeopardize our operations.

Our techs have made the recovered files available to you. It is up to you and your team to recover what data you can.

## ⚠️ Large Files ⚠️
This challenge includes large files as a separate download. Please download [here](https://presidentscup.cisa.gov/files/pc4/team-round3-code-breaking-tryouts-largefiles.zip) to get started. The zip file contains a collection of `.pcap` files that the user must analyze to complete the challenge and a text file with a list of probe locations. The zipped file is ~40MBs and the extracted artifact is ~256MBs.

## Getting Started

See the contents of the [challenge directory](./challenge) to retrieve all necessary files. The challenge requires access to standard Linux command line tools, cryptsetup, and the ability to mount images. A standard Kali system is sufficient to solve the challenge fully. 

### Objectives

#### Objective 1: Translate the UNICODE messages

Use the files provided in the [challenge unicode directory](./challenge/unicode). Use the various resource files to recover passcode 1 from the encoded message files.

#### Objective 2: Investigate and Analyze the Mail Log Data

Use the files provided in the [challenge maillogs directory](./challenge/maillogs). Use the various resource files to recover passcode 2 from the encoded and corrupted message files.

#### Objective 3: Investigate and Analyze the Traffic Captures

Use the files provided in the [challenge traffic directory](./challenge/traffic). Use the various resource files to recover passcode 3 from the corrupted `passcode3.pcap` file.

#### Objective 4: Access the virtualized system and its encrypted container (Objectives 1-3 required)

Use the files provided in the [challenge container directory](./challenge/container). Then, use the passcodes to access the encrypted container and retrieve the location of the meetup event.

> **Note:** Be precise when creating a password file for Objective 4. Leverage the hash provided to ensure your password file is accurate. Some text editors may add extraneous characters/whitespace to files. 

## Submission Format

The offline version of this challenge includes the answers listed below with the questions.

## Challenge Questions

1. What is the passcode recovered from the Unicode message problem? (10 alphanumeric characters)
2. What is the passcode recovered from the maillog/mail messages problem? (10 alphanumeric characters)  
3. What is the passcode recovered from the packet capture problem? (12 hexadecimal characters)  
4. What is the location (star, planet, moon, etc.) of the meetup event for the code breaker competitors?
