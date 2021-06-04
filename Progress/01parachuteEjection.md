# Parachute Ejection

This is how we will eject our parachute so that we can be able to recover our rocket after launch. There are many ways to recover the rocket mainly subdivided into pyrotechniques and non-pyrotechniques. I decided to use non-pyrotechniques as it is mainly fault tolerant and easier to make.

One mechanism in **DetMech** which was developed to automatically detach a rocket from its parachute line based on the apogee of the rocket. It is designed to assist in recovering rockets stagged by their parachutes. This method utilizes the use of a servo motor to open and close the hatch in order to eject the parachute.

Other mechanisms include :

1. Using a rubber band. The rubber band is wrapped around the body, nosecone or parachute door holding it in place until it is released.
2. Solenoid. The solenoid is used to activate thee recovery system via on board electronics usually in form of a pulse or a discharge from a capacitor. The solenoid activates a pin similary to the servo motor.
3. Mechanical armature. This involves using mechanical levers, strings and the likes.
4. Pyrotechnic. This is using a pyrotechnic charge whihc is ignited, or a wire is heated to activate the recovery system

One of the best methods is using mechanical systems since their failure rate is low. I chose servo motor as it averagely performs better in terms of cost and mode of design. The servo is an electromechanical system thus utilizing both the mechanical and electrical aspects.

## How it works

Ther mechanism is based on a simple clamp that holds the latch on to the nose cone. At the appropriate time, after maximum height has been reached with a specified delay, the clamp is moved which releases the parachute. By attaching the latch, nose cone and payload chamber to the parachute you will have a better chances in recovering the whole rocket.

The clamp is made up of a micro servo arm which is made of plastics. The latch on the other hand is made up of tough PLA material used in 3D printing the whole rocket. There can be large lateral force on the clamp during parachute opening. Aerodynamically, it has a low profile.

The bottom plate, payload chamber, which houses the electronics, is attached to the nose cone with screws rather than being glued due to large forces involved. The main parachute line should be fitted with a shock cord to reduce the stress on the clamp.

There is a little groove is to prevent the latch from moving side to side. This mechanism is contolled by the flight computer. This gives the rocket crew a chance t retrieve the rocket easily.

## More info

Using a micro servo to eject the parachute as well as detach it, will save on weight and complexity. The dual purpose mode of a single servo would be based on Christian Thomsen's RC dual chute release mechanism.
The servo could be controlled externally by a remote control. Allowing the rocketeer to release the rocket when appropriate.
A variation on the mechanism could make it completely internal to the rocket body reducing drag.
Another alternative is to replace the servo motor with a water soluble paper or plastic (such as Polyvinyl alcohol). This could be wound around the clamp to hold it down, and when it rains or humidity in the air would cause it to dissolve and release the mechanism.
