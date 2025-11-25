# Worksheet

**Unit 11: Cybersecurity and Incident Management**  
**Topic: Network Transmission - TCP/IP, Data Packets and Network Ports**  
**Duration: 25-30 minutes**

---

## Section 1: Fill in the Blanks (10 minutes)

Complete the following sentences by filling in the blanks using words from the word bank below. Each word should be used only once.

**Word Bank:**
`packets | Transport | 443 | payload | Application | 65535 | reassemble | Internet | checksum | routing`

---

**Question 1:**

The TCP/IP model consists of four layers. The top layer is called the __________ Layer, which interfaces directly with software applications such as web browsers and email clients.

---

**Question 2:**

The __________ Layer is responsible for end-to-end communication between applications and includes protocols such as TCP and UDP. This layer segments data and ensures reliability through error detection mechanisms.

---

**Question 3:**

Network port numbers range from 0 to __________. Port 80 is used for HTTP traffic, whilst port __________ is used for HTTPS traffic with encryption.

---

**Question 4:**

Rather than transmitting data as continuous streams, networks break information into small discrete units called __________. Each of these units consists of a header containing control information and a __________ containing the actual data being transmitted.

---

**Question 5:**

The __________ Layer handles logical addressing and __________ decisions using the IP protocol. When packets arrive at the destination, the receiving system uses sequence numbers to __________ them in the correct order and verifies the __________ to ensure no data corruption occurred.

---

## Section 2: Multiple Choice Questions (10 minutes)

Select the best answer for each question.

---

**Question 1:**

Which two protocols operate at the Transport Layer of the TCP/IP model?

A) HTTP and HTTPS  
B) TCP and UDP  
C) IP and ICMP  
D) Ethernet and Wi-Fi

---

**Question 2:**

What is the primary function of network ports?

A) To physically connect network cables to computers  
B) To provide electrical power to network devices  
C) To enable multiple applications to communicate simultaneously on the same device  
D) To encrypt data before transmission across networks

---

**Question 3:**

Which of the following best describes the structure of a data packet?

```
Option A:
┌────────────────────┐
│   Header Only      │
└────────────────────┘

Option B:
┌────────────────────┐
│   Payload Only     │
└────────────────────┘

Option C:
┌────────────────────┐
│   Header           │
├────────────────────┤
│   Payload          │
└────────────────────┘

Option D:
┌────────────────────┐
│   Payload          │
├────────────────────┤
│   Header           │
└────────────────────┘
```

A) Option A - Packets contain only header information  
B) Option B - Packets contain only payload data  
C) Option C - Packets contain header information followed by payload data  
D) Option D - Packets contain payload data followed by header information

---

**Question 4:**

A security analyst notices unusual traffic on port 3389. Which service is most likely being accessed?

A) Web browsing (HTTP)  
B) Email transfer (SMTP)  
C) Remote Desktop Protocol (RDP)  
D) File Transfer Protocol (FTP)

---

## Section 3: Question and Answer (10 minutes)

Answer the following questions in complete sentences. Provide clear explanations demonstrating your understanding of the concepts.

---

**Question 1:**

Explain the difference between TCP and UDP protocols. In your answer, describe when each protocol would be most appropriate to use.

---

**Question 2:**

Describe three advantages of packet-based transmission compared to sending data as continuous streams. Explain why each advantage is important for network efficiency.

---

**Question 3:**

A web browser needs to communicate with a web server to retrieve a webpage. Describe the journey of data through the four layers of the TCP/IP model, explaining what happens at each layer when sending the HTTP request from the browser.

---

*End of Worksheet*