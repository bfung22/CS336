# DDoS Attack Simulator

This project demonstrates a simulated Distributed Denial-of-Service attack. In a nutshell, a DDoS attack overwhelms a target server with traffic to the point where it crashes. This simulation sends protocol to an IP address or network, and floods it with packets; ultimately, this project documents the traffic flow and shows the results and (potential) effects of a DDoS attack. This is not exactly a DDoS; however, this program utilizes threads acting as workers to simulate what a DDoS attack would look like. This is merely for educational/testing purposes only.

## Goal:
Although websites are more or less secured nowadays, this simple python script seeks to send protocol packets to a server. The targetted website would be flooded with HTTPS protocol packets, and if successful, the targetted website/server would crash.

## Installation/Tools to use:
Etherape ( see this video for installation: https://www.youtube.com/watch?v=JHeEHqzclnc )   
Raspberry Pi (with Kali Linux)   
Target site to test DDoS (because it's hard/illegal to DDoS other sites): https://www.hackthissite.org   
You could use this site to see if server is down: https://www.downforeveryoneorjustme.com/    

## Usage: 
python ddosg.py [url] -w [number of threads] -s [concurrent sockets]   
python3 ddosh.py -s [IP/Domain] -t [Threads]   

## Results:   
Be sure to have etherape opened before you run the program. DDoS attack takes a while; you have to be patient. For this example, it took about ~10 minutes.   

During the process, you could see the traffic flow through Etherape:   
<img src="https://user-images.githubusercontent.com/25395966/39803530-1edc0d62-5326-11e8-8c2e-e69f30dcd06e.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803530-1edc0d62-5326-11e8-8c2e-e69f30dcd06e.jpg" width="300" height="300" />   

A successful attack would look like this on the terminal screen:   
<img src="https://user-images.githubusercontent.com/25395966/39803531-1ef8ffc6-5326-11e8-9eb2-a7c7c21b75f0.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803531-1ef8ffc6-5326-11e8-9eb2-a7c7c21b75f0.jpg" width="200" height="300" />   

On the browser, it would look something like this:   
<img src="https://user-images.githubusercontent.com/25395966/39803528-1ea883e8-5326-11e8-9b02-d7c040535ac2.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803528-1ea883e8-5326-11e8-9b02-d7c040535ac2.jpg" width="300" height="300" />   

Through Etherape, see the traffic flow in the network:   
<img src="https://user-images.githubusercontent.com/25395966/39803533-1f389b5e-5326-11e8-8503-03eaf6567ef2.jpg" data-canonical-src="https://user-images.githubusercontent.com/25395966/39803533-1f389b5e-5326-11e8-8503-03eaf6567ef2.jpg" width="300" height="300" />   

DDoS-ing takes awhile, and due to increased security nowadays, it gets increasingly difficult over time. Sometimes, results may backfire:   
<img src="https://user-images.githubusercontent.com/25395966/39804774-d99c5dd4-5329-11e8-8b40-68ef11bd6955.JPG" data-canonical-src="https://user-images.githubusercontent.com/25395966/39804774-d99c5dd4-5329-11e8-8b40-68ef11bd6955.JPG" width="300" height="300" />    
google.com server was able to detect the DDoS attempt, and as a result, I was temporarily blocked. Henceforth, please use your best judgment.

## Disclaimer:
This is just a demo; the source code that's attached can also be found in the references below. Again, this is merely for educational/testing purposes only. Pleae consider the cyber laws when it comes to DDoS-ing, and use this responsibly.

## References:   
https://gbhackers.com/anonymous-ddos-a-website-using-kali-linux/   
https://github.com/cyweb   
https://github.com/jseidl/GoldenEye   
