# AVENGERS - AUTONOMOUS VEHICLE WITH EFFICIENT NAVIGATION FOR GARBAGE COLLECTION AND ECO-FRIENDLY RECYCLING AND SEGREGATION

## I. INTRODUCTION
Waste collection, storage and transport are essential elements of any SWM system and can be major challenges in cities. Waste collection is the responsibility of the municipal corporations in India, and bins are normally provided for biodegradable and inert waste. Mixed biodegradable and inert waste is often dumped, with open burning a common practice. Improvements to waste collection and transport infrastructure in India will create jobs, improve public health and increase tourism. Local bodies spend around Rs. 500–1000 per ton on SWM with 70% of this amount spent on collection and 20% spent on transport. Kitchen wastes (KW) comprises of household kitchen wastes such as vegetables peels, fruit peels, smashed fibre of fruits, spare uneaten food items, and food grains.KW is full of nutrients and organic materials, and simply biodegradable. The Kitchen wastes are often dumped into trash without realizing the recycling methods which can be turned into organic fertilizers. The farmers often refuse to buy organic fertilizers pertaining the cost of it. The use of chemical fertilizers leads to toxification of land and water. The urban households who generate a lot of organic waste never use the same for gardening
purposes.

 ## II. BASIC CONCEPTS AND TECHNOLOGIES USED

Our project is mainly made of four modules as follows:
1. Autonomous movement of robot vehicle.
2. Garbage collection.
3. Segregation of bio-degradable waste and non-biodegradable waste.
4. Recycling of biodegradable waste into fertilizer.

### Autonomous movement of robot vehicle
Detecting and avoiding obstacles in an environment using a single camera and a laser
source

          Steps:
          • Canny Edge detection
          • Line Fitting
          • Purring Line Segments and
          • Segmentation Figure

### Garbage Collection
• The places of dustbins are predefined and the vehicle collects the waste from it periodically.
• The dustbins are fitted with IoT sensors which notify the AVENGERS for urgent collection of garbage.
• The vehicle is fitted with robotic arm that lifts and dumps the waste in dustbin into the segregator section.
• The robotic arm is capable of lifting a dustbin of 30-80 liters of waste at a time.

### Segregation of Bio-Degradable Waste and Non-Biodegradable Waste
• The garbage collected is moved in a conveyor belt with vibrating action in order to send waste one by one through monitoring system.
• The monitoring section has a high quality camera which helps in categorizing the waste using Deep Learning techniques (Faster R-CNN model).
• A flipper arm flips the waste into the specified bin once it is categorized.

## III. PROPOSED MODEL

### 1. Autonomous movement of the robot vehicle 
The robot is autonomous and can travel indoors and outdoors at an average walking speed of a human. The two main criteria that the robot should fulfill are Collision avoidance and following definite path. The robot can be manually controlled via app which allows the user to define a specific path to travel. Robot moves by identifying free space in floor. Wherever floor is visible and free, it moves. Novel method for floor segmentation has been used. Laser source emits light that falls on obstacle if any, and based on position of laser light on obstacle in the image and distance of obstacle from robot, robot change its direction with different angle and continues to move. This movement information is stored in text file which is used to create map of the environment. Absence of laser light with different floor mark will be treated as hole in the floor and will be skipped.

### 2. Garbage Collection
The robot vehicle is fitted with camera which detects whether the object in front of it is a waste or not using Deep Learning techniques and image processing. If a waste is found, the robotic arm picks it up and puts in the bin provided. The public can also drop the waste into the bin.The robotic arm has a humanoid elbow provided with Servo motors to effect arm bending movement. It has pincers like fingers to hold objects, in this case wastes. The arm puts the waste in the bin at the top by
following programmed instructions.

### 3. Segregation of bio-degradable waste and non-biodegradable waste 
The biodegradable waste and non-biodegradable waste are separated using the following methodology as illustrated below. Once segregated, the non-biodegradable and biodegradable waste is stored in two separate portions inside the bin. The wastes that fall inside the bin the wastes made to move over conveyer towards the scanning area. Before that the wastes spread over the conveyer is separated one by one to the scanner by a separator rod fitted in it. The scanner consists of a PiCamera which uses Deep Learning techniques to differentiate the waste as bio-degradable and nonbiodegradable .The model is pre-trained with numerous datasets of wastes for accurate prediction. The aim is to ensure that no non-biodegradable waste falls into the biodegradable section and contaminates the output. In the extreme case plastics may damage the composting system.

### 4. Recycling of biodegradable waste into fertilize 
The bin which collects biodegradable waste is made of foam covering made from Temporene which is an insulating material. It has a motor inside and it comes complete with a heating element (remember warm compost is better compost). The air pump and filter allows air to circulate around the machine. This ensures that oxygen supply is maintained inside the composting section. Rotating stainless steel blades which make light work of any compostable in the main upper chamber are provided in the shredding area to shred the wastes to pieces. This makes sure food scraps and vegetable peelings are mixed together well before they are dropped down into a lower area where they rot. This lower chamber has a removable tray to make the whole thing easier to manage. The power to supply heat and airflow is generated from solar power .It also has a carbon-filter which takes out the smell. Like a composting robot, the machine grinds up the biodegradable waste of max 2.5 kg per day and regulates air flow and temperature to supercharge the production of the compost, which takes less than 2 weeks. The organic compost fertilizer can be retrieved from the drip collector and can be supplied or used. The indicators
show whether the bin is full or not and when it should be removed.

• Insulating material : Temperone
• Mixing blades: Stainless steel
• Max capacity : 100 litres
• Hours taken to convert into fertilizer: 8 to 10 hours
• Temperature to be maintained : 120-140C
• Air pump: To induce faster recycling
• Carbon filter: To remove odour.
• An indicator to notify the completion of recycling process.


![Model of AVENGERS](https://github.com/harish988/AVENGERS/blob/master/AVENGERS%20(1).jpg)


An AVENGER is a one-time investment which helps in collection, segregation, and disposal and recycling in safe manner at the source itself thus reducing manpower, time, and energy drastically.

### Municipal Corporation
The municipal corporation uses manual pickers to pick out wastes from the environment and then they are dumped and segregated only in rare cases. And that segregation process takes 10 to 12 days to complete. So the waste picking and recycling process done by corporation at present involves and time and high cost. But using our robot the job can be done in very minimal cost and the wastes can also be recycled within 8 to 9 hours. Comparatively it reduces the cost of the corporations in long term.

### Farmers
We can’t find farmers those who use natural fertilizers to their fields. The main reason is that they are not available. But with the help of our robot recycler natural fertilizers can be made available easily in minimal cost and using natural fertilizers is much better than chemicals. The recycled fertilizers can also be used for home gardening purposes by common people.

### Organic Fertilizer Companies and Non-biodegradable recyclers
The organic fertilizer companies can directly procure the fertilizer from the AVENGERS which save them industrial processes, money. The non-biodegradable recyclers can collect the separate bin of collected non-biodegradable waste and use them for other recycling purposes. This saves a lot of money in transportation, segregation etc.

## IV. CONCLUSION
Thus we ensure the following through implementation of our project: Promotion of Swaach Bharat Abiyan initiative and ‘No Visible Waste’ initiative. 100% segregation and recycling at source, Regular collection and safe disposal of waste.
