# OhSINT - TryHackMe Write-up
## Resources
Clicking the **Download Task Files** link takes us to the following image:
![[Pasted image 20260301222322.png]]
## Step 1: Metadata
Since the image is the only resource available, we will check what we can find in its metadata.
We keep it simple and use online tools:
![[Pasted image 20260301224533.png]]
![[Pasted image 20260301224009.png]]
## Photo Owner Information
Highlighting the Copyright profile, we Google it.
![[Pasted image 20260301224730.png]]
We find the following in each of the links:
![[Pasted image 20260301224919.png]]
![[Pasted image 20260301225245.png]]
![[Pasted image 20260301225332.png]]
Perfect, we have obtained some of the answers required by THM:
![[Pasted image 20260301225459.png]]
![[Pasted image 20260301225508.png]]
![[Pasted image 20260301225603.png]]
## What is the SSID of the WAP he connected to?
After getting the answer "London", THM gives us an important clue: use Wigle.net.
![[Pasted image 20260301230154.png]]
![[Pasted image 20260301230756.png]]
After creating an account, you can use the basic search. A pop-up will appear with the answer:
![[Pasted image 20260301230939.png]]
## What is the person's password?
The answer to this question left a bad taste in my mouth. I'm not sure how long it would have taken me because I had no idea which password they were referring to. When I dragged the mouse, a word that was "hidden" in white text appeared:
![[Pasted image 20260301231611.png]]
![[Pasted image 20260301232317.png]]
And with that, all the questions asked by THM were answered.