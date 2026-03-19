This lab functioned as a short introductory course on network traffic analysis. The objective was to learn fundamental concepts and apply them by answering questions and finding flags throughout the theoretical and practical sections.
![[Pasted image 20260318193605.png]]
The first question was straightforward and could be answered by carefully reading the theoretical content provided at the beginning of the lab.
![[Pasted image 20260318193633.png]]
![[Pasted image 20260318193645.png]]
The first question in this section was answered by examining the server's response to the client's GET request. The key piece of information was the `Content-Length: 10485760` field in the HTTP response. The next two questions were also directly answerable from the theory. The relevant fragments were clearly highlighted in the reading material.
![[Pasted image 20260318193823.png]]
![[Pasted image 20260318193845.png]]![[Pasted image 20260318193918.png]]
![[Pasted image 20260318193934.png]]
The first two questions in this section were answered using the theory. The third question, however, was not explicitly covered in the lab text. It required prior knowledge or a quick web search to find the correct answer (TLS: Transport Layer Security).
![[Pasted image 20260318194233.png]]
![[Pasted image 20260318194428.png]]
![[Pasted image 20260318200644.png]]
In this scenario, we were redirected to an external site for a hands-on exercise. The task was to place a network interception device (TAP) in the most efficient location to capture relevant traffic.
![[Pasted image 20260318194910.png]]
![[Pasted image 20260318194935.png]]
I selected the web proxy as the interception point. This placement allowed me to capture all web traffic entering and leaving the local network.
![[Pasted image 20260318195007.png]]
After placing the TAP, I inspected the packet table and browsed through the captured traffic until I found the flag. The flag was hidden within the HTTP packets.
![[Pasted image 20260318195025.png]]![[Pasted image 20260318195032.png]]
For the second scenario, I repeated the process but focused on DNS traffic. For the second scenario, I repeated the process but focused on DNS traffic. I analyzed the DNS packets and found the second flag hidden in the traffic
![[Pasted image 20260318195311.png]]
![[Pasted image 20260318195329.png]]
![[Pasted image 20260318195341.png]]
This lab provided a solid foundation in network traffic analysis. It combined theoretical learning with practical exercises in TAP placement and packet inspection. Finding the flags required attention to detail and an understanding of how different network protocols (HTTP and DNS) can carry hidden data.