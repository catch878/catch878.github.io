---

title: Thought Experiment - Can a AI get a mental illness? 
layout: post

---



/** Objective of this thought experiment: **/
To approach the idea of a mentally ill AI from a debugging point of view in order to get an understanding of how and why such an issue might arise.


/** Introduction/Motivation **/
A few weeks back I was reading a response to a question on AskReddit [1] that was detailing how a close friend had devolved into paranoid schizophrenia. The part of the response that piqued my interest was how the friend picked out patterns that weren't there, such as the coincidence of the initials CDR/CMD (Here [2] is an explanation of the pattern). This symptom is known as Apophenia [3] and is characterized by seeing patterns or connections in what would otherwise be meaningless data and is a common symptom in schizophrenia. Later that same day, I read an article detailing how researchers had tricked a deep neural network (DNN) image recognition system called AlexNet into recognizing objects that weren't actually there [4]. I realized then that the false positives that AlexNet were returning could essentially be classified as apophenia, although a much less complex case of it. In this train of thought, it is relatively easy to see how an AI could develop symptoms similar to mental illneses observed in people. It is also equally easy, and terrifying, to see how, in a few years, this might happen to the AI in your self-driving car while moving 75 MPH down the interstate.

Since AI's, both rudimentary and complex, will be at the core of many systems in the next few decades including infrastructure and safety-critical systems, analysing the concept of a mental illness in an AI is a useful excercise to understand what the failure modes of future AI controlled systems might be.


/** The Brain's Trust Model **/
One of the things that is hardest to understand about mental illnesses (for those of us who have never experienced it) is how exactly a completely functional and well-adjusted individual such as the one in the reddit comment can devolve so rapidly into schizophrenia without realizing that their thoughts no longer make sense.

The way to understand this is to see that there is an model of implicit trust between interconnected sections of the brain, e.g. the brain, by default, trusts all information that comes from the visual cortext as true. This makes sense from the evolutionary standpoint of better safe than sorry, the same justification behind things such as PTSD. For instance if you're a neanderthal with your neanderthal buddies in near the forest at dusk and you think you see a lion/tiger/bear moving the shadows its much better to run for it than to risk an encounter.

It is, of course, this model of trust that gives rise to many mental disorders and illnesses. In order to better understand how this model of trust works and how it can give rise to mental illness, lets look at Deja Vu. Deja Vu is something that has happened to almost everyone in their lives and is helpful in this analysis because it happens in healthy brains too and illustrates the model of trust. There are many theories as to what causes Deja Vu, but the symptoms are the same, a strong feeling that a presently occuring event or experience has been experienced in the past, regardless of whether it has actually happened. Despite what is essentially a malfunction of the memory functions of the brain, when you get Deja Vu, the feeling is usually strong enough to make one wonder whether an event did actually happen already, even if you know logically there is no way for a current experience to have happened previously. This is because an individual's consciousness implicitly trusts the memory centers of the brain, and if the memory centers say a current experience has happened before, the brain instictively trusts it.

Going back to the schizophrenia/apophenia example, it is a little clearer as to how such mental illnesses can arise so suddenly. A person whose pattern recognition capabilities have gone haywire will very likely believe that the false positive patterns they perceive are actually there because the brain is wired to implicitly trust itself and it's different components.


/** The Brain as an Analogy for the Computer **/
The human brain can be abstracted as a very complex computer that is composed of hundreds or thousands of different modules (modules/classes/packages; pick your poison) that all perform different functions necessary for a person to react to and interact with the world around them. The interesting part, though, is an individual's consciousness, which presumably resides in the brain. For our purposes, we will use wikipedia's definition of consciousness, which states that "Consciousness is the quality or state of awareness, or, of being aware of an external object or something within oneself." Now, I say consciousness presumably resides in the brain because we aren't really sure yet what causes consciousness, and there are many competing theories of what causes it (field theories of consciousness, electromagnetic theories of consciousness, the quantum mind, mind-body duality). But what we do know is that our consciousness requires the cerebral cortex in order to exist at all, so for simplicity I will base this thought experiment on the idea that the consciousness of an individual resides in the cerebral cortex.

The idea of 'mental illness' in an AI is not new and has appeared quite a few times in sci-fi and pop culture before. While it is not always explicitly stated that the AI are suffering from mental illness, their symptoms can be used to find an appropriate diagnosis (what follows is my rudimentary diagnosis of mental illnesses)
	SHODAN 		- System Shock 1 & 2 					- Moral restraints removed from programming | megalomania; god complex
	HAL 9000 	- Space Odyssey/2001: A Space Odysses 	- Contradiction of programming with orders | Paranoia (book explanation)
	WOPR 		- War Games 							- Not necessarily crazy, but a great example of horrific consequences of 'mental illness' (maybe )
	GLaDOS 		- Portal 								- Narcissistic personality disorder; bipolar
	Cortana 	- Halo Series 							- Rampancy (resembles bipolar disorder/schizophrenia)

While the concept of mental illness in AI has been explored before, I think it would be a fruitful exersize to explore this concept from a more logical view point and theorize how it might arise in a real AI. To do this, lets return to the idea of the computer as an analogy of the brain.

A rudimentary AI at the university of texas was even used to simulate schizophrenia to test a theory on its cause.

However, I want to explore this concept in a different fashion and attack it more logically. 

Returning to the idea of the brain as a computer, lets start with the consciousness as the core component of the computer. In software, this would analogous to the part of a program that sees all the inputs and then decides what to output. In hardware, this would more or less be the CPU (It can even only do one thing at a time (per core) just like the brain - multitasking is a myth)(These are very simple analogies, and as such are flawed in multiple ways. But they will serve for our purposes). This consciousness core is connected to all other modules of the computer. In the brain these modules would be I/O devices, such as the optical nerves, sensory nerves, vocal cords. In addition to the I/O devices, there would be co-processors and embedded micro-processors to represent things such as language and visual processing centers of the brain which do processing of external inputs so that the conscious core only needs to worry about relevant input data.


/** Metacognition as a Tool for Identifying and Treating Mental Illness **/