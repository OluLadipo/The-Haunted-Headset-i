[README (6).md](https://github.com/user-attachments/files/34597208/README.6.md)
# The Haunted Headset

*"Good evening, mortal. Thank you for calling the Astral Queue. Please speak your first name, last name, date of birth, and the last four digits of your soul."*

Eight calls. One mortal headset. Questionable spiritual protection.

### 🎧 [Answer the call](https://thehauntedheadset.netlify.app/)

*A call center cryptid experience. If you've ever worn a headset for a living, this one's for you.*

---

## Your shift tonight

The hold music never ends here. Eight haunted calls come through the Astral Queue, and three meters are watching every move you make:

- **Sanity**
- **Adherence**
- **Hold Time**

You'll meet the Rambling Banshee. The Profanity Poltergeist. The Labyrinth of Lab Results. Somebody wants their MRI read to them "real quick." Somebody is clearly at a car wash.

Survive all eight and find out which cryptid you've become.

## Six cryptids

**The Hold-Time Necromancer** · **The Verification Vampire** · **The De-escalation Witch** · **The Transfer Portal Guardian** · **The Frozen Screen Exorcist** · **The Queue Survivor**

You get your Soul Score, your dark gift, a survival strategy and a prophecy for your next shift. Then copy it into the team chat and watch who claims they got the Witch.

## Two more rooms

**Haunted Call Bingo.** Play it during a real shift. Tap a square when it happens: "B as in... um... B." A dog takes over the call. The caller orders a #4 combo while verifying. Five in a row wins you absolutely nothing except bragging rights.

**DJ Spooky Shift.** The break room booth. Every channel is a layer of the beat and a piece of your call: The Caller on drums, The Request on bass, Your Energy on organ and a Plot Twist on lead. Ride the faders, drop the mix, and get your call remixed along with a dare for your next shift.

## Behind the scenes

A few crumbs from the code. The rest stays on hold.

**Every shift starts the same.** Full sanity, decent adherence, zero hold time. It goes downhill from there.

```js
function fresh(){ return {i:0, san:100, adh:70, hold:0, tally:{}, order:[]}; }
```

**Twelve ways to win bingo.** Five rows, five columns, two diagonals:

```js
for (let r=0; r<5; r++) L.push([0,1,2,3,4].map(c => r*5+c));
for (let c=0; c<5; c++) L.push([0,1,2,3,4].map(r => r*5+c));
L.push([0,6,12,18,24], [4,8,12,16,20]);
```

**The DJ booth has three speeds,** and one of them is suspiciously familiar:

```js
const TEMPOS = [{n:"normal",bpm:104}, {n:"rush hour",bpm:124}, {n:"hold music",bpm:84}];
```

Every drum, bass line and organ chord is generated live in your browser with the Web Audio API. No audio files.

What the Poltergeist says, what each cryptid's prophecy is, and what happens when the screen freezes mid-note... you'll have to take the call.

## Built with

One HTML file. Vanilla JavaScript, CSS, SVG and the Web Audio API. No frameworks, no audio files, no build step.

Every caller is fictional. No real members, no real data. It's a game, not training.

## Made by

**Olu Ladipo**
[Portfolio](https://oluladportfolio.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/oluladipoinsights)

### 🎧 [The queue is waiting](https://thehauntedheadset.netlify.app/)
