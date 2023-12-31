# The Droid You're Looking For

Examine a forensic disk image of an Android mobile device.

**NICE Work Roles**

- [Cyber Defense Forensics Analyst](https://niccs.cisa.gov/workforce-development/nice-framework)

**NICE Tasks**

- [T0049](https://niccs.cisa.gov/workforce-development/nice-framework) - Decrypt seized data using technical means.
- [T0103](https://niccs.cisa.gov/workforce-development/nice-framework) - Examine recovered data for information of relevance to the issue at hand.
- [T0216](https://niccs.cisa.gov/workforce-development/nice-framework) - Recognize and accurately report forensic artifacts indicative of a particular operating system.
- [T0396](https://niccs.cisa.gov/workforce-development/nice-framework) - Process image with appropriate tools depending on analyst's goals.

 ## ⚠️ Large Files ⚠️
 
 This challenge includes large files as a separate download. Please download and extract the `andrew.dd` image [here](https://presidentscup.cisa.gov/files/pc4/individuala-round1-the-droid-youre-looking-for-largefiles.zip) before beginning. The zipped file is ~3GBs and the extracted artifact is ~6GBs.

## Getting Started

Someone was caught stealing information off of The Dauntless and transmitting it to another party.  We have seized their mobile device and created an image of the data partition to examine.  The image, `andrew.dd`, is placed on the Security Terminal workstation's desktop.  Examine the partition to try to determine what was compromised and if there is anyone else we should suspect. Examine the disk image to answer the questions.  

The time zone for the device is EDT (UTC -0400).

All password cracking should use the provided wordlist.


## Challenge Questions

There were several variants of this challenge which asked different questions. These are the questions from one variant. 

1. There is a photo taken on 12-19-2021.  What city was this taken in?
2. What is the full name of the person who texted the device asking "do you have lunch plans?"
3. What is the MD5 hash of the browser tab that searched for "antiforensic & phone"?
4. The stolen data is the "Ship ports.xlsx file."  What is the system number 7 on the "Ship ports.xlsx" file? (Use entire cell)
5. The user texted one Dauntless crew mate.  There is one other contact from the same organization. What is the email address of the Dauntless crew mate that was not texted from this device?
6. The user has an interest in Roblox and searches the topic using various apps. What is the topic_id (from a local application database) for Roblox?
7. What is the timestamp from when the stolen information was sent to another person in YYYY-MM-DD HH:MM format? (24-hour format UTC -0400)
