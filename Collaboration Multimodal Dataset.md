# Collaboration Multimodal Dataset

This is a multimodal dataset collected from collaborative learning activities with a focus on collaborative writing.

## Context

The datasets were collected from classrooms on different subject matters in two Estonian schools. Though there were contextual differences among learning contexts of data collection in terms of teachers, students, physical location, subjects, and concrete learning activities, the learning design shared some common elements. For example, each learning design involved the use of a specific tool -[COTRACK]()- and had a major component of collaborative writing, was 20-40 minutes long, and had a group size between 2-4. Also, the learning designs were mainly of an unscripted nature with minimal teacher instructions.

## Data processing

The datasets used in this dissertation were collected from Estonian schools using COTRACK. From log data, simple quantitative features were extracted, including the number of characters written or deleted by each individual in the group. From audio, speaking time, turn-taking and speech-to-text features were collected based on prior literature. From the video, facial action units, head orientation, and head movement features were extracted. The video recordings were also used for annotation purposes utilising a rating scheme from Rummel et al., (2011). 

## Data Features

Table 1 below provides details on different types of features extracted from multimodal data.

Table 1. Multimodal data and extracted features

|           |                                                              |                                                                                                                                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                         |
| --------- | ------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Data type | Features                                                     | Description                                                                                                                                                                                                                                                                                                                                                    | Related studies                                                                                                                                                                                                                                                                                         |
| Log       | Number of character written<br>Number of characters deleted  | These features mainly captured the amount of text written or deleted by each individual in the group.                                                                                                                                                                                                                                                          | Indicators of individualparticipation which has been found as one of the key quantitative metrics for collaborative learning(Weinberger & Fischer, 2006)                                                                                                                                                |
| Audio     | Speaking time<br>Turn-taking<br>WH-frequency                 | There were two types of features; non-verbal (speaking time, turn-taking) and verbal (word frequency). The first type features measured speaking time and number of turns taken by each individual in the group. The second type focused on frequency-based features such as simply counting the frequency of WH words (e.g., WHY, WHAT) in the spoken speech. | MMLA research studies have found speaking time and turn-taking as indicators of collaboration (Martinez-Maldonado et al., 2013; Ponce-Lopez et al., 2015; Praharaj et al., 2021). Storch (2001) found differences between high and low collaborating groups in terms of their use of personal pronouns. |
| Video     | Facial action units<br>Head orientation<br>Mouth region area | The first feature type consisted of frequency of times  different facial expressions detected (e.g., eyebrow raiser). The second feature measured the differences in head orientation (detected in terms of x,y,z coordinates). The last feature computed the area of mouth which was used as a proxy for speaking.                                            | Previous research found a relationship between facial action units and collaboration behaviour (Sharma et al., 2019;Cai et al., 2020). Head pose contributes 68% to eye-gaze (Stiefelhagen & Zhuet al., 2002). Mouth area region detected lip activity (Siatras et al., 2009).                          |



## Publications

Chejara, P., Prieto, L. P., Rodriguez-Triana, M. J., Kasepalu, R., 
Ruiz-Calleja, A., & Shankar, S. K. (2023, March). How to build more 
generalizable models for collaboration quality? lessons learned from 
exploring multi-context audio-log datasets using multimodal learning 
analytics. In *LAK23: 13th International Learning Analytics and Knowledge Conference* (pp. 111-121). [Link](https://www.researchgate.net/profile/Pankaj-Chejara/publication/366006966_How_to_Build_More_Generalizable_Models_for_Collaboration_Quality_Lessons_Learned_from_Exploring_Multi-Contexts_Audio-Log_Datasets_using_Multimodal_Learning_Analytics/links/638dcce8658cec2104b1f425/How-to-Build-More-Generalizable-Models-for-Collaboration-Quality-Lessons-Learned-from-Exploring-Multi-Contexts-Audio-Log-Datasets-using-Multimodal-Learning-Analytics.pdfhttps://www.researchgate.net/profile/Pankaj-Chejara/publication/366006966_How_to_Build_More_Generalizable_Models_for_Collaboration_Quality_Lessons_Learned_from_Exploring_Multi-Contexts_Audio-Log_Datasets_using_Multimodal_Learning_Analytics/links/638dcce8658cec2104b1f425/How-to-Build-More-Generalizable-Models-for-Collaboration-Quality-Lessons-Learned-from-Exploring-Multi-Contexts-Audio-Log-Datasets-using-Multimodal-Learning-Analytics.pdf)

Chejara, P., Kasepalu, R., Prieto, L. P., Rodríguez‐Triana, M. J., Ruiz 
Calleja, A., & Schneider, B. (2024). How well do collaboration 
quality estimation models generalize across authentic school contexts?. *British Journal of Educational Technology*, *55*(4), 1602-1624. [Link](https://bera-journals.onlinelibrary.wiley.com/doi/abs/10.1111/bjet.13402)

Chejara, P., Prieto, L. P., Dimitriadis, Y., Rodríguez-Triana, M. J., 
Ruiz-Calleja, A., Kasepalu, R., & Shankar, S. K. (2024). The Impact 
of Attribute Noise on the Automated Estimation of Collaboration Quality 
Using Multimodal Learning Analytics in Authentic Classrooms. *Journal of Learning Analytics*. [Link](https://learning-analytics.info/index.php/JLA/article/view/8253)

Chejara, P., Kasepalu, R., Prieto, L., Rodríguez-Triana, M. J., & 
Ruiz-Calleja, A. (2024, March). Bringing collaborative analytics using 
multimodal data to masses: Evaluation and design guidelines for 
developing a MMLA system for research and teaching practices in CSCL. In
 *Proceedings of the 14th Learning Analytics and Knowledge Conference* (pp. 800-806). [Link](https://dl.acm.org/doi/pdf/10.1145/3636555.3636877)



## References

1. Rummel, N., Deiglmayr, A., Spada, H., Kahrimanis, G., & Avouris, N. (2011). Analyzing collaborative interactions across domains and settings: An adaptable rating scheme. In Analyzing interactions in CSCL: Methods, approaches and issues, 367-390.

2. Weinberger, A., & Fischer, F. (2006). A framework to analyze argumentative knowledge construction in computer-supported collaborative learning. Computers & Education, 46(1), 71–95.

3. Martinez-Maldonado, R., Dimitriadis, Y., Martinez-Monés, A., Kay, J., & Yacef, K. (2013). Capturing and analyzing verbal and physical collaborative learning interactions at an enriched interactive tabletop. International Journal of Computer-Supported Collaborative Learning, 8(4), 455–485. [https://doi.org/10.1007/s11412-013-9184-1](https://doi.org/10.1007/s11412-013-9184-1)

4. Ponce-Lopez, V., Escalera, S., & Baro, X. (2013). Multi-modal social signal analysis for predicting agreement in conversation settings. In ICMI'13: Proceedings of the 2013 ACM International Conference on Multimodal Interaction (pp. 495–501). ACM. [https://doi.org/10.1145/2522848.2532594](https://doi.org/10.1145/2522848.2532594)

5. Praharaj, S., Scheffel, M., Drachsler, H., & Specht, M. (2021). Co-located collaboration modelling using multimodal learning analytics - Can we go the whole nine yards ? IEEE Transactions on Learning Technologies, 14(3), 367–385. https://doi.org/10.1109/TLT.2021.3097766

6. Storch, N. (2001). How collaborative is pair work? ESL tertiary students composing in pairs. Language Teaching Research, 5(1), 29–53.

7. Sharma, K., Niforatos, E., Giannakos, M., & Kostakos, V. (2020). Assessing cognitive performance using physiological and facial features. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 4(3), 1-41. https://doi.org/10.1145/3411811

8. Cai, Y., Shimojo, S., & Hayashi, Y. (2020). Observing facial muscles to estimate the learning state during collaborative learning: A focus on the ICAP framework. In ICCE 2020 - 28th International Conference on Computers in Education, Proceedings, 1 (pp. 119–126). Asia-Pacific Society for Computers in Education.

9. Stiefelhagen, R., & Zhu, J. (2002). Head orientation and gaze direction in meetings. CHI 02 Extended Abstracts on Human Factors in Computer Systems CHI 02, 1, 858. https://doi.org/10.1145/506621.506634

10. Siatras, S., Nikolaidis, N., Krinidis, M., & Pitas, I. (2009). Visual lip activity detection and speaker detection using mouth region intensities. IEEE Transactions on Circuits and Systems for Video Technology, 19(1), 133–137. https://doi.org/10.1109/TCSVT.2008.2009262


