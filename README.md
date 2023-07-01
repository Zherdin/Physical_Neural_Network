# Physical_Neural_Network
Physical Neural Network (PNN) is a network of artificial neurons for building automated control systems

Author: Dmitriy Zherdin, 01.07.2023

There are two tendencies in modern science:

The tendency to narrow specialization, which consists in the fact that from scientific disciplines are allocated more narrow directions, for example, among biologists it is not difficult to find scientists who have devoted all their life to the study of butterfly proboscis;
the tendency to merge scientific disciplines that until recently were completely incompatible. Examples of combining the sciences are bioinformatics (a science that combines general biology, molecular biology, cybernetics, genetics, chemistry, computer science, mathematics and statistics), astrogeology (a discipline that studies celestial bodies: planets, moons, asteroids, comets, meteorites). Obviously, the impetus for the unification and specialization of scientific knowledge was the achievements of technological progress of the past and present century.
This paper will also touch upon the discipline, which in the 21st century has branched off from computer science, but its roots are in neurobiology. In scientific circles the mentioned discipline has received a strange name - "machine learning".

Currently, there is no standard, generally accepted definition of what the science of machine learning does. For example, a Stanford course on machine learning provides this definition: "Machine learning is the science of making computers work without the use of explicit programming. At the same time, Carnegie Mellon University states, "The field of machine learning seeks to answer the question: how do we build computer systems that improve automatically (by gaining experience), and what are the fundamental laws that govern all learning processes?"

The objects of the science are: artificial neural networks, deep neural networks, artificial intelligence. However, the interest of the author of this paper lies not in the field of software implementation of neural networks used for data processing, but in the field of so-called "physical" artificial neural networks, which are used to control physical automation objects, as well as to collect information about the state of control objects.

It is assumed that a physical neural network entangles control objects, linking them into a single whole. Each physical neuron of the neural network is located directly next to the control object, for the control of which it (the neuron) is responsible. Thus, an automated system of object control is formed, the topology of which resembles a network of the nervous system of a living organism.

The obvious advantage of such a distributed control system is its high fault tolerance, since the failure of one physical network neuron does not cause the failure of the entire control system. Only the object, for which the failed neuron was responsible, is deprived of control.
