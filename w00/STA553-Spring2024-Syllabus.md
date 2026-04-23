---
title: "STA553-Data Visualization"
author: "Instructor: Cheng Peng"
date: "Spring 2024"
output:
  word_document: 
    toc: no
    toc_depth: 4
    fig_caption: yes
    keep_md: yes
  html_document: 
    toc: no
    toc_depth: 4
    fig_width: 6
    fig_height: 4
    fig_caption: yes
    number_sections: yes
    theme: readable
  pdf_document: 
    toc: no
    toc_depth: 4
    fig_caption: yes
    number_sections: yes
    fig_width: 5
    fig_height: 4
---
<style type="text/css">
div#TOC li {
    list-style:none;
    background-image:none;
    background-repeat:none;
    background-position:0;
}
h1.title {
  font-size: 20px;
  color: DarkRed;
  text-align: center;
}
h4.author { /* Header 4 - and the author and data headers use this too  */
    font-size: 18px;
  font-family: "Times New Roman", Times, serif;
  color: DarkRed;
  text-align: center;
}
h4.date { /* Header 4 - and the author and data headers use this too  */
  font-size: 18px;
  font-family: "Times New Roman", Times, serif;
  color: DarkBlue;
  text-align: center;
}
h1 { /* Header 3 - and the author and data headers use this too  */
    font-size: 22px;
    font-family: "Times New Roman", Times, serif;
    color: darkred;
    text-align: center;
}
h2 { /* Header 3 - and the author and data headers use this too  */
    font-size: 18px;
    font-family: "Times New Roman", Times, serif;
    color: navy;
    text-align: left;
}

h3 { /* Header 3 - and the author and data headers use this too  */
    font-size: 15px;
    font-family: "Times New Roman", Times, serif;
    color: navy;
    text-align: left;
}

h4 { /* Header 4 - and the author and data headers use this too  */
    font-size: 18px;
    font-family: "Times New Roman", Times, serif;
    color: darkred;
    text-align: left;
}
</style>


# Contact Information

* Email: cpeng@wcupa.edu
* Office: 107 UNA 25
* Phone: 610-436-2369
* Office Hours: 


|    Day    |      Time      |      Location       |
|:----------|:---------------|:--------------------|
|Tuesday    | 2:00 PM-3:00 PM| R107, UNA25         |
|Wednesday  | 1:30 PM-3:30 PM| R107, UNA25  ZOOM   |
|Thursday   | 2:00 PM-5:00 PM| R107, UNA25         |
|By appointment|             |        |


* **ZOOM Link**: Available on the course web page and D2L as well.

* **Course Web Page**: [https://pengdsci.github.io/STA553VIZ/](https://pengdsci.github.io/STA553VIZ/)

* **Classroom**: 25 University Avenue 120


# Course Description

This course focuses on the principles of data visualization and addresses questions about what, why, and how to visualize. Topics include visualization design elements such as colors, shapes, and movements, etc.; data exploratory visualization; statistical graphics and model visualization; process visualization; dashboard design; and the ethics of data visualization. The course will also introduce some commonly used visualization tools.


# Learning Objectives and Outcomes

## **Learning Outcomes** 

After finishing this course, students should be able to 

* Design and create statistical graphics using the basic principles of visualization.

* Conduct exploratory data analysis using various tools.

* Critically evaluate visualizations and suggest improvements and refinements

* Design and evaluate interactive visualization tools.

* Create web-based interactive visualization.


# Logistics and Required Materials

* **Textbooks (optional):** No required textbook for this class. 
 
  
* **Class Notes:** Class notes will be provided. 

* **Computational Tools:** 

  + Primary Programming languages and Software: R and Tableau Public
  + Platforms: RStudio, Github, Shiny
  + Typesetting: LaTex and Markdown

* **Coverage:** See the list of tentative topics


# Assessments

## Assessment Components

The course grade consists of the following components:

  + Weekly assignments (60%)
  + Class attendance and participation (10%)
  + Project presentation (30%)

## Grade Scales


The final course grade will be calculated based on the above components. A letter grade will be assigned according to the following scale.


|  Grade | 	Quality Points |	Percentage Equivalents |	Interpretation |
|:------ |:--------------|:--------------------|:----------------------|
|A	|4.00	|[93%, 100%]|Superior graduate attainment                    |
|A-	|3.67	|[90%, 93%)	|                                                |
|B+	|3.33	|[86%, 90%)	|Satisfactory graduate attainment                |
|B	|3.00	|[83%, 86%)	|                                                |
|B-	|2.67	|[80%, 83%) |                                             	 |
|C+	|2.33	|[76%, 80%) |	Attainment below graduate expectations         |
|C	|2.00	|[73%, 76%)	|                                                |
|C-	|1.67	|[70%, 73%)	|                                                |
|F	|0	|< 70%	|Failure                                               |

D grades are not used. Refer to the Graduate Catalog for the description of NG (No Grade), W, & other grades.


# Class Policies

## Attendance and Participation

Attendance in the class is mandatory. Actively participating in class discussion is required in this class and is one of the components of the final course grade. 

## Late Homework and Assignments

Late assignments will be accepted. However, all late assignments will be subject to a small penalty deduction.


# Tentative Topics

* Logistics and Technical Tools
* Ethics & Principles of DataViz
* R & Base R Graphics
* Data Management for DataViz
* ggplot Revisited
* Interactive Plot with plotly
* Maps: Visualizing Spatial Information
* Advanced Maps
* Basic Graphics with Tableau
* Interactive Graphics and Tableau Dashboard
* Getting Started With RShiny Apps
* Data Analysis with Shiny Apps
* R Shiny Flexdashboard
* Shinydashboard and Multiple Flexdashboard
 


# University Policies and Resources

## ACADEMIC & PERSONAL INTEGRITY

It is the responsibility of each student to adhere to the university’s standards for academic integrity. Violations of academic integrity include any act that violates the rights of another student in academic work, that involves misrepresentation of your own work, or that disrupts the instruction of the course. Other violations include (but are not limited to): cheating on assignments or examinations; plagiarizing, which means copying any part of another’s work and/or using ideas of another and presenting them as one’s own without giving proper credit to the source; selling, purchasing, or exchanging of term papers; falsifying of information; and using your own work from one class to fulfill the assignment for another class without significant modification. Proof of academic misconduct can result in the automatic failure and removal from this course. For questions regarding Academic Integrity, the No-Grade Policy, Sexual Harassment, or the Student Code of Conduct, students are encouraged to refer to the Department Graduate Handbook, the Graduate Catalog, the Ram’s Eye View, and the University website at www.wcupa.edu. 

## ACCOMMODATIONS FOR STUDENTS WITH DISABILITIES

West Chester University is committed to providing equitable access to the full WCU experience for Golden Rams of all abilities.  Students should contact the Office of Educational Accessibility (OEA) to establish accommodations if they have had accommodations in the past or if they believe they may be eligible for accommodations due to a disability, whether or not it may be readily apparent.  There is no deadline for disclosing to OEA or for requesting to use approved accommodations in a given course. However, accommodations can only be applied to future assignments or exams; that is, they can’t be applied retroactively. Please share your letter from OEA as soon as possible so that we can discuss accommodations.

If you have concerns related to disability discrimination, please contact the university’s ADA Coordinator in the Office of Diversity, Equity, and Inclusion or 610-436-2433.

## EXCUSED ABSENCES POLICY

Students are advised to carefully read and comply with the excused absences policy, including absences for university-sanctioned events, contained in the WCU Graduate Catalog. In particular, please note that the “responsibility for meeting academic requirements rests with the student,” that this policy does not excuse students from completing required academic work, and that professors can require a “fair alternative” to attendance on those days that students must be absent from class in order to participate in a University-Sanctioned Event.

## REPORTING INCIDENTS OF SEXUAL VIOLENCE

West Chester University and its faculty are committed to assuring a safe and productive educational environment for all students. In order to comply with the requirements of Title IX of the Education Amendments of 1972 and the University’s commitment to offering supportive measures in accordance with the new regulations issued under Title IX, the University requires faculty members to report incidents of sexual violence shared by students to the University's Title IX Coordinator. The only exceptions to the faculty member's reporting obligation are when incidents of sexual violence are communicated by a student during a classroom discussion, in a writing assignment for a class, or as part of a University-approved research project. Faculty members are obligated to report sexual violence or any other abuse of a student who was, or is, a child (a person under 18 years of age) when the abuse allegedly occurred to the person designated in the University Protection of Minors Policy. Information regarding the reporting of sexual violence and the resources that are available to victims of sexual violence is set forth at: Diversity, Equity, and Inclusion at WCU website 

## INCLUSIVE LEARNING ENVIRONMENT AND ANTI-RACIST STATEMENT

Diversity, equity, and inclusion are central to West Chester University’s mission as reflected in our Mission Statement, Values Statement, Vision Statement and Strategic Plan: Pathways to Student Success. We disavow racism and all actions that silence, threaten, or degrade historically marginalized groups in the U.S. We acknowledge that all members of this learning community may experience harm stemming from forms of oppression including but not limited to classism, ableism, heterosexism, sexism, Islamophobia, anti-Semitism, and xenophobia, and recognize that these forms of oppression are compounded by racism. 

Our core commitment as an institution of higher education shapes our expectation for behavior within this learning community, which represents diverse individual beliefs, backgrounds, and experiences. Courteous and respectful behavior, interactions, and responses are expected from all members of the University. We must work together to make this a safe and productive learning environment for everyone. Part of this work is recognizing how race and other aspects of who we are shape our beliefs and our experiences as individuals. It is not enough to condemn acts of racism. For real, sustainable change, we must stand together as a diverse coalition against racism and oppression of any form, anywhere, at any time. 

Resources for education and action are available through WCU’s Office for Diversity, Equity, and Inclusion (ODEI), DEI committees within departments or colleges, the student ombudsperson, and centers on campus committed to doing this work (e.g., Dowdy Multicultural Center, Center for Women and Gender Equity, and the Center for Trans and Queer Advocacy). 

Guidance on how to report incidents of discrimination and harassment is available at the University’s Office of Diversity, Equity and Inclusion.

## EMERGENCY PREPAREDNESS

All students are encouraged to sign up for the University’s free WCU ALERT service, which delivers official WCU emergency text messages directly to your cell phone.  For more information, visit WCU Alert. To report an emergency, call the Department of Public Safety at 610-436-3311.

## ELECTRONIC MAIL POLICY

It is expected that faculty, staff, and students activate and maintain regular access to University provided e-mail accounts. Official university communications, including those from your instructor, will be sent through your university e-mail account. You are responsible for accessing that mail to be sure to obtain official University communications. Failure to access will not exempt individuals from the responsibilities associated with this course.
