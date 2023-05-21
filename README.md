# Nvidia-final-project: Volacano eruption detection AI
The purpose of a volcano detection AI model is to analyze various data sources and identify potential volcanic activity or eruptions. Volcanoes can be highly unpredictable, and their eruptions can pose significant risks to human life, infrastructure, and the environment. By leveraging AI and advanced data analysis techniques, volcano detection models aim to provide early warning signs of volcanic activity, enabling timely responses and mitigation measures.
![modeltrained](https://github.com/gaurijain21/Nvidia-final-project/assets/132837846/cfb2a8a2-f725-4c56-8fb5-1953a8b74126)

Volcano detection AI models are designed to analyze data from seismic sensors, gas emissions monitoring, satellite imagery, and ground deformation measurements. By processing and integrating these data sets, the models can identify patterns and indicators of volcanic activity, allowing for early warning and evacuation measures to be initiated. Overall, the purpose of volcano detection AI models is to improve our ability to monitor, predict, and respond to volcanic activity, thereby minimizing the risks to human life and property. These models play a crucial role in volcano monitoring networks, aiding scientists and authorities in making informed decisions and taking proactive measures to mitigate the impact of volcanic eruptions.

Directions: With your Jetson Nano, you can upload the Volcano AI script into your jetson-inference. With imagenet setup with the code, load your desired images within network and get an image classification. This image classifcation is stored into a dictionary database that can be accessed via the database_print code.

Imagenet: The imageNet object accepts an input image and outputs the probability for each class. Having been trained on the ImageNet dataset, the GoogleNet and ResNet-18 models were also downloaded.

After image classification code, go to your terminal and type
1. cd my-recognition
2. wget https://github.com/dusty-nv/jetson-inference/raw/master/data/images/polar_bear.jpg
3. python3 my-recognition imagename.jpg --> here should be your already saved image name and extension in my-recognition folder.

Note: I have images saved as volcano1.jpg, volcano2.png etc so I use python3 my-recognition volcano1.jpg for step 3 in visual code studio terminal.

Video explaination: https://youtu.be/5h1y6mBVYow

