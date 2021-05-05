## 1. Example of Industrial Application


### 1.1 The real-world smart home
   The scenario includes 3 areas, the sitting room, bedroom and balcony. Different smart devices are arranged in each area. The scenario includes 4 types of context, which is temperature, humidity, brightness and PM2.5. Smart devices can provide monitor, increase, reduce and assign for different types of context. For example, air conditioner can provide services such as temperature monitoring, increase the temperature, decrease the temperature, and assign the temperature. And air purifier can provide service that decrease the PM2.5.




<a href="https://sm.ms/image/a9k24uswTP8SrBn" target="_blank"><img src="https://i.loli.net/2021/04/19/a9k24uswTP8SrBn.png" ></a>

### 1.2  The runtime knowledge graph for smart home

Fraship has created 3 location instances (Ll), 12 context instances (Cl m, l is the serial number of the location), 11 device instances (Dd) and 29 service instances (Sd n, d is the serial number of the device). Fraship further specifies in the configuration two users Alice and Ken whose instances are created (U1 and U2). Based on the basic knowledge of the smart device deployment, Fraship establish from beginning 54 Located in, 29 Provide, 9 Monitor, 8 Increase, 5 Reduce and 7 Assign relationships.

<a href="https://sm.ms/image/q5ERfIASGzFLnbo" target="_blank"><img src="https://i.loli.net/2021/04/19/q5ERfIASGzFLnbo.png" ></a>



### 1.3  Concept Instances in the Knowledge Graph for Smart Home

The constructed concept instances are listed in Table.
<a href="https://sm.ms/image/NXKZHS7DP9rOdpf" target="_blank"><img src="https://i.loli.net/2021/04/19/NXKZHS7DP9rOdpf.png" ></a>

<a href="https://sm.ms/image/p9c3oymKSGsEDkW" target="_blank"><img src="https://i.loli.net/2021/04/19/p9c3oymKSGsEDkW.png" ></a>




## 2. Accuracy for Instruction Recognition

We utilize three data sets which are a Base set, a Paraphrase set and a Scenario set. All together, 2304 sentences are collected, in which 1424 are primitive sentences and 680 are compound sentences.

### 2.1 Base set
The language instructions in the Base set are generated by the rules in Section V-B. The Base set provides the basic instructions for the smart home service, which enables basic control of various devices. A total of 200 instructions are generated in our Base set which consists of 121 primitive sentences and 79 compound sentences.


https://github.com/Fraship/Fraship/blob/main/data%20set/Base%20Set.txt

### 2.2 Paraphrase set
The Paraphrase set is used to increase the diversity of language instructions in order to simulate the users’ usage of smart home devices in real-world scenarios as much as possible. Therefore, we invite several trained workers who are familiar with the devices and the corresponding services of the smart home to customize the the instructions. To this end, 1057 sentences are collected, of which 714 are primitive and 343 are compound.

https://github.com/Fraship/Fraship/blob/main/data%20set/Paragphrase%20Set.txt

### 2.3 Scenario set
The language instructions in the Scenario set are given by the volunteers who are not familiar with the various devices and the services. Based on our brief introduction about the smart home, these volunteers are asked to give the instructions according to their experience and understanding of smart home scenarios. The volunteers finally contribute 1047 instructions, including 710 primitive instructions and 337 compound instructions.

https://github.com/Fraship/Fraship/blob/main/data%20set/Scenarios%20Set.txt
