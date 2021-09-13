# hydra-experiment
experiment using Hydra


for the project: Metaquid the metaphorical bull of AI

youtube: https://youtu.be/D3cwWELK_ws

---

images used from the project: the Ten Thousand Bulls Metaquid project

site: metaquid.com/NFT

---

for test, connect to:

https://hydra.ojack.xyz

---

try the code:

// METAQUID by SMZ

pb.setName ("METAQUID")

a.show()

s0.initCam(1)

src(s0) .diff(o1) .out(o0)

osc ([5,3,9,17], .2, 0.8) .diff (o0) .scale( () => a.fft[3] *9 ) .out (o1)

osc(20) .color(0.5,0,0) .scale( () => a.fft[2] *1.5 ) .rotate(1,0.5) .add(o1) .out(o2)

noise(() => a.fft[1] *200) .color([1,.5],[0,2],0.5) .add(o2) .out(o3)

render ()
