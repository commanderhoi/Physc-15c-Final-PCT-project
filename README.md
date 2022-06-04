# Physc-15c-Final-PCT-project
#### Jacob Nie, Justin Hsu, Linda Jin

Final report for group The Wednesdays's point contact transistor.

## TRANSISTORS: POINT CONTACT TRANSISTOR

[jacob]

## THE GERMANIUM DIODE
Early semiconductor developments used germanium
as the commercial semiconductor material however was
eventually replaced by silicon. However, germanium
diodes have the advantage of an intrinsically low forward
voltage drop, typically 0.3 volts; this low forward volt-
age drop results in a low power loss and more efficient
diode.[1] Hence, we used a germanium diode as the source
of semiconductor to build our device on.The diode looks
like Figure. 1.

![fullDiagram](https://user-images.githubusercontent.com/102839205/171823949-86059013-235c-4df7-91c3-73513a020ae3.jpg)

The diode was broken carefully with a cutting pliers.
Using a microscope, we were able to guess the structure of
the germanium diodes we purchased. We demonstrated
that we could reliably and reproducibly crack open diodes
to reveal the Ge p-n junction inside.
The orange side has an obvious square block of metal
(Figure. 2a), which is different from the round conductor
on the black side of the glass (Figure. 2b). We deduced
that the metal block is the germanium, with the approx-
imate size of 0.3mm × 0.3mm through 10x image on mi-
croscope. We can see the relative sizes of the tentative
germanium block and the metal base in Figure .2d.
<img width="511" alt="截屏2022-06-03 上午1 54 15" src="https://user-images.githubusercontent.com/102839205/171824249-1fb1a07f-ec0d-431e-a945-c11a6000c7af.png">

The diode structure can hence be anticipated as a small
germanium block in contact with two larger metal con-
ductor bases. The anticipated inner structure is plotted
in Figure. 3.

![structure](https://user-images.githubusercontent.com/102839205/171824363-6b7fca27-92a9-49a7-83db-8ef2f0faa78f.png)

This small block of germanium is what we needed for
a P-N junction on semiconductor as one side is P-doped
and the other is N-doped. Based on this existed structure, we came to perceive our fabrication plan for a bipo-
lar P-N-P transistor.


## TESTING THE CUT-OPEN DIODE

We proved that the metal block is indeed germanium by putting an exterior contact on it. By measuring the current and forward voltage of the circuit of both an intact diode and the cut one with the same resistor, we can see they behave the same. 

 Forward-biased I-V curve of intact Ge diode |  Forward-biased I-V curve of cut Ge diode
:-------------------------:|:-------------------------:
![unnamed-3](https://user-images.githubusercontent.com/102839205/171825211-e5f72332-6e4f-4b2e-baa9-658ff21afa54.png) | ![unnamed-4](https://user-images.githubusercontent.com/102839205/171825235-0e19c7b8-c42c-421e-9b5f-0da2cd054c49.png)
![unnamed](https://user-images.githubusercontent.com/102839205/171825358-5f8f40e6-297a-493b-a237-7816014ff110.png) | ![unnamed-2](https://user-images.githubusercontent.com/102839205/171825376-883bab70-8992-405a-8a84-90fc3ccb59a1.png)

## Fabrication Process: Difficulties & Solutions
Instead of only one p-n junction we need two for a p-n-p transistor. We can achieve this by etching a thin scratch on the germanium. But considering the size of the germanium and stabilizing the two pins to keep in contact with the germanium without touching each other, we need a better plan for the feasibility and the unity of the device.
Initial Plan
:-------------------------:
![unnamed-5](https://user-images.githubusercontent.com/102839205/171825780-99aac7ea-5fa9-487b-89d4-c6cb43a2969f.png)|


Hence, another essential issue is to establish the micropositioning on x-y-z axes. We solved the problem of micromanaging the two pins as a whole entity by hot gluing them together. The conductor has insulating coating, so we kept the parts inside the **hot-glued tube** insulated and sanded the two ends of the wires to conduct current across. Another challenge arise when the two contact points are too close to each other, they may not be detached. So we cut the excess sanded part to make sure only the cross section contacts with the germanium is conductive. The resistance between two ends on the other side of the hot-glued tube was measured to be zero, so disconnected between two terminals.

<img width="792" alt="截屏2022-06-03 上午2 17 47" src="https://user-images.githubusercontent.com/102839205/171826358-ecf2f6ee-8563-4b9d-80f6-6b8096fc0545.png">

Two hot-glued terminals in contact with the germanium, stabilized together by a tape.
:-------------------------:
![T20220525_001_0001](https://user-images.githubusercontent.com/102839205/171826908-b02a3f55-5dc7-4c07-9158-ca8dfee5aa57.jpg)|

Another detail is that the conductor is very thin so even easier to break after being sanded. The hot glue protects the wires. The wires were soldered to jumper wires for taking measurements through LabJack, and heat shrink tube was also used to protect the fragile device,
<img width="792" alt="截屏2022-06-03 上午2 26 10" src="https://user-images.githubusercontent.com/102839205/171827860-8b9caa78-21c2-4945-85bd-6afd4b5e1396.png">

## PERFORMANCE
The device managed to show that we had contact between the collector, the doped germanium, and the emitter. We saw a pretty clear saturation region between Ve and Vc. 

## FUTURE IMPROVEMENTS
Ideally, we'd want to test our device for amplification. It would also be advisable to use a bigger diode to establish better contact. 
