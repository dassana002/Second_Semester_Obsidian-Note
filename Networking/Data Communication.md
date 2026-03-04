![[DataCommunication_image.png]]

==Devices දෙකක් (sender & receiver) අතර Data exchange වෙන process එක.==
The exchange of data between two or more devices via a transmission medium using protocols.

==**Direction** කියන්නේ data flow වෙන way එක.==
#### Main purposes:
1. Information sharing (e.g., email, WhatsApp)
2. Resource sharing (printer, database)
3. Remote access (server, cloud)
4. Real-time communication (video call)
5. Distributed systems (client-server architecture)

#### Main Components
1. ==Source==
2. ==Receiver==
3. ==Medium==
4. ==Message== 
5. ==Protocol (Rules)==

| Real World     | Data Communication  |
| -------------- | ------------------- |
| Sender         | Sender Device       |
| Receiver       | Receiver Device     |
| Letter         | Data                |
| Postal Service | Transmission Medium |
| Address Rules  | Protocol            |
##### Source (Sender)
==Data යවන device එක.==
- Laptop
- Mobile phone
- Server
##### Receiver (Destination)
==Data ලබාගන්න device එක.==
##### Message
==Actual data (text, file, video, etc.)==
##### Transmission Medium
==Data travel කරන path එක.==
- Twisted pair cable
- Coaxial cable
- Fiber optic
- Wireless (WiFi, Radio waves)
##### Protocol
==Communication rules.==
- HTTP
- TCP/IP
- FTP
- SMTP
Without protocol → communication fails.

# Data communication types
- Simplex
- Half Duplex
- Full Duplex
### Simplex Communication
==Data එක එක දිශාවට විතරක් (one-way) flow වෙන communication type එක.==
	
	Sender → Receiver  
	Receiver → ❌ (data යවන්න බෑ)
	
Simplex භාවිතා කරන්නේ **feedback අවශ්‍ය නැති situations** වල.  
Receiver side එකෙන් response එකක් එවන්න ඕන නැති විට.

### Half Duplex Communication
==Half Duplex කියන්නේ දෙපැත්තටම communication පුළුවන්.  
හැබැයි එකම වෙලාවේ දෙපැත්තෙන් data යවන්න බෑ.==

	Bandwidth save කරගන්න.  
	Low-cost systems වල භාවිතා වෙනවා.

### Full Duplex Communication
==Full Duplex communication කියන්නේ දෙපැත්තටම data එකම වෙලාවේ transmit & receive කරන්න පුළුවන් communication type එක.==

	- Real-time communication
	- High efficiency
	- Modern networking systems

| Feature      | Simplex | Half Duplex   | Full Duplex |
| ------------ | ------- | ------------- | ----------- |
| Direction    | One-way | Two-way       | Two-way     |
| Simultaneous | ❌       | ❌             | ✅           |
| Feedback     | ❌       | ✅             | ✅           |
| Example      | TV      | Walkie Talkie | Phone Call  |

# Based on Connection Type
1. Wired communication
2. Wireless communication

# Real-World Technology
	