# Analysis of student behavior patterns when using large-scale public online learning

**Introduction**

Due to COVID-19 online learning became widespread and relevant since in many cases across the globe the universities are obliged to implement off-site study processes that almost always involve online activities. Even though the pandemic seems to be at the endpoint, many institutions and companies are reluctant to return back to fully offline education. The question how did the online mode influence the behaviour of the students within the educational process is not yet clear, however. In the process of learning they may acquire different patterns of studying that are as well defined by their socio-cultural characteristics. Moreover, during online learning, some students may change their role to ‘teacher’ and vice-versa. 

Therefore, the research gap of our project is as follows: many papers introduced SNA to patterns of e-learning, but they often either focus on emergent roles only with additional variables or use SNA as a complementary method. Our research, instead, will use SNA as the core method in defining the general behavioural structures of the student network and in addressing adapted roles of students during the process of solving mathematical problems. That is our research topic: “Analysis of student behavior patterns when using large-scale public online learning”. 

The main aim of the research is thus to as much as possible identify patterns of student behaviour whilst solving mathematical problems using large-scale public online learning Junyi Academy. Additionally, it is important in reaching the goal to typologize students based on their socio-cultural characteristics and behaviour patterns. Moreover, analyze, in accordance with the identified types of students, their models of interaction within the framework of the "teacher-student" model. 

Necessary research steps in achieving the goal after picking the dataset include analysis of literature which can help us to understand the topic in a more general point of view, which is presented below, data preparation  with descriptive statistics networking and final interpretation of the results achieved with the discussion of further research. 

**Literature review**

To start with, it should be mentioned that the most comprehensive literature on online learning and patterns of education using social network analysis is built around the online peer interaction and consequent emergence of student and teachers roles within the learning process. This may lead to a better understanding of student activity and final learning outcome for each learner. For that SNA is one of the appropriate tools along with content analysis and other methods. Below is the literature review on the most revealing studies. 

The starting one is an article by Xuemei Wu et al. (2022) that analyses the interaction patterns of diverse roles among learners that possess varying levels of co-reflection in the online learning community. For that they used around 11 thousands of posts in social networks that were analysed with the help of both Social Network Analysis and Lag Sequence Analysis. SNA was mostly used to identify various roles of learners during online education. One of their findings states that people with higher levels of collaborative reflection had an advantage over various roles while having a dialogue and they are far more engaged in self-rethinking.  

When relating to online learning, some papers often use the combination of methods or introduce a new one consisting of re-interpretation of a few others as in the previous case. For instance, the research by Dowell & Poquet presents a combination of semantic tool - Group Communication Analysis - and SNA. While focusing on the emergent socio cognitive roles of students within the process of interaction, they add the dimension of semantic and temporal discourses as influencing factors of interaction. Their data consisted of peer communication that occured within the online course at Coursera which is quite similar to our approach to the sources of data. In the end, they categorized learners into five groups: Lurkers, Followers, Socially Detached, Influential Actors and Hyper Posters.

The idea of creating the new method appears as well behind an article by Marcos-García et al. where they introduce a new method DESPRO with implications for future on how to improve teaching. The role of SNA here is in the characterization of the roles of learners or participants in the educational process similarly to previous research papers. In general, much research on online education focuses on production of practical inferences that will be beneficial for the organization of online or hybrid learning. 

The example of that would be an article by Jiun-Yu Wu and Mei-Wen Nian (2021). It is devoted to the dynamics of online studying with the help of QOPS from pedagogy and SNA. They used posts, comments and messages from Facebook groups in order to see how the community of learners changed with the application of QOPS and how the roles of students and teachers altered during the process. Finally, authors also indicated what was the relation between student outcome and relational ties and other SNA measures. In result, the factors that most strongly affected the final result of learning are students' outdegree, degree, and closeness centralities. 

Therefore, one might say that certain works define online education from a more concrete theoretical stance as for example the case in the paper by M. Saqr. He used the perspective of Problem Based Learning as a part of technology-enhanced learning to study the interaction of students and trace their positions within the process of sharing information, participating in the communication. SNA in his research played quite a similar role to previously mentioned works - it helped to show the dynamics of interaction and roles the students take and their influences over studying results.  

If one compares those articles above, it is clear that there is a certain pattern of research and data sources within the field of online learning. Much of the time, researchers use either social networks communication or a particular online course as the data sources. Moreover, generally, they rarely use SNA as a single method on account of research goals and research themes. For linguistic and behavioral studies, scientists prefer to combine a few methods together for more viable results and when they need to go beyond the roles and positions. 

**Research Dataset**

The research dataset that was chosen for this project is from Junyi Academy - school of public online learning. It focuses on math students and solving math problems within the course. The overall number of observations within the dataset is 16,217,311, while the number of observed students equals 75728. With the help of random sampling the dataset was cut down to 9841 of observations and 50 students overall and it constitutes less than  0.0001% of all pupils. 

The dataset includes such information as age of the person, level attained within a particular course, the status of the student according to the output from the exercises done, the amount of classes to which the user belongs. Additionally, it presents the data concerning teachers’ assistance: e.g how many teachers help, collaborative learning, when students exchange their position into teacher’s one. Based on the socio-cultural characteristics of the pupils and their behavioral patterns, it will be possible to typologize different kinds of students and with the help of that trace the interaction of the ‘teacher-student’ model. 

**Results**

For the subsequent analysis of the activity and progress of students, we formed three graphs based on the dataset: the graph of students, the graph of tasks, and the graph of problems.

**_1. Graphs of students that deal with the math problems_**

At the first stage, we combined three datasets into one, cleaned it up, removed unnecessary variables, grouped data by users and calculated additional variables: "total and average number of problems that students encountered", "average time required to solve the problem", "total and average the number of hints used", "the total and average number of solved problems in which there were problems".

<img width="1004" alt="image" src="https://user-images.githubusercontent.com/105935163/175204896-47c61c3a-b2c4-402f-bb64-7d924d944831.png">

We have a fairly small dataset for the students, only 50 lines, because the additional information about tasks and problems made the dataset heavy and difficult to analyze. Therefore, the patterns that we identify on this dataset are preliminary and require additional analysis of more data using a more powerful computer.

In our dataset, only one student is a teacher and has 16 students, two students have their own classes. Thus, students show little activity in relation to switching roles and becoming a teacher. At the same time, the number of teachers and the number of classes are related. A student who has a teacher is more likely to be in the class. The more teachers, the more students are in the number of classes. Based on our data, the social activity of students on the platform is more related to the number of tasks they solved and the problems they faced than to their academic performance.

<img width="911" alt="image" src="https://user-images.githubusercontent.com/105935163/175210283-a38ab6cb-7bb1-4329-8bc9-86f159d503bf.png">

_Now we will turn to the graph фтв start to describe of the core variables. 
| The nodes of the graph are students who are interconnected based on what tasks they solved |_

**User grade** (user_grade): the grade of the student, his level depending on the process of learning. Ranges from 1 to 12. Interestingly enough, the biggest share of the user grade pertains to the value of 4 and accounts for 30%, while 6 and 7 accounts for 18% and 14% correspondingly. Those with 4, 7 and 8 levels (black) are the most clasterized across other values. 6, on the contrary, is less clasterized and more disseminated. If contrasting with the belongness to the class, it is clear that students from a central purple cluster in the left lower side of those with level 4 also are subscribed in majority only to the 1 class, while those with level 7 from right blue cluster are as well partially subscribed to 1 class or 3 classes. 

![image](https://user-images.githubusercontent.com/105935163/175212061-230d7cb9-f2f3-430e-8e77-f5d91dfd0467.png)

**Points** (points): the number of points received by the student, assesses student’s performance. The number of points indeed varies, the overall quantity of the values equals 48, where the strongest student possesses more than 400.000 of points and the lowest number equals to 1050. Moreover, it is quite heterogeneous with little patterns. All students apart from 4 (for 4% percents accordingly), have a diverging number of points. 

![image](https://user-images.githubusercontent.com/105935163/175212265-04305db6-e65c-4259-b4fa-df64b7cad989.png)

**Teachers** (has_teacher_cnt): how many teachers does the student have. According to the graph, the majority of the students have only 1 teacher and this percentage accounts for 58% of all students. There are also 28% of pupils who do not have a teacher at all and 8% of those who have even two teachers. The rest are those with 3 and 5 instructors with 4% and 2% correspondingly. The cluster of those with 1 teacher can be found in the center and on the frontiers of the graph. What can be said from contrasting it with the user grade graph is that students with a level 4 in the lower leftly-center part are those with 1 teacher. Those with a level 7 in the right frontier can have a range from 1 to 3 and 5 teachers. While those at level 6 can have either 1 or no teachers at all, the distribution for that seems to be relatively equal. 

![image](https://user-images.githubusercontent.com/105935163/175212420-95993578-f490-4352-aaf7-6a85b87856af.png)

**Students** (has_student_cnt): how many students does the student (in the role of a teacher) have. There is a clear lack of participation, since the undeniable majority (98%) does have 0 students as a teacher, while only 2% have 16 students. 

![image](https://user-images.githubusercontent.com/105935163/175212765-865647aa-90ed-4f4a-8585-a0b7ace7e820.png)

**Classes** (has_class_cnt): the number of classes created by the student as a teacher. Here there is the same trend as with the amount of students on the behalf of the teacher. Majority of the pupils (96%) have not created any class, while only 2% and 2% created correspondingly 1 and 2 educational classes. _There is as well no clear patterns of connection between the teacher-student role and educational performance, grade or number of classes to which he or she belongs since the numbers are quite small to suppose any strong linkage._

![image](https://user-images.githubusercontent.com/105935163/175213002-490c0627-2d09-437e-843d-7978c2ce802c.png)

**Tasks** (uniq_zd): the number of unique tasks that was ‘opened’ by the student. The most popular and distributed number of tasks entered by the student accounts for 12% and it is a value of 3, while two other biggest share includes 2 and 6 tasks with 8% and 8% correspondingly. Generally, there is a range of 30 values related to the amount of unique tasks ‘opened’ by the pupils and it is hard to contrast the quantity of the tasks to other variables considered above since there is _no clear pattern or connection due to high heterogeneity. _

![image](https://user-images.githubusercontent.com/105935163/175213184-08e06d80-2ca9-4083-908d-8cfe8b2a8fda.png)

**Belongness** (belong_to_class_cnt): the number of classes, student groups to which the student belongs. The biggest share of students pertains to only 1 class or student groups and equals 48%, while 36% do not belong to any class and 10% are subscribed to 2 classes. There is also a smaller share of participants of 3 and 6 classes, 4% and 2% accordingly. 

![image](https://user-images.githubusercontent.com/105935163/175213398-c36499c4-fcba-4afd-8fa5-86f565615b71.png)

_Continuing with statistical indicators_

**Degree of network.** It is the average number of connections the node has to other nodes. In this graph the _average degree equals 5.96 degrees_, therefore almost **6 connections** a node generally has to other nodes. Below can be found a degree distribution that shows the probability of the distribution of this degree across the network. Graph density **equals 0.122**, meaning that the graph _is not really _dense_ since it is closer to 0 than to 1. 

![image](https://user-images.githubusercontent.com/105935163/175214064-2cd5d02f-5915-4473-9f75-d05a3b1905f7.png)

**Network diameter.** The shortest distance between two most distant nodes in this graph is _estimated at value 6, while radius equals 0 and average path length equals approximately 2.65_. Below are presented both betweenness and closeness centrality distributions. 

![image](https://user-images.githubusercontent.com/105935163/175214241-0b439fe1-d448-42c0-aa07-3574919a8915.png)


**Conclusion**

In this project proposal we discussed the research route for the analysis of student behavior during online education in the public courses in the contemporary post-COVID 19 world. This project is supposed to be conducted with the application of Social Network Analysis (SNA). As given by literature review, the usage of SNA within the research on online education and student patterns is very stirring: almost the majority of sources contain SNA as a part of methods. However, the uniqueness of our perspective lies in the fact that we focus only on SNA as a core tool of analysis. We anticipate some weaknesses and strengths of such an approach, for instance, more focus on patterns compared to other works, while providing less flexibility in the interpretation. 

The initial dataset for this research is taken from Junyi Academy and by dint of random sampling it was shortened down to 0.0001% of all cases and prepared for further exploratory and interpretive analysis. It gives information about the personal study characteristics of students such as his or her educational level and data on interaction of students with each other and role they are taking. With that, we would be able to distinguish patterns of student behavior during online education – the question which may facilitate the development of study plans and enhance overall pupils’ performance. 

**Bibliography**
1. Dowell, Nia M.M., and Oleksandra Poquet. «SCIP: Combining Group Communication and Interpersonal Positioning to Identify Emergent Roles in Scaled Digital Environments». Computers in Human Behavior 119 (June 2021): 106709. https://doi.org/10.1016/j.chb.2021.106709.
2. Marcos-García, José-Antonio, Alejandra Martínez-Monés, and Yannis Dimitriadis. «DESPRO: A Method Based on Roles to Provide Collaboration Analysis Support Adapted to the Participants in CSCL Situations». Computers & Education 82 (March 2015): 335–53. https://doi.org/10.1016/j.compedu.2014.10.027.
3. Saqr, Mohammed, and Ahmad Alamro. «The Role of Social Network Analysis as a Learning Analytics Tool in Online Problem Based Learning». BMC Medical Education 19, ed. 1 (December 2019): 160. https://doi.org/10.1186/s12909-019-1599-6.
4. Wu, Jiun-Yu, and Mei-Wen Nian. «The Dynamics of an Online Learning Community in a Hybrid Statistics Classroom over Time: Implications for the Question-Oriented Problem-Solving Course Design with the Social Network Analysis Approach». Computers & Education 166 (June  2021): 104120. https://doi.org/10.1016/j.compedu.2020.104120.
5. Wu, Xuemei, Zhenzhen He, Mingxi Li, Zhongmei Han, and Changqin Huang. «Identifying Learners’ Interaction Patterns in an Online Learning Community». International Journal of Environmental Research and Public Health 19, ed. 4 (16 of February 2022): 2245. https://doi.org/10.3390/ijerph19042245.

___________________________________________________________________________________________________________________________________________________________
**Additional Research: clustering**





