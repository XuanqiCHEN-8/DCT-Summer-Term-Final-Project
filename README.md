# Good Plant

## Description
Good Plant is an interactive installation that explores how human ideas of care and order can become a form of control over non-human life.

## Introduction
This project is an interactive installation that explores how human ideas of order and care can become forms of control over non-human life. Inspired by Foucault's concept of the 'docile body,' the work transforms a plant into a mechanical body whose movement is restricted by a predefined system. Visitors are invited to gently 'groom' the plant with a comb, triggering its gradual movement from a bent position towards an upright, human-defined 'correct' state. Through this seemingly caring interaction, the work questions who determines what is considered normal, healthy, or better for another living being.

## Concept and Background
My interest in order started from observing how rules and patterns affect behaviour. In my first project, I explored how a simple rule could make people follow the same pattern. The work used many mouths. At first, all the mouths said '0''. When one mouth was pressed, it changed to '1', and then all the other mouths also started to say '1'. This made me think about how one action can create a shared rule and influence a group.
In my second project, I moved from human behaviour to animals. I used a pet leash and TouchDesigner to explore the relationship between humans and animals. The leash became a symbol of how humans guide, control and define the movement of another living being. These two projects made me interested in a wider question: how do human ideas of order affect non-human life?
This led me to Michel Foucault's idea of the 'docile body.' In Discipline and Punish, Foucault writes: 'A body is docile that may be subjected, used, transformed and improved.' For me, this idea is important because control does not always look violent. It can happen through small actions, repeated practices, correction and ideas of what is considered 'normal' or 'better'.
I was also inspired by Pierre Huyghe's Untilled (2012), which creates an environment where humans are not fully in control. Plants, animals, insects and other non-human elements develop within the environment and create their own relationships. Huyghe's work made me think about the difference between controlling nature and allowing nature to exist by itself.  
These ideas became the background for Good Plant, where I continue to question the relationship between order, care and control, and ask who has the right to decide what is 'good' for another living being.

## Technical Implement
I started by making a small prototype with cardboard to test the basic movement of the plant. I did not know much about mechanics, so I watched tutorials and learned how simple linkages, joints and motors work. After the cardboard model worked, I rebuilt the structure with 3 mm black acrylic and used M5 screws as moving joints. The main challenge was that the motor was too strong and sometimes broke the acrylic parts. I solved this by changing the position of the motor, making the connecting parts stronger, and using a longer linkage to spread the force. I also added limit switches to stop the motor at the two end positions. For the interaction, I used an ultrasonic sensor to detect the movement of the comb. Each interaction moves the plant one step, from 0% to 25%, 50%, 75% and finally 100%. I used Arduino to control the sensor and motor. After many tests, I adjusted the motor speed and movement time to make the movement slower and more stable. Finally, I added moss, leaves and a mechanical flower to make the structure look more like a plant while keeping the mechanical parts visible.

## Acknowledge
[1] Foucoult, M., 1975. Discipline and Punish.

[2] Huyghe, P., n.d. Untilled | Pierre Huyghe [WWW Document]. EstherSchipper. URL https://www.estherschipper.com/exhibitions/386-untilled-pierre-huyghe/(accessed 9.2.26).

[3] bileam tschepe (elekktronaut), 2022. Image revealing (new)TouchDesigner tutorial 59. YouTube.

[4] 10hrsh, 2013. Linkage mechanism for robot finger. YouTube

[5]C. Bowker, G., 2011. Sorting Things Out. PsycCRITIQUES 56https://doi.org/10.1037/a0025682

[6]MoMA, 2015. Pierre Huyghe's Untilled (Liegender Frauenakt) | MoMA[WWW
Document]. The Museum of Modern Art. URLhttps://www.moma.org/calendar/exhibitions/1537

[7]Coates, M., 2004. Journey to the Lower World [WWW Document] National Museums Liverpool. URL https://www.liverpoolmuseums.org.uk/artifact/journey-lower-world

[8]Bucher, T., 2018. If .. then : algorithmic power and politics. OxfordUniversity Press,Oxford

[9]MoMA, 2013. Hito Steyerl. How Not to Be Seen: A Fucking DidacticEducational.MOV
File. 2013 | MoMA [WWW Document]. The Museum of Modern Art. URL https://www.moma.org/collection/works/181784
