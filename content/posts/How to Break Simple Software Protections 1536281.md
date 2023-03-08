---
title: "Unleash Your Inner Hacker: Learn How to Break Through Simple Software Protections in Minutes!"
ShowToc: true 
date: "2023-04-23"
author: "David Butler"
---
*****
# Unleash Your Inner Hacker: Learn How to Break Through Simple Software Protections in Minutes!

Are you fascinated with hacking and wondering how hackers are able to break through software protections in no time? Well, the truth is that even if you are not a computer science expert, you too can turn into a hacker in a matter of minutes!

In this article, we'll explore some easy methods you can use to unleash your inner hacker by breaking through simple software protections. Strap in and let's dive in!

## Method 1: Use Cracking Software

One of the easiest ways to break through software protections is by using cracking software. With this type of application, you don't have to be a coding expert to get started. All you need to do is download and install the software, and you're good to go.

Some popular cracking software applications include Hashcat, John the Ripper, and Aircrack-ng. These tools are designed to identify and crack passwords, Wi-Fi networks, and other forms of software protection. With a bit of practice, you can become efficient in using these cracking tools to break through different types of software protection.

## Method 2: Employ Social Engineering

Social engineering is a technique that involves using psychology to trick people into sharing sensitive information. For instance, a hacker may pose as an IT technician and ask employees to share their login details for a system. Once the hacker has the login details, they can easily breach the system.

To employ social engineering effectively, you need to be well versed in human psychology. You'll need to understand how to persuade, manipulate, and deceive people into sharing critical information. With practice, you can become a skilled social engineer and break through simple software protections with ease.

## Method 3: Use Brute Force Attacks

A brute force attack involves using software to try different combinations of passwords until the correct one is found. For instance, if you want to crack a password that is 8 characters long and made up of upper and lower case letters and numbers, a brute force attack would try all possible combinations until it finds the right one.

To use brute force attacks, you need to use specialized software such as Hydra, Cain and Abel, or Medusa. These applications allow you to automate the process of trying different password combinations across different systems.

Final Thoughts

Becoming a hacker is not as difficult as you might think. By following the simple methods outlined in this article, you too can unleash your inner hacker and break through simple software protections in no time. However, it's important to remember that hacking is illegal and can lead to serious consequences. Therefore, use your newfound skills ethically and responsibly.

{{< youtube AOHI9U8phDw >}} 



In this article I’ll explain to you how easy it is to break these kinds of protections. Generally, when a program starts, it tests if it’s registered (purchased) or not, and depending on the result (0 or 1) it shows you a navigation screen or activates limitations … or not!
What really happens is that our software makes a CALL to the routine which makes this test (TEST, CMP…) then after this CALL it puts a static value in a register that is usually EAX, then the software checks the result of the concerned register (in this case AL).
NOTE 1: 
[plain]EAX (32bits) = AX (16bits) = AL (8bits) + AH (8bits)[/plain]
After putting 1 or 0 in this register, either a JE or a JNE determines if the software is registered or not. These Jumps (like others except JMP) are directly influenced by the Zero Flag which is modified according to the value of EAX.
Well, now we know how this works, so even a newbie cracker will not find difficulties to break this kind of protection, and he even has several ways to do it, the simplest one is to find the CALL, then force the register EAX or AL into getting the right value (0 or 1).
NOTE 2: You have to know that a “Call” is ALWAYS ended by a RET.
[plain]Pattern of a disassembled protection:</pre> <em></em> :00408740 E87B5B0000 Call 0040E2C0 ; calls serial check routine.. :00408748 85C0 test eax, eax ; checks if sn is good :0040874B 7527 Jne 00408774 ; jump if ZF = 1 :0040874C —><span style="color: red;">"Invalid Registration code." </span>*********More Instructions********** :00408774 —> <span style="color: #00b050;">"Thank you for Support!!"[/plain]
 
Assuming that our software asked us for a serial key, if we input an invalid one, the CALL begins the check routine from the address 40E2C0, till a RET then it sends a result to EAX. If EAX contains the correct value, JNE shows us that our software is correctly registered. 
Some may think to change the conditional jump JNE at 40874B to an unconditional one, so this way we can force the software to say that we are registered, except that we have to input a serial number each time we close and start the software. 
But at this stage we know that everything is around EAX’s value, and by forcing its value to have either 1 or 0 in the beginning of the routine started by the CALL (in our case at address 40E2C0), we will force our software to be registered or not. 
In Assembly language, MOV is the instruction that tells an x86/IA-32 processor to move an immediate value into a register. So to force EAX to have 0, we can put mov eax, 0 Or mov al, 0. 
Which means, all that the routine under the CALL must do is to move/put 0 into EAX; in other words, it tells the software that the serial number given is correct without filling it, and then sends the correct value to EAX. 
In our example, the CALL at address 408740 calls this serial check routine: 
[plain]:0040E2C0 81EC340400 sub esp, 434 :0040E2xx 8B0D605F4500 Mov ecx, dword ptr ds:[455F60] …
*** Cutting more instructions
****** … :0040Exxx C3 RET ‘ Note that every routine called by a CALL is ended by a RET (C3 hex)[/plain]
 
By changing sub esp, 434 and mov ecx, dword ptr ds:[455F60] to mov eax, 1 and RET 
[plain]0040E2C0 B801000000 mov, eax,1 :0040E2xx C3 RET :0040E2xx 0D ? :0040E2xx 60 ? :0040E2xx 5F ? :0040E2xx 45 ? :0040E2xx 00 ?[/plain]
 
We get fully registered software without knowing how a correct serial number is calculated and without even having a correct one. 
NOTE 3: We can fill instructions after RET with NOPs (90 hex), but it’s not necessary since they will not be executed. 
More details about Mov picked from Wikipedia: 
The binary code for this instruction is 10110 followed by a 3-bit identifier for which register to use. The identifier for the AL register is 000, so the following machine code loads the AL register with the data 01100001 what gives : 10110000 01100001 
This binary computer code can be made more human-readable by expressing it in hexadecimal as follows: B0 61 
Here, B0 means ‘Move a copy of the following value into AL‘, and 61 is a hexadecimal representation of the value 01100001, which is 97 in decimal. Intel assembly language provides the mnemonic MOV (an abbreviation of move) for instructions such as this, so the machine code above can be written as follows in assembly language, complete with an explanatory comment if required, after the semicolon. This is much easier to read and to remember: 
[plain]MOV AL, 61h ; Load AL with 97 decimal (61 hex)[/plain]
 
References: 

 

http://en.wikipedia.org/wiki/Assembly_language




