This project is centered around two drone models. The DJI Tello, and the DJI Mini. These are two relatively cheap drone models that we've been using for
AI pathing projects. Unfortunately, in order to charge them currently, the battery needs to be removed from the drone and charged separately,
or the drone needs to be physically plugged in, disabling flight capabilities. It's my hope to change that. If I can successfully create a charging platform,
with a minor attachment to the drones themselves, then those two drone models will be free to follow fully automated paths on a schedule,
or simply take off whenever certain conditions are met.

Development Updates, May:

     The initial prototypes have been made for both the charging circuit and for the DJI Tello 3D printed model for the charging base. I'm happy to report,
     the DJI Tello fits well within the housing, and the three different parts fit together nearly flawlessly. However, some filing was required for the proper
     fitment, something I'll have to refine with future prints. I just had the tolerances set too tight, the material used for printing tends not to be absolutely 
     perfect during the printing process. Shaving down the sides just a hair should do the trick. I took all measurements I needed by hand. so I was particularly
     suprised when this worked :)

     What remains to be seen is wether the circuit I've designed will fit, and, even if it doesn't, how well it will work. I'll be adding that to this page as soon
     as parts are available and I can begin documentation of the physical circuit itself. The goal of this project after all is replicability, so I want to limit
     the effort that goes into putting all of this together. Of course, that will also come with plenty of refinement down the line. 
     Until then, know I'll be taking the proper precautions when it comes to circuit design.

     As for the charging solution itself, I've decided the best way forward for the time being. The battery on the DJI Tello connects via special contacts at
     one end of the battery, which mesh with the corresponding contacts on the Tello itself. Those contacts are accessible through a narrow opening below the drone.
     With some specially designed copper contacts of my own, it's my hope to be able to create a charging circuit that _includes_ the DJI Tello itself.
     The reason I'm opting for this approach over any other currently, is I think this would be the easiest way to charge it without it 'knowing.' Think of the
     battery like a bucket. Simplistic, I know, but follow me. When you charge that battery, the bucket fills. When you're done, and the bucket is full, you
     operate the drone, and that bucket is slowly dumped out. The DJI Tello is designed so that if that bucket is being filled, it can't also be drained. But,
     If I can utilize the same connection point that's already being used, then I should be able to fill the bucket regardless, and still allow operations. 

     Of course, like all electrical issues, a solution is never that simple. 'Tapping in' to this connection means if ever there's an overcurrent condition, or 
     too much power is being sent through the connection at one time, then there is a risk posed to both the drone and the battery. With proper safeguards,
     that should not be an issue, but it is something that will plague the back of my mind during development. 

     I do still have other options at my disposal should that not work out. There is a charging port on the side of the drone I could use, but the Tello is
     designed to shut off flight capabilities while it detects power going to that port. I'll have to find a creative way to circumvent that should I need to. 
     There's also the potential of utilizing the Tello battery charging dock itself, and just lengthening that connection. Of course, to do so, I'd have to
     find a way to electrically isolate the drone from the battery during that process. But for now, we'll keep on the path of least resistance.

Development Goals, June:

     Begin tinkering with the actual circuit design. I've got two spare batteries at my disposal currently, and I'll be making a circuit I can use to charge them
     outside of the drone first. Once I'm confident I can do that reliably, the goal is to get the circuit to work with the battery connected to the drone. Once
     I'm confident I can do _that_ reliably, the goal will be to fit the circuit into the freshly designed 3D model. 

     In short, June is the month of electrical engineering!

Development goals, July:

     With the electrical engineering settled, July will hopefully be the month of refining. Taking our initial 3D model and circuit prototype, and furthering the 
     design so just about anyone with a 3D printer and a basic understanding of ciruits could put this together. If that goes well for the Tello model, I'll
     then take everything I've learned so far and get to work on creating one for the Mini. That process should be substantially faster, though will likely be
     reserved for August.

     
