﻿AUDIO TRANSMISSION THROUGH LI-FI USING NODE MCU
  


  Submitted By :
            VAISHNAVI V (201EC277) 
           SOBIKA S K (201EC256) 
              VINOTHINI R (201EC288) 






**ABSTRACT **
In today's interconnected world, the proliferation of wireless devices accessing the internet  continues to surge, leading to escalating network complexity and a strain on available wireless  radio bandwidth. This surge also raises concerns about the potential for interference in radio  frequencies, which can compromise the reliability and security of data transmission. However, Li 
Fi technology offers a promising solution by leveraging Visible Light Communication (VLC)  through light-emitting diodes (LED's) for data transmission. Li-Fi operates by using LED's as  transmitters and photo-diodes as receivers, utilizing light waves to carry data instead of traditional  radio frequencies. The use of light for data transmission not only enhances security but also  mitigates concerns about radio frequency interference. Moreover, the rapid advancements in LED  manufacturing have led to the development of highly efficient, durable, and long-lasting LEDs,  making them suitable for both private lighting and data transmission purposes. The effectiveness  of Li-Fi is further underscored by its ability to achieve data transmission rates of several gigabits  per second (GBPS), surpassing many existing wireless technologies. Consequently, the  implementation of Li-Fi technology holds immense potential for revolutionizing communication  systems, particularly in environments where security, speed, and reliability are paramount. The  design and implementation of Li-Fi audio transmission systems exemplify the innovative  applications of this cutting-edge technology, offering a glimpse into the future of wireless  communication. As research and development in Li-Fi continues to progress, the possibilities for  its integration into various industries and everyday applications are limitless, paving the way for a  more efficient and interconnected world.
________________________________________________________________________________________________________________________________________________________


**OBJECTIVES** 
The project aims to develop a prototype system for audio transmission utilizing Li Fi technology. It involves implementing modulation and demodulation techniques  to encode and decode audio signals for transmission via light waves. The integration  of Node MCU with Li-Fi modules facilitates the establishment of communication between the transmitter and receiver components. Real-time audio transmission with  low latency and reasonable audio quality is a primary goal of the project.  Additionally, the investigation of potential applications and scenarios for Li-Fi based audio communication, such as in home automation, audio streaming,  and other IoT domains, will be explored. This endeavor seeks to demonstrate the  feasibility and practicality of utilizing Li-Fi for audio transmission, opening avenues  for innovative applications in various domains.
__________________________________________________________________________________________________________________________________________________________
PROPOSED SYSTEM BLOCK DIAGRAM: 
  



Figure 1.1 Transmitter side of the proposed system


  

Figure 1.2 Receiver side of the proposed system 




 RESULTS: 
The transmission of audio signal was done through a Smartphone at the transmitter  end, providing the audio signal through the 3.5 mm jack. The 3.5mm audio jack and  the input audio from the phone is converted from digital to analog. A typical 3.5mm  audio jack has three output lines namely, right, left and the ground. The left and right  have the audio output signal, which is connected to the negative of the 9V battery.  The ground of the 3.5mm jack is given to the negative of the LED array connected  on a breadboard and the positive of the 9V array is given to the resistors in series  with the LED array. This circuit effectively modulates the intensity of the LED light,  which acts as carrier wave, according to the effective voltage difference. The  fluctuations occur at a high speed, invisible to the naked human eye. This variation  in the intensity of light, however, is captured on a solar panel that acts as a photo  detector. It captures all the variations and sends the received signal to the amplifier,  which amplifies the signal and gives the audio output through the speaker. The  sound intensity received from the speaker varies based on the distance of the solar  panel from the LED arrays. This shows that the information can be received from  the line of sight of the LED array. As the distance between the LED array and the  solar panel increases, the intensity of light reduces and the light becomes more  scattered thus, making it difficult for the solar panel to detect all the light rays being  emitted.




CONCLUSION: 
In conclusion, the exploration of audio transmission through Li-Fi using Node MCU  has unveiled promising avenues for communication technology. Throughout this  study, the potential of Li-Fi as an alternative or complementary technology to  traditional radio frequency-based systems has been highlighted. Li-Fi offers several  advantages including higher data rates, enhanced security, and reduced  electromagnetic interference, making it a compelling choice for various applications,  including audio transmission. 
The implementation of audio transmission through Li-Fi using Node MCU has  demonstrated feasibility and effectiveness. By modulating audio signals onto light  waves and transmitting them through LED bulbs, Node MCU microcontrollers have  facilitated the integration of Li-Fi technology into existing communication  frameworks. The experimental results have showcased reliable audio transmission  with minimal latency, affirming the practicality of this approach. 
Furthermore, the scalability and adaptability of Node MCU-based Li-Fi systems  open doors to a plethora of applications across different domains. From wireless  audio streaming in smart homes and offices to secure communication in industrial  environments, the potential use cases are vast. Additionally, the low-cost nature of  Node MCU and readily available components make it accessible for hobbyists,  researchers, and developers to explore and innovate in the realm of Li-Fi-based  communication.
However, it is essential to acknowledge the existing challenges and limitations  associated with Li-Fi technology. Factors such as line-of-sight requirement,  susceptibility to ambient light interference, and the need for specialized hardware  may pose constraints in certain scenarios. Addressing these challenges through  advancements in LED technology, signal processing algorithms, and network  protocols will be crucial in realizing the full potential of Li-Fi for audio transmission. 
Looking ahead, further research and development efforts are warranted to enhance  the performance, reliability, and practicality of Li-Fi-based audio transmission  systems. Collaboration between academia, industry, and regulatory bodies will be  instrumental in driving innovation and standardization initiatives. By harnessing the  strengths of Li-Fi technology and leveraging the capabilities of Node MCU  platforms, we can pave the way for a future where high-speed, secure, and efficient  audio communication is seamlessly integrated into our interconnected world. 
Project final Model :https://drive.google.com/file/d/1tXwNQv3ymipJHbLfLg5KsUhokVQb6M9o/view?usp=sharing