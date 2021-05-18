## 1. Example of Industrial Application


### 1.1 The real-world smart home

The scenario includes three areas: living room, bedroom, and balcony. Smart devices are arranged in each area. The scenario includes four types of contexts: temperature, humidity, brightness, and PM 2.5. Smart devices provide services such as Monitor, Increase, Reduce, and Assign for different contexts. For example, air conditioners can monitor, increase, decrease, or assign the temperature. Air purifiers can provide services that decrease the PM 2.5.

<a href="https://sm.ms/image/kxMZQfN213bhnEF" target="_blank"><img src="https://i.loli.net/2021/05/07/kxMZQfN213bhnEF.png" alt="scenario210426.png"></a>

### 1.2  The runtime knowledge graph for smart home

Fraship created three location instances (Ll), 12 context instances (Cl_m, where l is the serial number of the location), 11 device instances (Dd), and 29 service instances (Sd_n, where d is the serial number of the device). Fraship further specifies two users, Alice and Ken, whose instances are created (U1 and U2). Based on the basic knowledge of smart device deployment, Fraship initially established 54 Located in, 29 Provide, 9 Monitor, 8 Increase, 5 Reduce, and 7 Assign relationships.

<a href="https://sm.ms/image/GNECl3BqOV61inS" target="_blank"><img src="https://i.loli.net/2021/05/07/GNECl3BqOV61inS.png" ></a>


### 1.3  Concept Instances in the Knowledge Graph for Smart Home

The constructed concept instances are listed in Table.

<a href="https://sm.ms/image/ykOjlctn5QiGwsV" target="_blank"><img src="https://i.loli.net/2021/05/06/ykOjlctn5QiGwsV.png" ></a>
<a href="https://sm.ms/image/tefuCOTRxPK7oq3" target="_blank"><img src="https://i.loli.net/2021/05/06/tefuCOTRxPK7oq3.png" ></a>



## 2. Accuracy for Instruction Recognition

We used three datasets: a base set, a paraphrase set, and a scenario set. In total, 2304 sentences were collected, including 1424 primitive and 680 compound sentences.
### 2.1 Base set

The language instructions in the base set were generated using the rules described in Section V-B. The base set provides basic instructions for the smart home service, which enables basic control of various devices. Our base set included 200 instructions (121 primitive and 79 compound sentences).

https://github.com/Fraship/Fraship/blob/main/data%20set/Base%20Set.txt

### 2.2 Paraphrase set

The paraphrase set is used to increase the diversity of language instructions and simulate users’ usage of smart home devices in real-world scenarios as much as possible. Therefore, we invited several trained workers who were familiar with the devices and corresponding services of the smart home to customize the instructions. Thus, we collected 1057 sentences, including 714 primitive and 343 compound sentences.

https://github.com/Fraship/Fraship/blob/main/data%20set/Paragphrase%20Set.txt

### 2.3 Scenario set

The language instructions in the scenario set were provided by volunteers who were unfamiliar with the various devices and services. Based on our brief introduction to the smart home, these volunteers were asked to give instructions according to their experience and understanding of smart home scenarios. The volunteers provided 1047 instructions, including 710 primitive and 337 compound instructions.

https://github.com/Fraship/Fraship/blob/main/data%20set/Scenarios%20Set.txt
