---
marp: true
theme: default
@auto-scaling fitting
paginate: true

---


<style>
section {
  color: #fff;
  background: #ef5131;
  font-family: 'figtree';
}

h1, h2, h3 {
  color:#fff
}

a {
  color: #ef5131;
  text-decoration: underline #ef5131;
}

img.emoji {
  width:100px;
  height: auto;
  background-color: #fff;
  border-radius: 50%;
}

img{
  background-color: transparent;
}

</style> 

<style scoped>
h1 {
  font-size: 4em
}
</style>

# WebRTC extravaganza
## Standard browser-to-browser instant communication
TADSummit 2023

---
:wave:
# Romain Vailleux
![width:200px](./assets/apizee_logo.png)
_DevRel & Partnership Manager_
WebRTC Paris Meetup | DevFest Perros-Guirec 
@rvailleux 

---


<style scoped>
section {
  background: #FFF
}
</style>

![height:500px](./assets/apirtc_logo.png)

---


<!-- # WebRTC - a W3C Standard
2021 - WebRTC becomes a standard 
(per W3C and IETF (Internet Engineering Task Force))

:tada:

---
<!--
backgroundColor: #fff
color: #EF5131
 -->
<!-- # W3C - a Community-led Standardization Organization
- Any individual can participate to working groups
- Anyone can be a W3C member (membership fees apply :))
  - Browser Editors
  - End-users Solution providers
- Any member can propose for a new standard
- A standard will succeed only if it is elaborated collectively
- The working group leaders are making sure the consensus is going forward and reached before publication of a news standard.

---
-->
 # What is WebRTC?
![](./assets/flash_dead.jpg)

---
<!-- 
# Yes but what is WebRTC?
- **P2P**: A protocol to set up a P2P connection across some peers over the Internet
- **Real-time**: A way of exchanging video and audio and data streams (latency < 500ms)
- **Universal**: Implemented in most browsers (desktop and mobile) since 2013 (and any app that implements the W3C standard)
- **Secured**: Streams are sent through encrypted network ensuring integrity and confidentiality (Secured RTP, AES, HMAC-SHA1)
- **For developers**: Javascript APIs and HTML DOM objects

---
# How does it work?
![](./assets/arch_scheme.png)
*Scheme by Genesys*

---

# How does it work?

![height:500](./assets/mesh_sheme.png)
*Scheme by Fatih Erikci*

---

# How does it work?
![height:500px](./assets/sfu_sheme.png)
*Scheme by Fatih Erikci*

---
# Limitations
- Scalability
(look toward HLS or MPEG-DASH protocols for broadcasting use cases)
- Stream Integrity (UDP)
(comparing to WebSocket for example)

---
-->

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>


![bg](./assets/google%20meet.jpg)

## Instant Video communication
- Chroma key and background replacement
- Real-time image/audio processing
(ex: Google Meet)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>


![bg](./assets/discord.webp)

## Audio chat rooms
(ex: Discord)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/aircall.webp)

## Web client for VoIP/CTI
Signaling achieved through classic SIP protocol
(ex: Aircall)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 500px;
}

</style>



![bg](./assets/apizee_solution.png)

# Remote Assistance
(ex: Apizee)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>


![bg](./assets/lavitre.jpg)

## Remote presence
(ex: LaVitre)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>


![bg](./assets/starline.jpg)

## Remote presence
(ex: Google Starline)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/workadventure.gif)

## Virtual events
(ex:  Workadventure)

---


<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/kumo.png)

## Virtual workspace
(ex:  Kumospace)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/tunadesk.png)

## Remote Control
(ex:TunaDesk)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/webtorrent.png)

## File streaming 
(ex: WebTorrent.io, PeerTube)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/snowflake-schematic.png)

## Anti Censorship network 
(ex: Snowflake, WebRTC+Tor-based VPN to avoid state trafic blocking)


---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/auctions.jpg)

## Auctions
(ex: https://github.com/dedalusmax/live-auction)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/betting.png)

## Gambling and Betting

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/commerce.jpg)

## Live Commerce and Shoppable Video

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/education.jpg)

## Online Education

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/Scout%20robotic.jpg)

## Robotic
(ex: Scout, RTCBot)

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/telehealth.png)


## Telehealth and Remote Monitoring


---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/emergency.avif)

## Emergency Response and Communication

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/fitness.jpg)

## Connected Fitness and Health

---

<style scoped>
h1, h2, ul, p {
  background: #000D;
  width: 650px;
}

</style>



![bg](./assets/livemusic.jpg)

## Virtual concert
(ex: JamKazam)

---
<!-- 
## Where to start?
1. **Have a glance at the architecture** (20min by Tashi): https://www.youtube.com/watch?v=5ci91dfKCyc 
2. **Try plain WebRTC**: https://webrtc.org/ or https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API or https://web.dev/webrtc-basics/
3. **Find it too hard** and look for shortcuts: some real-time video service platforms offers out-of-the-box WebRTC SDK to speed up and stabilise your app: https://bfy.tw/UBcM

---
 -->
 
 <style scoped>
a {
  color: #FFF;
  text-decoration: underline
}
</style>

# Thx :pray:
@rvailleux
romain.vailleux@apizee.com
![width:500px](./assets/apizee_logo.png)

---

# Worthy advertisement

WebRTC Paris Meetup

![](assets/cat_animation.gif)