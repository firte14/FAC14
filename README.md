# UNIT 15 Web Dev
## Favour Ajiduah

# Content
## 1. Design Documentation
### 1.1 WIREFRAME
To create the website, I had to first define the main requirements to create a mockup wireframe of different ways I would like the Hot Beans to look. Below are some of the wireframe ideas I came up with to aid in creating the website.

Low fidelity Wireframe

![image](https://github.com/user-attachments/assets/15423e49-58c0-45f5-92b8-7e2569100c36)


Wireframe 2(Careers Page)<br/>
![image](https://github.com/user-attachments/assets/6bc075a8-e1ca-4d1b-98fe-6735a166da99)

A search bar would be implemented on the page to aid in quick and easy accessibility of the user to different job roles available








Wireframe 2(Updated)<br/>

![image](https://github.com/user-attachments/assets/101864e3-af4e-4596-aa5c-4ca294a5cd7f)


### 1.2 USER FLOW DIAGRAM
The Data Flow Diagram for the user will show the visual processes of the users data through the website, highlighting the inputs, outputs and routes between them.

DFD Level 0

![image](https://github.com/user-attachments/assets/6a8557b5-775e-49f9-980e-72a53463d650)


DFD Level 1
This shows more detail on what happens when the users interact with the Hot Beans Website
![image](https://github.com/user-attachments/assets/5da9dbe0-999e-494d-8c0a-f2e27a0a2a83)

The users(Aspiring applicants) can:<br/>
. Fill out applications which is saved to the database<br/>
. Search job listings -  this pulls the data from the database<br/>
. Browse courses - pulls from the database<br/>

The Admins can:<br/>
. Update the courses on the page<br/>
. Manage applications<br/>
. Add/remove job listings<br/>

### 1.3 Client REQUIREMENT ANALYSIS
Hot Beans want their website to attract skilled prospective web developers who have finished their training courses and qualifications that are now looking for jobs as web developers, to recruit them. The main goal is to create a compelling careers section that will inform the prospective candidates about the company in general, showcase the available job opportunities and an online application form that is simple to complete. The key requirements and how they will be addressed include:
1. Promotion of the company to prospective web developers: To address this the creation of a well-structured "About Hot Beans" web section that will highlight the mission statement of the company as well as its values, work culture and all-round reputation in the industry. This section will build the company's credibility and excitement for potential candidates.
2. Details on the available Job Roles and requirements: There will be a dedicated "Job Openings" section with the clear job roles needed, descriptions, responsibilities, required qualifications and the benefits. Each job posting will include an easy-to-access "Apply Now" button to encourage applications.
3. An easy-to-use Application Form: Creation of a streamlined online application form that is mobile-friendly and intuitive. It will include different fields for personal details, resume uploads, cover letter, etc. The automated validation will ensure a smooth user experience
4. Profiles showcasing existing trainee web developers: A web section for "Meet Our Team" will be implemented, the section will feature profiles of current web developers who are currently in training at Hot Beans Web. This will provide social proof and motivate potential applicants by showing the real career growth that is possible within the company
5. Links to web development courses: A "Web Development Resources"section that will list links to high-quality online learning platforms like FreeCodeCamp, Udemy, etc. The resources will help aspiring developers continue learning and enhance their qualifications.
6. Furthermore, making use of modern UI/UX design principles, including a clean and responsive layout, consistent typography and an attractive colour scheme will be implemented to make sure the websites design is optimised for readability, accessibility, and ease of navigation.
 
By addressing these requirements, it ensures that the Hot Beans Web Careers section will offer a seamless and informative experience for the potential candidates while helping the company to attract top tier talent.


### 1.4 COLOUR SCHEME AND TYPOGRAPHY

The colour scheme for the development of the website was chosen with the help of the Adobe colour wheel which looked at the logo, highlighting the best choice colours that would go with colours on the company's logo. These colours include: ![image](https://github.com/user-attachments/assets/dbd31f25-0938-4a62-9e43-7bc469fbcbb8)
Which most of the colour themes in the website will be based of off

#### Typography
As for the typography, the decision on the font to be used was put into deep consideration as I looked at providing the website with a font type that will suit it in every aspect. I searched for the best font types to use for a website and chose the one that would best suite the website

####

## 2. Development Justification
### 2.1 Justification of Design Decisions
The current design for the Hot Beans Web website has different foundational elements in place that were put in the direction of meeting the clients requirements

#### Colour Theory
In regards to the colour theory, it was kept in line with the original logo. The maintained green colour scheme represents growth, stability, and nature aligning with the company's "Hot Beans" branding while conveying reliability. The added blue accents introduce trust and professionalism, which is important for recruiting technical talent. The warm neutrals create approachablilty, whilst balancing the technical nature of the content


#### The Golden Ratio Application

The creation of the major layout divisions where done to follow the golden ratio standard:<br/>
.The height to hero sections ratio(1.1.618)<br/>
. The card's dimensions (e.g 300px * 485px)<br/>
.Typography scale (16px, 26px, 42px, 68px)<br/>
.The image-to-text proportions in the team profiles<br/>
This was done to create natural visual harmony across the website, which makes the content more appealing and easier to process<br/>

#### White Space Management
There were strategic white space implementations put in place:
- The increased line height(1.6) improves readabiility

### 2.2 Optimisation

#### Visual Design improvements
##### Colour Scheme
Maintained the current green as the primary colour but added some complementary colours
Created a 60-30-10 ratio: 60% primary green, 30% neutral whites/greys, 10% accent colours
Added a secondary palette of blues and warm neutrals

##### Typography
In regards to the optimised typography:
- Implemented a typographic scale using the golden ratio(1:1.618)
- Created defined fonts for different aspects of text:
  - Primary font: 'Poppins' (sans-serif) for headings
  - Secondary font: 'Open Sans' for body text
- Consistent line-height of 1.6 for optimal readability

##### White Space
- Increased padding and margins using the 8px baseline grid
- Section spacing follows Fibonacci sequence (16px, 24px, 40px, 64px)
- Improved paragraph spacing for better readability

#### Structural Improvements
##### Navigation:
Implemented a mega menu for the careers section
The sticky header for easy access
**Adding a breadcrumb navigation for multi-level pages**
An active state indicator

##### Layout
- Used flexbox for simpler components
- Made a card-based design for the team members and services
- Implemented the CSS Grid for some complex sections


#### Interactive Elements
For the interactive aspects of the website, optimisations took place in different areas to enhance the sites interactivity with the users:
##### Micro-interactions:
Implemented smooth hover transition(0.3 ease)
Button animations(scale, change of colour when hovered around)
Loading animations for the career listings

#### Performance Optimisation
- Critical CSS inlined
- Implemented lazy loading
- Minified CSS and JavaScript

#### Website Areas
The Existing Trainees: Additionally, looking at the area in which the trainees' thoughts or messages was kept in the previous version of the website looked compressed, as the trainees had a lot to say and it was all compiled together with not much space to look appealing. To optimise it, I created a separate page for the trainees to improve the readability of their messages whilst making the overall presentation of the website better, increasing its appealing visuals.<br/>
Search Bar: I also added a search bar to aid in the website's functionality, to enable the user easy access to available job roles<br/>


### 2.3 Demonstration of Individual Responsibility & Creativity
#### Time Management
I implemented a 8-week agile plan to fully create the website to meet the requirements:<br/>
Week 1-2: General Research, Design Documentation and Wireframing<br/>
Week 3-4: Development of the Website implementing the visual designs<br/>
Week 5: Interactive elements development<br/>
Week 6-7: Testing and Optimisations <br/>
Week 8: Evaluation of the designs with the final product review<br/>
Used a Gantt chart to fully manage the allocated time to deliver a great product to the clients. Time was also allocated for any unexpected issues or hindrances that might occur during the development of the project<br/>


### 2.4 Evaluation of Design
The existing Hot Beans Web website has various foundational elements put in place but it lacks overall cohesive design principles and optimisation for it to completely meet the its target audience of prospective developer employees. The following will be an evaluation of the websites current state showing its strengths and weaknesses:

#### Strengths
- The basic structure of the site with all its required sections, which include: the company profile, trainee profiles, job specs, application form, and course links
- It incorporates some visual hierarchy established through the headings
- Uses functional navigation between the websites pages
- Responsive grid layout for services section

#### Weaknesses:
- The inconsistent styling across most of the pages
- Poor colour contrast in some of the areas
- Lack of visual appeal and modern design elements
- No clear information architecture
- The minimal interactivity elements beyond the basic hover states
- No considerations for mobile responsiveness
- Performance issues with image optimization
- Inconsistent typography and spacing
### 2.5 Review of Final Product

## 3. Testing Documentation
### 3.1 Test Plans
The test plan will include the strategy that'll be used for testing the Hot Beans careers website to ensure that it meets the functional, performance and usability requirements. The website is built with the use of HTML, CSS, and Bootstrap for the styling and structure with JavaScript. Various testing methods will be implemented to thoroughly test the website, these will include User Acceptance Testing(UAT), Manual testing and Automated testing procedures.

#### The Testing Approach
The testing will be conducted in different stages<br/>
Unit Testing: This will involve testing the individual components (e.g. navigation, buttons, forms)
separately<br/>
Integration Testing: This will be implemented to validate the interaction between components<br/>
Functional Testing: To ensure all functionalities work as expected(e.g, Job search, Job submission)<br/>
UI/UX Testing: Checking the Bootstrap-based design for its responsiveness and consistency to actions<br/>
Performance Testing: Evaluating the effectiveness of the website's load times and responsiveness<br/>
User Acceptance Testing: Allowing end-users or customers to test the website to make sure it meets their requirements, verifying its usability<br/>

### 3.2 Test Cases and Results
| Test Case ID | Scenario | Description | Expected Outcome | Actual Outcome | Comments |
|----------|----------|----------|----------|----------|----------|
| TC01   | Home page loads correctly   | Open the homepage multiple times on different browsers   | Homepage loads without lags | // | Works as expected |
| TC02   | The Job search functions properly  | Enter a keyword in the search bar, check result | The search bar loads the job searched for and shows a message if the position is not found | Doesn't function properly as nothing loads when a position is input based on | Need to work on implementing the write code to make the search bar active |  
| TC03   | Careers on the header takes user to the Careers Page   | Click the Careers on the header | Takes the user to the home page | // | Works as expected |
| TC04   | About on the header takes user to the About Us Page   | Click About on the header | Takes the user to the About page | // | Works as expected |
| TC05   | Check 'Apply Now' button functionality   | Click 'Apply Now'| Loads the Application form | // | Works as expected|
| TC06   | Test Application form Validation   | Submit the form with missing fields | The form should display messages telling the user to fill in the missing columns | The validation messages shows telling the user to fill out the blanks | 
| TC07   | Test Navigation bar links   | Click eack link within the navbar | Take the user to the desired page |
| TC08   | Test website performance   | Use performance testing aids like Lighthouse to check speed scores
| TC09   | Ensure website responsiveness   | Resize the browser to mobile view
| TC010   |  Validation message appears after form submission  | A message stating the user has successfully submitted the form | A successful submission message pops up after the form is filled | Nothing shows after the form is submitted | The code will be looked at to see any errors made that stops the message from  |
| TC011 |  |  |

### 3.3 BUG TRACKING LOG
|Date | Test ID| Tester | Outcome | Notes |
|-------- |--------- |-------- |--------|-------|
|02/04/2025| OO1 | Favour A.C| Failed |Job search not returning the expected results  |
|02/04/2025| 002 | Favour A.C|||
|03/04/2025| 003 | Favour A.C| Passed | Homepage loads correctly 
|05/04/2025| OO4 | Favour A.C|  |  |
|10/04/2025| OO5 | Favour A.C|  |  |

### 3.4 USABILITY TESTING FEEDBACK
During the usability testing phase, different issues were found and logged which include the job search not loading, a validation message not appearing after the successful submission of the application form etc. These issues were looked at and worked on to enhance the efficiency of the website and ensure a great product is given to clients to maintain/increase the user engagement on the site. As the testing performed was iterative throughout the development to fix any issue before the deployment of the website, with the goal of ensuring a seamless, responsive and functional experience for the users

## 4. Evaluation
### 4.1 FINAL EVALUATION
The Hot Beans Web website was designed to attract new prospective web developers by showcasing the company in it's full glory, with its culture, job opportunities and training resources. This evaluation assesses the overall effectiveness of the final product in meeting the clients requirements, its appeal to the target audience and the websites overall success compared to some alternative solutions. Furthermore, The websites development reflects on my performance, time management, and decision-making throughout the course of the project. 

### 4.2 POTENTIAL FUTURE IMPROVEMENTS
Backend Integration
Dark Mode Implementation
AI Chatbot
### 4.3 FEEDBACK RESPONSES
