# 🖥️ Computer Fundamentals

![Platform](https://img.shields.io/badge/Platform-TryHackMe-c11111?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> My first module. The goal: understand what a computer is made of
> and how the systems I will be defending actually work.

---

## 📚 Rooms


| #   | Room                                                                                  | Status |
| --- | ------------------------------------------------------------------------------------- | ------ |
| 1   | [Inside a Computer System](https://tryhackme.com/room/insideacomputer)                | ✅      |
| 2   | [Computer Types](https://tryhackme.com/room/computertypes)                            | ✅      |
| 3   | [Client-Server Basics](https://tryhackme.com/room/clientserverbasics)                 | ✅      |
| 4   | [Virtualisation Basics](https://tryhackme.com/room/virtualisationbasics)              | ✅      |
| 5   | [Cloud Computing Fundamentals](https://tryhackme.com/room/cloudcomputingfundamentals) | ✅      |


---



## 💡 Key Takeaways

**1. Inside a Computer System**  


- The CPU executes instructions, RAM holds what is being used right now,
and storage (HDD/SSD) keeps data long-term.
- When a program starts, it is loaded from disk into RAM and the CPU runs it.
- 🛡️ **Security angle:** RAM can contain evidence that never touches the disk,
which is why memory analysis matters in investigations.



**2. Computer Types**  


- A computer is not just a PC: servers, smartphones, IoT and embedded
devices are computers too.
- Each type is built for a different job and works differently.
- 🛡️ **Security angle:** every device on a network is a potential entry point
for an attacker, even a smart light bulb.



**3. Client-Server Basics**  


- A client sends a request, the server processes it and sends back a response.
- Websites, email, games and most online services work this way.
- 🛡️ **Security angle:** every request leaves a trace in logs. Who, when and
what was requested is the foundation of any investigation.



**4. Virtualisation Basics**  


- A hypervisor lets several isolated operating systems run on one machine.
- Virtual machines can be saved as snapshots and rolled back at any time.
- 🛡️ **Security angle:** suspicious files can be safely analysed inside an
isolated VM. My home lab will be built the same way.



**5. Cloud Computing Fundamentals**  


- The cloud means renting resources from a provider instead of owning hardware.
- Service models: IaaS (infrastructure), PaaS (platform), SaaS (ready-made software).
- 🛡️ **Security angle:** cloud misconfigurations are one of the common causes
of data leaks.



---



## 🎯 Main Takeaway

To defend a system, you first need to understand how it works.
This module gave me the map: what a computer is made of, how devices
talk to each other, and where data lives today.

---

⬅️ [Back to progress](../README.md)