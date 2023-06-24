# Unity-Koekatamarin

## About

This is a real-time speech to text gadget inspired by one of my favorite anime, Doraemon. In this show there's a gadget called Koekatamarin, which is a potion like gadget that when consumed grants the user the ability to literally speak words into existence! As a kid, I always found this idea to be quiet unique so after 8 years, I've finally made one for myself.

![koekatamarin doraemon](https://github.com/rohithateappple/Unity-Koekatamarin/assets/131531154/21e6fd0d-4021-45cb-baae-2703642e486b)

## Blueprint

So essentially how this programs works is pretty simple, we just convert speech to text in real-time and then add a dimensional quality to the string. Real-Time transcription is essentially so I setted with Google Cloud Services. And it works pretty well! Of course Google API isn't completely free so you'll have to run the program with your own Google Service API. But once thats set, everything is good to go.

![vlcsnap-2023-06-24-18h52m01s205](https://github.com/rohithateappple/Unity-Koekatamarin/assets/131531154/c1e31a34-abbf-40a2-8307-14f717bfaddc)

## Tutorial

1. Download this repository as a .zip
2. Unzip and paste your service_key.json in this path (inside folder) --> Google Speech Transcriber\Debug\net6.0
3. Once thats done, open the game.
4. You might notice a Console has also popped up, DO NOT CLOSE IT! It's our speech server, don't worry the game terminates the console once you quit.
5. First you need to connect to the console server, do this by pressing 'E'.
6. Once the game has shook hands with the server, now its play time! Press 'LMB' to initiate recording and speech client. The first initialization always takes a little time, so be aware of enemies!
7. Once the first initialization is complete, the consecutive iterations are almost instantaneous. So have fun!

 
