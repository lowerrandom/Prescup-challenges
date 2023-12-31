# Can't You Hear Me Knocking

Recover concealed information from a streamed video and exploit the target.

**NICE Work Roles**

- [Cyber Defense Forensics Analyst](https://niccs.cisa.gov/workforce-development/nice-framework)
- [Exploitation Analyst](https://niccs.cisa.gov/workforce-development/nice-framework)

**NICE Tasks**

- [T0103](https://niccs.cisa.gov/workforce-development/nice-framework) - Examine recovered data for information of relevance to the issue at hand.
- [T0240](https://niccs.cisa.gov/workforce-development/nice-framework) - Capture and analyze network traffic associated with malicious activities using network monitoring tools.
- [T0028](https://niccs.cisa.gov/workforce-development/nice-framework) - Conduct and/or support authorized penetration testing on enterprise network assets.

## IMPORTANT

This challenge only partially open sourced. The files in the [challenge directory](./challenge) are provided to give you a starting point if you wish to recreate the challenge on your own. The files provided will allow you to solve Question 1.  Question 2 required a specific virtual machine setup. The full version of the challenge can be played on the hosted site.

Before getting started, extract the pcap from [cant-you-hear-me-knocking.zip](./challenge/cant-you-hear-me-knocking.zip).

## Getting Started

We have recovered a transmission from an alien spy to a user on our systems.  This agent is known to hide messages in the audio track of streamed videos.  Extract the message from the **pcap** file, discover the hidden information, and act on it accordingly.

## Challenge Questions

1. What is the "from IP" given in the hidden message?
2. What is the text value in the token file at `C:\token\token\token1`.
