# Computer Networks Project
This project demonstrates a simulated Distributed Denial-of-Service attack. This simulation sends protocol to an (fake) IP address or network, and floods it with packets; ultimately, this project documents the traffic flow and shows the results and (potential) effects of a DDoS attack. This is merely for educational/testing purposes only.

## Goal:
Although websites are more or less secured nowadays, this simple python script seeks to send protocol packets to a server. If successful, the targetted website/server would be down   

## Tools to use:
Etherape  
Raspberry Pi (with Kali Linux)   
https://www.hackthissite.org   
https://www.downforeveryoneorjustme.com/ 

## Usage:   
python simddos.py -s [IP/Domain]

## Results:   
Be sure to have etherape opened before you run the program. DDoS attack takes a while; you have to be patient. For this example, it took about ~10 minutes.   

During the process, you could see the traffic flow through Etherape:   
<img src="https://user-images.githubusercontent.com/25395966/39803530-1edc0d62-5326-11e8-8c2e-e69f30dcd06e.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803530-1edc0d62-5326-11e8-8c2e-e69f30dcd06e.jpg" width="200" height="200" />   

A successful attack would look like this on the terminal screen:   
<img src="https://user-images.githubusercontent.com/25395966/39803531-1ef8ffc6-5326-11e8-9eb2-a7c7c21b75f0.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803531-1ef8ffc6-5326-11e8-9eb2-a7c7c21b75f0.jpg" width="200" height="200" />   

On the browser, it would look something like this:   
<img src="https://user-images.githubusercontent.com/25395966/39803528-1ea883e8-5326-11e8-9b02-d7c040535ac2.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803528-1ea883e8-5326-11e8-9b02-d7c040535ac2.jpg" width="200" height="200" />   

Through Etherape, see the traffic flow in the network:   
<img src="https://user-images.githubusercontent.com/25395966/39803533-1f389b5e-5326-11e8-8503-03eaf6567ef2.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803533-1f389b5e-5326-11e8-8503-03eaf6567ef2.jpg" width="200" height="200" /> 


## Disclaimer:
Again, this is merely for educational/testing purposes only. Pleae use responsibly.


## References:
https://gbhackers.com/anonymous-ddos-a-website-using-kali-linux/   
https://github.com/cyweb   
https://github.com/jseidl/GoldenEye

