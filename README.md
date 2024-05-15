# Parcoursup

<a href="https://ibb.co/g6T6Qpm"><img src="https://upload.wikimedia.org/wikipedia/fr/thumb/d/dc/Logo_parcoursup.svg/2560px-Logo_parcoursup.svg.png" alt="Parcoursup" border="0"></a>

<h2>Introduction</h2>
<p>	<i>Parcoursup</i>. For French students and high schoolers, this name can bring up stress and bad memories. <a href="https://www.parcoursup.gouv.fr/">Parcoursup</a> is a platform designed by the French Ministry of Education and the French Ministry of Higher Education, Research and Innovation to help solve the stable marriage problem between high school students and universities. It was launched in 2018, replacing the <i>APB</i> portal (Admission Post-Bac), after a CNIL (Commission Nationale de l’Informatique et des Libertés) formal notice. Parcoursup functions with the help of an algorithm, which is updated each year. The platform has received numerous criticisms from the press, teachers and families, questioning its transparency or the social inequalities it perpetuates… Yet, among these condemnations, which ones are actually true, and which ones result from the algorithm itself and its parameters?
We have chosen to research this issue, driven by the following question: <b>To what extent can we argue that there is a lack of consistency between the algorithm of Parcoursup and its public representation?</b> By public representation, we understand the elements in the official documentation and discourse of the French state around Parcoursup and its goals.
</p>

<h2>Methodology</h2>
<p>	To tackle this problem, we primarily considered diving into the code of the Parcoursup algorithm made available by the French Government. However, we soon found out that the code was not going to be extremely useful for our research, as it does not offer more elements than what is already documented in official governmental communication about Parcousup.
<p>Hence, we relied on other sources to build our research. First, we dived into academic articles that had been produced about Parcousup by researchers. We completed this analysis with an overview of press articles published about Parcoursup, in order to find out about public opinion around the algorithm and the platform.
<p>Finally, we had the chance to conduct interviews with <a href="https://nmaudet.gitlab.io/">Nicolas Maudet</a> and <a href="https://www.linkedin.com/in/khaled-belahcene-7047a133/?originalSubdomain=fr">Khaled Belahcene</a>, experts in algorithms. Nicolas Maudet is an Artificial Intelligence (AI) researcher and Information Technology (IT) teacher at Jussieu University. Khaled Belahcene is a professor at the engineering university, CentraleSupélec.
This research methodology allowed us to analyse the official government discourse about Parcoursup with governmental documents, as well as public opinion, seeing what was said about Parcoursup in the press. On top of this, the academic research and interviews with experts gave us a more critical analysis of these distinct stances.
</p>

<h2>Presentation of the Parcoursup algorithm</h2>

<p><strong>Stable marriage algorithm</strong> </p>
Parcoursup is based on the algorithm known as “stable marriage” developed by David Gale and Lloyd Shapley in 1962. It was initially designed to answer the following question: given N men and N women, is it possible to form stable couples, i.e. couples in which no man or woman would prefer each other to their respective spouses? Gale and Shapley have shown that if men and women have complete preferences (i.e. a ranking) for individuals of the individuals of the other sex, then it's always possible to form stable couples. In the algorithm they propose men “propose” and women “dispose”. However, the pairing is not necessarily optimal for those who “dispose” (the women in this example) (Lenoir et al, 2019).
The Parcoursup platform enables students to apply to more than 23,000 higher education programs.
Within the framework of a single dossier, students can use a single application to (République Française, 2024):
consult the full range of post-baccalaureate programs on offer;
find the information such as: course status, tuition fees, criteria for analyzing applications, demand levels and success/employment rates;
assemble the application, which will then be sent to the programs selected.
freely formulate your wishes for the programs that interest them;
receive admission offers and choose the school. </p>

<a href="https://ibb.co/yS3BrtK"><img src="https://i.ibb.co/4dQgHzC/Design-sans-titre.png" alt="Design-sans-titre" border="0"></a>

<p><strong>Innovations compared to APB</strong> </p>
Compared to APB, Parcoursup introduces four major innovations (Lenoir et al, 2019):
 <li>Abandonment of the random selection system for non-selective courses in short supply, which had been perceived as arbitrary.
 <li>Abandonment of the ranking of wishes by applicants. This choice was motivated by the desire to enable applicants to gradually mature their choices, and to remove the inhibitions potentially induced by prior ranking of wishes.
 <li>Increased role given to the “responsables de formation” at both school and university levels. There is a phase in which applications are examined by the CEVs, including for non-selective courses. This human intervention, required by the CNIL in its formal notice on APB in 2017, results in a pedagogical ranking based on their dossiers.
 <li>Inclusion of quotas for scholarship holders and non-residents set by rectors. The introduction of grant-holder quotas was motivated by the quest for greater social equity.
<p>However, this priority corresponds to a legal obligation in terms of opportunities (proposals made to applicants), not in terms of results (number of scholarship students finally assigned and enrolled in courses) and does not concern unsaturated courses. The criteria on which the rectors decide on the scholarship rate are not very transparent (Frouillou, Pin & Van Zanten, 2020).</p>

<p>Once applications and wishes have been submitted by students, universities give a ranking of the students that expressed interest in them. For each program, Parcoursup sends daily admission proposals to some of the applicants who have confirmed a wish for this program and who have been selected by the wish review committee at the end of its review of applications. Admission proposals are sent in the order of call, calculated by the Parcoursup algorithm. The order of call takes into account, based on the pedagogical ranking, the legal requirements, which are materialized in the quotas set by rectors (Ministère de l’Enseignement Supérieur et de la recherche, 2018).</p>

<p><strong>Changes</strong> </p>
The algortihm was first deployed in 2018. In 2019, after the first experience, some changes were implemented (Lenoir et al, 2020):
 <li>The integration of new programs into Parcoursup and the systematic requirement of a leaving certificate for applications outside Parcoursup.
 <li>The introduction of stages. Three stages have been introduced: on June 25, July 6 and July 17, at the close of the main phase. Applicants were then asked to confirm their wishes within three days, otherwise they would be deleted by the platform.  This measure aims to avoid dormant wishes.
 <li>Better information for candidates on their position in the waiting lists by displaying the rank in the waiting lists of the students admitted last year.
     
<p>For 2021, there were some changes regarding CEVs. Until now, the CEVs (Commissions d'Examen des Vœux de Parcoursup) only had the marks from the French bac and the school reports transcribed in the Avenir form. From now on, the CEVs will have access to almost three-quarters of the bac grades to establish their rankings. The CEVs will have around 30% of the baccalauréat grade at their disposal. For the 60% made up of national exams, the CEVs will have the marks for the French bac (10%) and the two speciality exams (16% each) (Lenoir et al, 2022).</p>

<p>In 2023, the Baccalauréat and Parcoursup calendars converged to integrate high school students' marks from the final exams for speciality courses into the Parcoursup file. This reinforces the weight of the Baccalauréat final exams for access to higher education (Ministere de l’Éducation Nationale et de la Jeunesse, 2023).
However, for 2024, the opposite decision was taken. The speciality written tests will take place from June 19 to 21. This decision is in response to criticism from lycée teachers and headteachers concerning the the high level of absenteeism in the 3rd trimester, as students considered the year to be over, and the impossibility of “finishing the program”. The files examined by the (CEV) in 2024 will therefore only include marks for continuous assessment grades. This seemingly insoluble contradiction is based on many implicit assumptions that have not been sufficiently explained and discussed (Cuesta, C. et al., 2024).</p>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h2>Positive Aspects in the Implementation of Parcoursup’s Algorithm </h2>

<p><strong>Transparency of Parameters</strong></p>
<p>
    Parcoursup offers a heightened transparency in terms of the parameters taken into consideration when evaluating applications. These parameters are the grades since the end of the “terminale”, the “Avenir” form filled by professors, the “activities and interests” section, a motivational letter, optional courses taken during high school, and any complementary file.
</p>
<p>
    While Parcoursup’s algorithm ensures transparency in the processing of applications, the only opacities of the system do not come from it, but rather from some academic institutions that do not clearly state their precise selection criteria. The algorithm itself is designed to consider applicants' program preferences, rank them accordingly, and present the applications to schools for further examination.
</p>
<p>
    Therefore, Parcoursup's algorithm facilitates a fair and transparent process by objectively ranking applicants based on all the available data, which is their qualifications and preferences, thereby enhancing the overall transparency and efficiency of the admissions process.
</p>

<p><strong>More Space Offered to Local Students and Scholarship Holders</strong></p>
<p>
    The Parcoursup system is bound to respect specific admission rates for scholarship holders and local residents. Hence, the admission ranking is obtained from the pedagogical ranking, made with the previously detailed parameters, and then adjusted to lift scholarship holders and residents to guarantee that the admission rates are respected.
</p>
<p>
    In practice, when reviewing the list of candidates, Parcoursup has shown that it may decide to move some scholarship holders up the list and some non-resident applicants down. Specifically, we have discovered that Parcoursup gives priority to scholarship-holding resident candidates, then to non-scholarship-holding resident candidates, then to scholarship-holding non-resident candidates, and finally to non-scholarship-holding non-resident candidates.
</p>
<p>
    Therefore, this system makes sure that local students and scholarship holders, who [scholarship holders] have gained that status thanks to their specific socio-economic background, are prioritized and given more space. This adjustment reveals to be a balancing force, ensuring that social equity and equality of opportunity are guaranteed, at least in theory.
</p>

<p><strong>A Supposedly Fair Algorithm Regarding High School Reputation and Students' Respective Situations</strong></p>
<p>
    Following a Jacobin political rhetoric, the Parcoursup algorithm considers all grades on the French territory to be equivalent. Legally, the algorithm cannot be programmed depending on each high school, whether they are high or low ranked, public or private. All students are hence supposedly considered equally by the algorithm, no matter the high school they attended. This vision also has its limits when considered under an equity principle, potentially disadvantaging the students coming from “Réseaux d’Education Prioritaire”.
</p>
<p>
    The Parcousup system does not take into consideration missing grades, considering that every student must be ranked. This principle puts on an equal setting for all students, no matter how many absences of attendance they might have, which is considerate towards students who might have complicated personal situations and lives. Yet, this also has its limits.
</p>

<p><strong>Reduced Administrative Burden</strong></p>
<p>
    The Parcoursup algorithm is one component of a larger strategy by the French state to digitalize and simplify bureaucratic processes. This change of paradigm implies that the State and the civil service must take up digital technology and, a priori, succeed in offering users a better quality of service while achieving cost savings, thanks to the automation of procedures.
</p>
<p>
    Parcoursup represents a centralized system that not only simplifies the application process but also allows for the automation of tasks such as admission communications or waitlist management, as well as providing a centralized database of information that facilitates data management and analysis. This automation saves time, resources while minimizing the risk of errors and inconsistencies in the admission process.
</p>
<p>
    The algorithm’s official designation is “Outil d’Aide à la Décision” (OAD), which can be translated as Tool to Aid Decision. It is especially useful for schools and universities which do not have the physical, financial and time resources to handle the very numerous applications of high school candidates who want to access higher education.
</p>
<p>
    To parameter the OAD, no high statistical skill is needed in IT. Each university wanting to implement the OAD in their decision process can access seminars on the Parcoursup platform, which also provides documentation to help with the algorithm implementation.
</p>
<p>
    The change brought by Parcoursup significantly simplifies a plethora of processes and procedures, hence reducing the bureaucratic burden on administrations related to the education ministry and academic institutions. Therefore, we should be positive to say that Parcoursup saves French society and State a significant, yet not quantified, amount of economic resources.
</p>
</body>

<h2>Limitations of Parcoursup’s algorithm</h2>

<p><strong>Transparency Limitations</strong></p>
<p>
 
Transparency is often mentioned as the real added value of Parcoursup’s algorithm. However, it seems that it is still not completely achieved. According to the engineers we consulted and (<a href="https://academic.oup.com/book/40047/chapter-abstract/340575385?redirectedFrom=fulltext">further readings</a>), in computer science theory, there is a clear distinction to be made between “the formulation of the problem”, “the algorithm” and “its implementation process”. In the case of Parcoursup, the algorithm and its implementation process are indeed very well documented since the code and some additional information are open-source and freely available online. However, when it comes to the formulation of the problem, there is more blur regarding the answer, and we cannot really find why exactly this specific algorithm has been implemented. As stated by one of the interviewees, “Nobody ever questions the problem we are trying to solve with Parcoursup, it is not documented {…}. Why this specific matching model has been chosen among so many other?”. Indeed, the stable marriage problem as theorized by Gale and Shapley has many possibilities and the choice of this specific one has never been justified. <p>
 
<p><strong> Towards the renewal of some inequalities</strong></p>
<p>
 
While the fairness and equitable aspects of Parcoursup are also often praised by the French Government, Parcoursup’s algorithm seems in practice to contribute to the renewal of some inequalities. First, there is no ranking of their preferences for the high-schoolers and students, which means that for many of them it takes longer for the algorithm to find the perfect match. Sometimes, it can take until the very end of the summer. However, not all students can wait until the last minute to join a higher education program. Indeed, it often implies that the student must move to another city and/or make organizational sacrifices that some students can’t afford. Therefore, only the high-schoolers and students who have the financial means necessary would be able to join the program which contributes to the exacerbation of existing socio-economic inequalities. 

The quota for each program is also limited in practice. In fact, the choice of determining the quota of scholarship-holders for each program lies with the rector of each academy and is not uniform at national level. The only rule they all have to respect is the minimum threshold of 5%. As a result, some rectors have repeatedly chosen to demand a very low rate. Unsurprisingly, this is the case for the Paris académie, which is home to the most prestigious universities and schools, a point that has been emphasized on numerous occasions. Consequently, the proportion of scholarship holders has indeed risen among those admitted through Parcoursup since the introduction of quotas, but their rate has tended to stagnate, or even decline in selective programs.
 
<p>

<p><strong> An administrative burden displaced rather than reduced</strong></p>
<p>
 
Regarding the administrative burden, it seems that it has been displaced rather than reduced. Indeed, through the platform, students can formulate up to 10 wishes with potential sub-wishes and 10 additional wishes for apprenticeship, while at the end they select only one or none of all these programs. Since the students do not rank their choices, the complexity to go through every single application they receive remains to the higher-education institutions, which can easily become a real burden, complicating the task for the humans behind it and encouraging selection by unsupervised algorithms, which can be dangerous in terms of mistakes and biases. As mentioned by one of the engineers interviewed, “Universities and schools have to deal with exponentially more applications than those who will be selected at the end. For a university such as La Sorbonne which selects 6000 students every year, it would mean that they probably have to deal each year with at least 60 000 applications through the platform.” <p>


<h2>How could Parcoursup be used differently, to achieve more equity?</h2>

In the end, Parcousup is only an algorithm, with specific chosen parameters driving certain outcomes. Yet, an algorithm only is an instrumentalisation of a political public action, through technical choices (<a href="https://laviedesidees.fr/Parcoursup-ou-la-selection-par-les-algorithmes">Tiberj, 2021</a>). Parcousup solely reflects the choice of the decision-makers behind its conception; yet, there could be other ways to operate this algorithm, producing different results of higher education admission for students.

This reflection drives the research of sociologist Vincent Tiberj. When French university Sciences Po Bordeaux asked him to parameter an alternative algorithm, V. Tiberj chose to rely on an algorithm which would use the grade average gap (“écarts à la moyenne”) between students, over the current raw grades (“notes brutes”) parameters used by the Parcoursup OAD. Sciences Po Bordeaux uses the Parcousup algorithm to pre-select the candidates deemed “admissible”. Only after this step would there be a qualitative reading of the pre-selected students’ application (motivation letter, extra-academic activities).

Comparing the results of the two different algorithms, V. Tiberj concluded that his “homemade” algorithm achieved better social democratisation, as well as territorial diversity, an objective expressed by Sciences Po Bordeaux. Indeed, the university historically admits a majority of students coming from the area surrounding it, as they are more driven to apply to a university located near their residence and are proportionally more important than students from other areas of France.

Hence, a simple modification in the algorithm parameters, ranking students on one kind of qualitative data over another can significantly change the outcome of the admission. This contributes to the idea that the Parcoursup algorithm is not in itself discriminatory, but it is the way it is used and the goals driving its conception that might be.

<h2>Conclusive thoughts</h2>

To sum up, there seems to be a certain gap between the official discourse of the government around Parcousup and its real outcomes. Indeed, when looking at official documentation, the launch of Parcousup by the French government demonstrates a will from the latter to move away from the previous arbitrary nature of APB and to come up with a more democratic and transparent system and algorithm. Moreover, Parcoursup is advertised as a more humanized system, less dependent on the algorithm while still lighting the administrative burden of universities. Finally, by setting up scholarship holders quotas, the French government tries to establish a message and goal of greater social equity.
However, when we look at the ways the algorithm is parameterized and used by the platform, it seems to contradict this official stance from the government. First, the objective of social equity stated is limited, as it ultimately depends on each rectorate and does not solve self-censorship issues. Furthermore, the displaced problem of administrative burden ends up putting even more importance on the grades, the qualitative analysis of applications being disregarded in the process. Finally, despite the claimed improved transparency from the APB algorithm, there is no clear clarity about the choices behind the Parcoursup algorithm.

In the end, we can conclude that the Parcoursup algorithm is not flawed in itself. However, the way it is parametered to serve a political purpose which is not clearly mentioned contradicts the official discourse of the government.
It is also interesting to see that there are other ways to set the algorithm to achieve more social equity, as seen in the work of V. Tiberj who set a new algorithm for the University of Sciences Po Bordeaux (<a href="https://laviedesidees.fr/Parcoursup-ou-la-selection-par-les-algorithmes">Tiberj, 2021</a>). If the French government really wanted to achieve this end, there would be ways to do it with the existing algorithm. This really puts into perspective the instrumentalisation and the political choices behind the Parcousup algorithm.


