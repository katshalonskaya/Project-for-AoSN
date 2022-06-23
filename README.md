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

**Tasks** (uniq_zd): the number of unique tasks that was ‘opened’ by the student. The most popular and distributed number of tasks entered by the student accounts for 12% and it is a value of 3, while two other biggest share includes 2 and 6 tasks with 8% and 8% correspondingly. Generally, there is a range of 30 values related to the amount of unique tasks ‘opened’ by the pupils and it is hard to contrast the quantity of the tasks to other variables considered above since there is _no clear pattern or connection due to high heterogeneity._

![image](https://user-images.githubusercontent.com/105935163/175213184-08e06d80-2ca9-4083-908d-8cfe8b2a8fda.png)

**Belongness** (belong_to_class_cnt): the number of classes, student groups to which the student belongs. The biggest share of students pertains to only 1 class or student groups and equals 48%, while 36% do not belong to any class and 10% are subscribed to 2 classes. There is also a smaller share of participants of 3 and 6 classes, 4% and 2% accordingly. 

![image](https://user-images.githubusercontent.com/105935163/175213398-c36499c4-fcba-4afd-8fa5-86f565615b71.png)

_Continuing with statistical indicators_

**Degree of network.** It is the average number of connections the node has to other nodes. In this graph the _average degree equals 5.96 degrees_, therefore almost **6 connections** a node generally has to other nodes. Below can be found a degree distribution that shows the probability of the distribution of this degree across the network. Graph density **equals 0.122**, meaning that the graph _is not really dense_ since it is closer to 0 than to 1. 

![image](https://user-images.githubusercontent.com/105935163/175214064-2cd5d02f-5915-4473-9f75-d05a3b1905f7.png)

**Network diameter.** The shortest distance between two most distant nodes in this graph is _estimated at value 6, while radius equals 0 and average path length equals approximately 2.65_. Below are presented both betweenness and closeness centrality distributions. 

![image](https://user-images.githubusercontent.com/105935163/175214241-0b439fe1-d448-42c0-aa07-3574919a8915.png)

![image](https://user-images.githubusercontent.com/105935163/175214577-1f989389-d63f-4812-9b33-e03307143f95.png)

**Modularity.** Since it measures the strength of division of a network into modules, it provides clusters. In the case of this graph there are 4 strong clusters and 3 weak clusters that have no ties at all. There are 0, 3 and 5 cluster values with all 26% of the whole sample, while cluster 2 comprises 16% of the population taken. The modularity coefficient **equals 0.403** which means that _the strength of connections is somewhat lower than medium_ (closer to 0 than to 1). 

![image](https://user-images.githubusercontent.com/105935163/175214888-8c7bdb2b-a4f5-4de0-8694-01229323988a.png)

**Average clustering coefficient.** In this graph the closeness of neighboring nodes is a bit smaller compared to the graph of tasks, but still can be considered as significant. It **equals 0.611** that allows us to assume that there _are medium ties between the nodes_ in the graph. The clustering coefficient distribution can be found below. 

![image](https://user-images.githubusercontent.com/105935163/175215191-5997c2bd-95aa-4873-8889-9dfd84eb9c8e.png)

**_2. Graphs of tasks where problems occurred while solving math problems across 50 students_**

In the second step, we removed other variables from the combined data set, grouped the data by task, and calculated additional variables: “number of problems students encountered within the task”, “number of first-time problem solving”, “number of hints used within the task”. Using th table we have created a grapf. The nodes of the graph are tasks who are interconnected based on what students have solved them.

<img width="914" alt="image" src="https://user-images.githubusercontent.com/105935163/175218012-f5132289-507b-4a96-a0fb-ff960e2e38af.png">

_Starting with the description of the core variables:_

**Correctness from the first trial** (correct_ctn_first): how many times the students managed to resolve the task from the first trial successfully. The range goes from 0 times to 50 with certain lacunas as a maximum point. The most significant weight is pertained to 0 (19.79%), 1 (18.42%) and 2 (14%). Relatively significant also 3, 4, 5 with 9.89, 7.15 and 6.24% correspondingly. They are colored in black, orange and pink. What can be concluded from the network is that the majority of students managed to solve the task from the first attempt only a few times, while almost 20% did not manage to solve any math problem from the first attempt at all. From the graph it appears that the first option of 0 times is the most clasterized option, it can be found in the biggest central cluster and in the one on the right corner side. 

![image](https://user-images.githubusercontent.com/105935163/175218701-970f22d1-464b-47f8-98c9-ea8c280c374f.png)

**Hints** (hint_cnt): how many times the students used hints to resolve the math task. The range of this variable is very large and accounts to 50 dimensions, while 121 is the maximum point. In contrast to the previous variables, there is more distributed range. The biggest significant number of times when students used the hints equals 5 (accounts for 17.66%), while the second and the third place is retained by 10 times and 2 times (7.31% and 6.09%) accordingly. Other meaningful values include 7, 6 and 3 (5.94%, 5.33% and 4.26%). Only 2.13% of students utilized the hints only 1 time, which is somewhat striking, but it is offset by the value of 2. The most clasterised value is the biggest value of 5, it can be seen at frontiers on the left side and on the right clusters (upper and lower). The second value is mostly clustered in the center of the biggest cluster, but certainly smaller. If contrasted with the first graph, _one will see that those who did not manage to solve any math problem from the first attempt generally utilized 5 hints._ 

![image](https://user-images.githubusercontent.com/105935163/175219525-f6a890c3-06d0-4151-af63-9c2522ad8834.png)

**Problems** (prlm_resh): how many problems were encountered by the students while solving the task. The number of values within this variable approximates 59, while the maximum number of problems that were encountered equals 123, however, the students’ percentage is very small. The biggest significance is possessed by 5 problems (11.72%), 6 and 10 accordingly (7.15% and 5.78%). The other 15% of the sample is given to 8, 7 and 11 problems that appeared in students’ perception. Rest of the values presume that other students found quantitatively more problems during the process of solving, while only 1% of them encountered only 1 problem. Therefore, it is clear _that half of pupils met from 5 to 10 problems_, while the rest found the task more problematic (>10 problems). What is more, small orange clusters of students in the down sides of central & frontiers and a bigger right lower cluster are _those who used 5 hints and did not manage to solve the task from the first attempt, thus encountering 5 problems. Also, a portion of those who found 6 problems used 5 hints as well_ (in the upper right cluster and left frontier).

![image](https://user-images.githubusercontent.com/105935163/175219646-23079d2e-d72b-4dde-9133-ed49145969fa.png)

**Learning stage** (learning_stage): what is the level of a student's learning process. Either 0, 1 or 2, which relates to elementary, junior and senior levels of education. Clearly, the biggest portion pertains to the elementary level of learning that accounts for 69.56% out of all students. The junior stage is received by 30.29% of students, while only 0.15% of them attained senior level. The distribution of values definitely corresponds to clusters presented with the help of a modularity function that will be observed below. As can be seen, elementary and junior stages are divided into two clusters with few junior outliers found connected in the lower educational group. What is interesting is that this clusterization does not give an idea that the number of problems, hints and successful first attempts is somewhat connected to the only particular group. Therefore, the patterns found above have no relation to the learning stage of the students, _that is they will generally use 5 or 10 (2) hints, encounter 5 to 10 problems and still solve from 0 to 2 tasks from the first attempt independently of their learning level._  

![image](https://user-images.githubusercontent.com/105935163/175219836-4ec6dd92-86e4-49a7-b937-3d7d4f1ff5e2.png)

**Level of difficulty** (difficulty): how difficult was the task according to the students’ perception. Either 0, 1, 2 or 3, which corresponds to easy, medium, difficult levels and being not sure (3). The biggest share of students are sure that the task is easy (67.58%), while 21% of them consider it difficult. This divergence is particularly surprising since the students’ perception of the math task as having a medium level of difficulty is only 7.76% of the whole sample. Therefore, the task is mostly perceived to be either difficult or easy. Those who were not sure about the task’s complexity accounted for 3.65%. Few insights can be grasped. Firstly, difficult and medium levels are concentrated in the center of the clusters and are highly connected to each other, while those with the perception of tasks being easy are located as well on the frontiers of the graph (left side). The lower right cluster is the _group of students who are less inclined to perceive the task as an easy one, they are mostly not sure or see it as complex and it corresponds to the group of students who encounter ~5 problems, use 5 hints, pertain to junior stage and are not able to deal successfully with the task from the first trial. It is the most diverged cluster out of all._ Those who are located in the left central frontiers and use as well 5 hints found the task easy and pertained to elementary learning level. Moreover, _generally those at junior level of education are less inclined to view the task as of medium difficulty than those at elementary level, while difficulty ratio itself is slightly less at junior level in contrast to elementary (the most lower right cluster). _Given the same junior level of learning for the right cluster and the most lower right cluster, it is striking that difficulty perception is not homogeneous, thus one can only argue for small dependance of it on the learning stage, except for the second mentioned cluster (which is bigger)._ 

![image](https://user-images.githubusercontent.com/105935163/175220195-f2f33257-c150-43a8-8d73-701c06575f0e.png)

_Continuing with statistical indicators:_

**Average degree of the network.** This is the average number of connections the node has to other nodes, while degree distribution is the probability distribution of these degrees over the whole network. The overall number of degrees involves 126 values that are distributed within the network. The biggest frequency of degree pertains to 0 connections and it accounts for 19.03%. Other visible big groups include the degree of 96 connections (5.48%), 37 (3.81%), 46 (3.2%), 35 (3.04%), 123 (3.04%) and other less significant clusters below 3% of the sample. According to the degree distribution report, **the average degree** of our network **equals 92.357**.

![image](https://user-images.githubusercontent.com/105935163/175221110-121208bb-dad9-48cf-887d-323f041f6b90.png)

![image](https://user-images.githubusercontent.com/105935163/175221139-20c99d93-119d-471f-8845-c28b7df09988.png)

**Network diameter.** This is the shortest distance between the two most distant nodes of the network. _The diameter of our network **equals 4**, while the radius and average path length account **for 3 and 2.223 accordingly**._ The distribution of betweenness and closeness centralities can be found below, which is the amount of others’ dependence on a certain node and control and measure of independence from possible control (in case of betweenness). 

![image](https://user-images.githubusercontent.com/105935163/175221189-8f899089-7de5-4cb3-bfa0-378e08cc7b9d.png)

![image](https://user-images.githubusercontent.com/105935163/175221245-da66b46d-06c0-45af-be81-7fdbff206973.png)

**Graph density.** It shows the ratio of existing edges and maximum number of possible edges in the graph. In our graph it **equals 0.173** which means that it **is not really dense**, since minimal density starts from 0 and goes till 1. 

**Modularity.** This measure indicates the strengths of division of a network into modules. In the case of our graph it was _divided into **6 core** clusters_, while the value of modularity is estimated at **0.502**. _This means that the graph has relatively medium strength of community structure – it is not random >0, but not close to 1._ In the graph below the clusters can be identified. Although, three of them are almost equal, the biggest one is on the right side, which as well relates to the junior stage of learning and accounts for 23.9% of all samples, while the most down right cluster that also involves juniors is considered to be second with 23.14%. The central blue left cluster is estimated at 22.98%. While two upper and one most down left clusters are smaller and accordingly equals 13.24%, 10.81% and 5.94%. Generally, in contrast to conventional wisdom, size of the clusters are different from the size’s appearance, thus two most lower clusters seem to be relatively equal, but in fact far divergent. The blue and purple clusters, if considering previous graphs and variables, are the most distinct in the way of tracing the patterns of student behavior, while the others are more heterogeneous across the variables, though some exceptions are present.

![image](https://user-images.githubusercontent.com/105935163/175221286-034bce6f-d5ea-4a08-9f19-e745eb20e9f2.png)

**Average clustering coefficient.** It helps to define how close the neighboring nodes are to being a complete graph or how they try to cluster together. _In our graph the average clustering coefficient equals **0.793**, which allows us to assume that we have relatively strong ties between the nodes._ The clustering coefficient distribution of values can be found below.

![image](https://user-images.githubusercontent.com/105935163/175221333-49d13606-a998-457a-8831-0ee628bf2b78.png)

**ЗДЕСЬ НУЖЕН МИНИ ВЫВОД ПО ГРАФУ И ВСЕМУ**

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

We also did some additional research on data clustering. Using all the variables available to us, we tried to cluster students according to their assessment on the platform. We combined the 12 rating levels into four based on the distribution of the "user_grade" variable. As a result, the significant variables that made it possible to cluster the data as close as possible to the original groups, reflecting the success of students through the "grade", were the variables the complexity of the tasks being solved, the city where the student lives, the number of awards that he received on the platform and the presence of a teacher. It is also worth noting that a fairly good model was obtained by replacing the variable about the presence of a teacher with a class membership variable.

Thus, it was not possible to predict student performance based on the variables associated with the change in the role of the teacher-student. At the same time, the model included or could include variables related to the activity of students as students. However, the main role was still played by the variable difficulty of the task and the number of awards received on the online platform.

**_Cluster Graph_**

![image](https://user-images.githubusercontent.com/105935163/175223522-625d2991-dd04-491f-886e-3ce5f3073ae4.png)

_**Graph of level of grades**_

![image](https://user-images.githubusercontent.com/105935163/175223675-f7465a93-784d-41fc-ab7e-9c2c1dc1ccdd.png)


