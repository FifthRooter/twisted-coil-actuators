A twisted coiled actuator (TCA) is an alluring idea. Instead of having a simple string being pulled by an electric motor, why not embed the actuation mechanism within the material itself? Just like animal muscles.  

This was a project I worked on as a student assistant in university, trying to manufacture nylon based twisted coil actuators, powered by resistance heated wires, with the goal of designing a breathing trainer vest that could contract and expand to assist children with breathing problems. I was also working on my vertical farming company at the time, so I also some incredible soft robotics applications for this actuator, if pulled off.

Initial testing was promising, but ultimately the idea was scrapped in favor of regular small servo motors due to several factors:
1. Heat dissipation - in order to get strong enough an actuation force, several individual coils needed to be combined together, which made it very difficult to cool them down fast enough to allow for rapid contraction/relaxation cycles that could match the rate of breathing of a child;
2. Safety - embedding resistance heating-based TCAs posed a safety risk that could not be easily done away with by using feedback sensors. Occasionally, overheating of the coils resulted in the nylon melting and breaking. And in case of some feedback loop failure, the resistance wire could heat up too much and cause discomfort at best, and set the vest material on fire at worst.
3. Feedback Control System - direct measurement of the resistance wire's temperature was practically impossible due to it being tightly woven into the nylon fishing line, and hence it was difficult to accurately determine when to stop the heating, which resulted in the TCAs melting after having reached the optimal actuation temperature. Using wire's resistance measurement as a function of its temperature was explored, but due to the several other drawbacks, was never implemented.
4. Lack of time - this was a side project for me, and the amount of effort, research, design and experimentation would've easily consumed a full time work schedule in order to actually realize it. Unfortunately, I underestimated the complexity of it and realized it quite late in the project. You live and you learn.

### TCAs: Revisited
After 5 years of completely forgetting the idea, I started thinking about it again. At the time I thought that we were probably really close to cracking mass-producable solid state electroactive polymer artificial muscles, which would've rendered the much lower tech TCAs irrelevant. However, we're still not quite there, nor are we anywhere near them being scalable and affordable. 

At first I didn't set out to revisit the nylon TCA concept, but it happened as a result of me purchasing a sewing machine and starting to think about woven materials. I was curious whether it would be possible to affect how a rubber tube bends once pressurized with gas if woven into a carefully woven fabric where some spots are tighter than others, causing the tube to bend at certain points, potentially creating a useful conceptual framework for developing articulating joints/fingers for use in soft robotics. Because the weave would be made from simple thread in one specific pattern, only a single possible motion/bend would be possible.

The next logical step was to decide how to transition from this one static bent position into full articulation, where the threads would tighten and loosen in different places on the fabric to cause the tube to change its bend pattern. Then the TCA idea came back into my mind.

So, I thought it might be a good idea to revisit this idea with a fresh new perspective.

There I was, sitting in the bike shop where I work and thinking about how to resolve the issues of waste heat, inconsistent heating of the nylon with the nichrome wire wrapped around it, or similarly silver-coated nylon fiber, and, of course, the safety aspect of having an exposed resistance wire touch external surfaces like skin, plastic, fabric etc. As I was considering different options as to how to deal with these issues, I suddenly thought of a common product we deal with at the shop - bike tires! Bike tires have a metal bead lining embedded into the rubber on each side of the tire to add additional structural support while pressed against the rim under pressure. That inspired me to think about fusing the resistance wire within the core of the nylon fibre. A **coaxial nylon TCA**!

This was quite the rabbit hole as I started investigating how the tires are made and how the beads are fused into the rubber. Turns out they're folded into the rubber and then the tire gets squished and stretched - it wasn't a directly translatable manufacturing process to such a tiny diameter fibre. However, it got the (idea) ball rolling.

### Make coaxial nylon TCAs cheap and accessible
Of course, with almost no budget, I wouldn't get far without thinking of how I could repurpose something affordable and accessible for a regular person on a budget. After all, these coaxial TCAs (CXTCAs) should be possible to make in a home lab setting. 

### Rough Plan
I plan on tweaking a 3D printer extruder a little bit by inserting a tiny syringe needle in the center of an extruder nozzle and feed a nichrome wire through it, with melted nylon flowing/extruding from around it throught the nozzle, pulling the wire with it and embedding it in the core of the newly extruded nylon fiber. 

### Mechanical/thermal property implications of remelting and drawing of nylon fiber

### Twisting setup
[Nylon-based twisted coil actuator twisting setup - Youtube](https://www.youtube.com/watch?v=FogEhFSXHNA)
![DSC08511](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/bb9535bf-276e-44a7-81a8-9f0d9c850ccd)
![DSC08504](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/a37ead29-0f2c-47ba-940b-73dd330d44b6)
![DSC08500](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/a71e67f6-4888-4a11-bbd7-43ac113819d3)
![DSC08495](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/b67f8a09-2532-4500-89e6-17990fb96566)
![DSC08493](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/a2c14878-bf42-4366-8904-7824a97cde94)
![DSC08484](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/70713c6b-05d7-405f-9466-df6c6c2cfba5)
![DSC08483](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/0485ba9f-df99-4354-8211-65f4640b933e)
![DSC08481](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/bf7bae39-d75b-4042-8cd2-215e8481a71a)

### Tests
![IMG_20190322_100229](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/2055e96e-a174-4929-a4ba-aa5712870d21)
![IMG_20190318_193056](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/1dc8a144-45af-448d-8566-147083f81db2)
![IMG_20190318_193032](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/5b03aefd-27bd-430a-875e-99d71c8675b9)
![IMG_20190318_172618](https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/f993fb6f-ce48-4e28-8bbd-c5bb69b775c5)


https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/1d620ba4-4050-4cbe-9367-09b7f9cec222




https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/3c78bc81-1077-4f20-8fcc-23502b65240f


https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/49b48f48-153f-4a1a-a1d4-c570336fcd51



https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/7d370865-4be7-47f9-991e-2ac5f94430b7



https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/53bbf641-fe5d-42c0-8598-cd9975a46543



https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/4da2715e-edb3-4c72-9eb5-accba51a6940


https://github.com/FifthRooter/twisted-coil-actuators/assets/22204845/92eececb-7e52-46c5-b986-2a805c1f9758


