
# INTRODUCTION


License plate recognition systems have become indispensable in modern applications, revolutionizing areas such as traffic control, surveillance, and automated toll collection. This project represents a convergence of cutting-edge technologies, blending hardware and software components to meet the evolving demands in this domain. By integrating advanced image processing techniques with state-of-the-art neural networks, the system aims to deliver a highly accurate license plate recognition solution. Overcoming challenges like varying lighting conditions and diverse plate designs, the project strives to address the multifaceted requirements of license plate recognition applications. In essence, this project epitomizes the relentless pursuit of innovation in computer vision and machine learning, highlighting the transformative potential of merging technologies to tackle complex real-world challenges.





## Detailed Design
The data utilized for training and validation of the license plate recognition system consisted of a diverse set of images containing Indian license plates captured under varying environmental conditions and scenarios. The dataset encompassed a wide range of license plate designs, fonts, sizes, and orientations to ensure the robustness and generalization capability of the developed system.

Data collection involved sourcing images from both publicly available datasets and custom capture sessions to cover a comprehensive spectrum of real-world scenarios. Images were captured using different cameras and devices to simulate varying lighting conditions, angles, distances, and perspectives commonly encountered in practical applications.

To ensure the reliability and accuracy of the system, rigorous validation procedures were conducted using annotated ground truth data. Each image in the dataset was meticulously annotated to delineate the exact location and content of license plates, including individual characters. The annotations served as reference points for evaluating the system's performance across different metrics. To comprehensively evaluate the system's performance, multiple key metrics are employed:

Character Segmentation Accuracy: Gauging the system's accuracy in segmenting individual characters from license plates.
Character Recognition Accuracy: Assessing the CNN model's accuracy in recognizing and interpreting segmented characters.
Overall System Accuracy: Calculating the overall accuracy of the entire license plate recognition system in retrieving and presenting the correct license plate number.

## Architecture


![Screenshot 2024-02-26 203816](https://github.com/Yashasvigm14/Licence_plate_recognition/assets/132649643/e8c869fa-bea8-473a-8256-61ac45db71a2)


![Screenshot 2024-02-26 203838 - Copy](https://github.com/Yashasvigm14/Licence_plate_recognition/assets/132649643/5f083dad-e294-4386-9eb2-5270e920efdb)


![Screenshot 2024-02-26 203858](https://github.com/Yashasvigm14/Licence_plate_recognition/assets/132649643/7f467458-722c-4d70-aa54-b10e2f584a7b)



## Results

The model trained for 18 epochs achieved an outstanding accuracy of 88.67% using the provided dataset. This remarkable performance highlights the effectiveness of the chosen approach and techniques in recognizing alphabets (A-Z) and digits (0–9) from 28x28 images. Augmenting the training data with techniques like width and height shift using the ImageDataGenerator class in Keras contributed to the model's robustness and generalization.

Input Image:

![car](https://github.com/Yashasvigm14/Licence_plate_recognition/assets/132649643/3cef05df-7f8c-4d69-adfe-3beb07f5e04e)

Predicted output:

![Screenshot 2024-02-26 214029](https://github.com/Yashasvigm14/Licence_plate_recognition/assets/132649643/8ad72cdf-4eb9-4b9c-8ea6-56d36c292cae)

