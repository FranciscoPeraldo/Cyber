# OhSINT - TryHackMe Write-up

## Resources
Clicking the **Download Task Files** link takes us to the following image:

![WindowsXP.jpg](Pasted%20image%2020260301222322.png)

## Step 1: Metadata
Since the image is the only resource available, we will check what we can find in its metadata.

We keep it simple and use online tools:

![Metadata tool 1](Pasted%20image%2020260301224533.png)
![Metadata tool 2](Pasted%20image%2020260301224009.png)

## Photo Owner Information
Highlighting the Copyright profile, we Google it.

![Google search](Pasted%20image%2020260301224730.png)

We find the following in each of the links:

![Twitter profile](Pasted%20image%2020260301224919.png)
![Twitter bio](Pasted%20image%2020260301225245.png)
![Twitter details](Pasted%20image%2020260301225332.png)

Perfect, we have obtained some of the answers required by THM:

![Answer 1](Pasted%20image%2020260301225459.png)
![Answer 2](Pasted%20image%2020260301225508.png)
![Answer 3](Pasted%20image%2020260301225603.png)

## What is the SSID of the WAP he connected to?
After getting the answer "London", THM gives us an important clue: use Wigle.net.

![Wigle.net search](Pasted%20image%2020260301230154.png)
![Wigle.net results](Pasted%20image%2020260301230756.png)

After creating an account, you can use the basic search. A pop-up will appear with the answer:

![SSID answer](Pasted%20image%2020260301230939.png)

## What is the person's password?
The answer to this question left a bad taste in my mouth. I'm not sure how long it would have taken me because I had no idea which password they were referring to. When I dragged the mouse, a word that was "hidden" in white text appeared:

![Hidden password 1](Pasted%20image%2020260301231611.png)
![Hidden password 2](Pasted%20image%2020260301232317.png)

And with that, all the questions asked by THM were answered.

---

## Answers Summary
- **Avatar of user:** cat
- **City:** London
- **SSID:** UnileverWiFi 
- **Personal email:** Ollie@example.com
- **Site where email was found:** Twitter
- **Holiday destination:** New York
- **Password:** [Pon aquí la contraseña exacta]

## Tools Used
- Online Metadata Viewer
- Google Search
- Twitter
- Wigle.net

## What I Learned
- How to extract metadata from images using online tools
- OSINT techniques for finding information across different platforms
- The importance of checking hidden elements on web pages
- How a single image can reveal so much information
