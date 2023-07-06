# Graduate Research Assistant - ML Applications and Network Security
 Welcome to my GitHub.io page!
 *main tabs menu - like https://amandamartocchio.com/
## Home
Welcome to the world of Edwin Tenkorang! I am an electrical engineer with a passion for applied machine learning. Join me as I aim to become a top-notch researcher in next-generation technology's security and privacy. Explore my projects, research, and diverse interests, including music, sports, reading, and board games. Together, let's shape the future of technology and make a meaningful impact. Welcome to my world of research, creativity, and endless possibilities!
* Need a visually appealing layout with an eye-catching banner or image that represents my interests or field of research.
## About Me!
Hey there! I'm Edwin Tenkorang, an electrical engineer with a deep passion for the exciting intersections of security, privacy, computer and wireless networking, as well as power systems and smart grids. I love exploring how technology can empower and protect us in our increasingly connected world. I am driven by the desire to leverage technology to protect and empower individuals in our increasingly interconnected world and aim to become a top researcher in the interdisciplinary of field of security and privacy. My research interests span the boundaries between academia and industry, driven by a passion for practical solutions and real-world impact. I believe that by combining artificial intelligence with research in security and privacy in the context of power systems and networking, we can build more efficient, secure, and resilient infrastructures that meet the ever-growing demands of our digital society.

With a strong foundation in electrical engineering, a deep curiosity, and a commitment to continuous learning, I am excited to contribute to cutting-edge research in these areas. I believe that bridging theory and practice can pave the way for a safer, more connected future. Being a Teaching  Assistant in the Department of Electrical/Electronic Engineering is an incredible experience. I work closely with my mentor, Prof. E.A. Frimpong, and contributed to lectures while gaining practical insights into power system operation and protection. I also had the chance to work on some remarkable research projects. One of my favorites involved developing a deep learning technique that predicts and classifies cascading failures in power grids. In addition to my academic pursuits, I am a firm believer in the power of hands-on experience. As a Cybersecurity Research Assistant at the University Information Technology Services, which develops and controls all of K.N.U.S.T's IT deliverables, I had the opportunity to dive into network access control configurations, earn sponsored certifications, and explore open-source tools for logical security mapping.

Beyond my professional endeavors, I actively participate in initiatives promoting diversity and empowerment. One of the initiatives I am actively involved in is BecauseSheCan. As an event planner for the December For Women Who Code program, our aim was to empower women who are tech-savvy and skilled but lack access to laptops. We organized a laptop donation program and were able to provide 5 laptops to deserving women. Witnessing the joy and transformation these laptops brought to their lives was truly inspiring. Another organization close to my heart is the National Society of Black Engineers (NSBE). I participated in an outreach program where we assisted children in preparing for the BECE (Basic Education Certificate Examination). It was fulfilling to share my knowledge and help these young minds navigate their educational journeys.

Beyond my academic and volunteering pursuits, I have a grand vision. My ultimate goal is to revolutionize engineering and create a product that has a significant impact on the African landscape. I believe that through innovation, entrepreneurship, and engineering, we can bring about transformative change, addressing the unique challenges and opportunities present in Africa.
## Research
* https://www.nowness.com/seasons for inspiration for different tabs inspiration
### Power Systems:
#### Transformer Inter-turn Fault Detection using Artificial Intelligence
##### Background
In the realm of power systems, transformers play a vital role in efficient voltage transformation. However, they are vulnerable to inter-turn faults, which could damage their insulation and lead to power interruptions and equipment damage. You see, the windings of a transformer were tightly woven, and any fault occurring between adjacent turns had the power to wreak havoc. If left unchecked, these faults would disrupt the power supply, causing financial losses, damaging other equipment, and posing a threat to the brave souls operating within the realm. Detecting these faults at an early stage is crucial to prevent extensive damage and reduce outage time. Thus, a project emerged, driven by a dedicated team seeking to develop a method to detect and locate inter-turn faults before they caused severe harm. 
##### Objectives 
* Revise existing literature on artificial intelligence based methods for transformer inter-turn fault detection.
* Model and simulate different inter-turn faults in transformers using MATLAB/Simulink.
* Propose an improved artificial intelligence-based method for inter-turn fault detection in transformers.
##### Methodology and Results
Our project tackled the challenge of detecting inter-turn faults in transformers using a deep learning approach. Unlike previous research that focused solely on fault detection, we aimed to enhance the detection process by also determining the severity of the faults.

To achieve this, we employed a convolutional neural network (CNN) as our primary tool. The first step involved capturing the phase currents on both sides of the transformer. We then processed these waveforms concurrently using the Analytic Morlet wavelet as the mother wavelet to obtain coefficient matrices. Each of the six resulting waveforms was transformed into a scalogram image using its respective coefficient matrix. These six images were combined to create a single 256 x 256 BGR image, which was subsequently fed into a trained CNN model for fault detection.

Our CNN model was designed to not only detect faults but also evaluate the health of the transformer. When a fault was detected, the model provided predictions regarding the impacted phase, side, and the percentage of the transformer affected. Furthermore, the faults were classified into appropriate severity levels, namely low, medium, and high.

After an extensive training process, our fault detection scheme demonstrated remarkable performance. It achieved a minimum accuracy rate of 98% for fault localization, ensuring precise identification of fault locations within the transformer. Additionally, our severity prediction model exhibited a high level of accuracy, with an impressive R^2 evaluation score of 98.6%.

Through our project, we have successfully pushed the boundaries of fault detection in transformers. By integrating deep learning techniques and leveraging the power of CNNs, we have not only enhanced the accuracy of fault detection but also introduced a novel capability to assess the severity of inter-turn faults. Our advancements pave the way for quicker fault identification, reduced downtime, and improved maintenance strategies in power systems, ultimately contributing to a more reliable and efficient electrical infrastructure.

#### Cascading Failure Prediction using Deep Learning

The objective of this project was to enhance the prediction of cascading failures in power systems. Cascading failures occur when one or multiple lines of the power system fail, overloading other lines and eventually leading to significant load shedding and blackouts. To improve the prediction accuracy, I simulated a 118-bus system in Simulink and utilized deep learning techniques to predict the number of failed lines. By employing selected features and classifying the cascading failures into no, small, and large cascades, I achieved promising results. I will showcase the obtained results through relevant pictures.

### Networking
#### Transmit Power Optimization in IRS-NOMA Systems

This project explores machine learning approaches to minimize transmit power in two-cell intelligent reflecting surface (IRS)-aided non-orthogonal multiple access (NOMA) systems with joint detection. To tackle the original optimization problem, I converted the joint optimization problem of power allocation and phase shift into a pure phase shift determination problem, thus rendering it tractable.

#### Classification and Detection of Man-in-the-Middle Attacks in Software-Defined Networks (SDNs)

In this project, I designed and implemented a machine learning algorithm to classify and detect man-in-the-middle attacks in Software-Defined Networks (SDNs). I generated data using a simulated SDN environment with the help of NS-3. By leveraging machine learning techniques, I achieved accurate detection and classification of these security threats.


theme: Hacker
