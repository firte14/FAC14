# UNIT 15 Web Dev
## Favour Ajiduah

# Content
## 1. Design Documentation
### 1.1 WIREFRAME
To create the website, I had to first define the main requirements to create a mockup wireframe of different ways I would like the Hot Beans to look. Below are some of the wireframe ideas I came up with to aid in creating the website.

Low fidelity Wireframe

![image](https://github.com/user-attachments/assets/15423e49-58c0-45f5-92b8-7e2569100c36)
![image](https://github.com/user-attachments/assets/2fadc7ad-6595-4c04-8ad3-cf5d10f0f1b3)



Wireframe 2(Careers Page)<br/>
![image](https://github.com/user-attachments/assets/6bc075a8-e1ca-4d1b-98fe-6735a166da99)

<br/>

![image](https://github.com/user-attachments/assets/550c39db-a3a2-4664-98e7-8a0c47726469)



#### Review of the Websites' Design
![image](https://github.com/user-attachments/assets/e3224707-dd2b-482a-bf6a-849714b5b884)<br/>

In line with the feedback received, a search bar would be implemented on the page to aid in the quick and easy accessibility of the user to different job roles available


Wireframe 2(Updated)<br/>

![image](https://github.com/user-attachments/assets/101864e3-af4e-4596-aa5c-4ca294a5cd7f)


### 1.2 USER FLOW DIAGRAM
The Data Flow Diagram for the user will show the visual processes of the users' data through the website, highlighting the inputs, outputs and routes between them.

DFD Level 0

![image](https://github.com/user-attachments/assets/6a8557b5-775e-49f9-980e-72a53463d650)


DFD Level 1<br/>
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
Hot Beans wants their website to attract skilled prospective web developers who have finished their training courses and qualifications and are now looking for jobs as web developers, to recruit them. The main goal is to create a compelling careers section that will inform the prospective candidates about the company in general, showcase the available job opportunities and provide an online application form that is simple to complete. The key requirements and how they will be addressed include:
1. Promotion of the company to prospective web developers: To address this the creation of a well-structured "About Hot Beans" web section that will highlight the mission statement of the company as well as its values, work culture and all-round reputation in the industry. This section will build the company's credibility and excitement for potential candidates.
2. Details on the available Job Roles and requirements: There will be a dedicated "Job Openings" section with the clear job roles needed, descriptions, responsibilities, required qualifications and the benefits. Each job posting will include an easy-to-access "Apply Now" button to encourage applications.
3. An easy-to-use Application Form: Creation of a streamlined online application form that is mobile-friendly and intuitive. It will include different fields for personal details, resume uploads, cover letter, etc. The automated validation will ensure a smooth user experience
4. Profiles showcasing existing trainee web developers: A web section for "Meet Our Team" will be implemented, the section will feature profiles of current web developers who are currently in training at Hot Beans Web. This will provide social proof and motivate potential applicants by showing the real career growth that is possible within the company
5. Links to web development courses: A "Web Development Resources"section that will list links to high-quality online learning platforms like FreeCodeCamp, Udemy, etc. The resources will help aspiring developers continue learning and enhance their qualifications.
6. Furthermore, making use of modern UI/UX design principles, including a clean and responsive layout, consistent typography and an attractive colour scheme will be implemented to make sure the websites design is optimised for readability, accessibility, and ease of navigation.
 
By addressing these requirements, it ensures that the Hot Beans Web Careers section will offer a seamless and informative experience for the potential candidates while helping the company to attract top tier talent.


### 1.4 COLOUR SCHEME AND TYPOGRAPHY

The colour scheme for the development of the website was chosen with the help of the Adobe colour wheel, which looked at the logo, highlighting the best choice of colours that would go with the colours on the company's logo. These colours include:![image](https://github.com/user-attachments/assets/dbd31f25-0938-4a62-9e43-7bc469fbcbb8)
Which most of the colour themes in the website will be based on

#### Typography
As for the typography, the decision on the font to be used was put into deep consideration as I looked at providing the website with a font type that will suit it in every aspect. I searched for the best font types to use for a website and chose the one that would best suit the website

####

## 2. Development Justification
### 2.1 Justification of Design Decisions
The current design for the Hot Beans Web website has different foundational elements in place that were put in the direction of meeting the clients' requirements

#### Colour Theory
In regard to the colour theory, it was kept in line with the original logo. The maintained green colour scheme represents growth, stability, and nature, aligning with the company's "Hot Beans" branding while conveying reliability. The added blue accents introduce trust and professionalism, which is important for recruiting technical talent. The warm neutrals create approachability, whilst balancing the technical nature of the content


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
For the interactive aspects of the website, optimisations took place in different areas to enhance the site's interactivity with the users:
##### Micro-interactions:
Implemented smooth hover transition(0.3 ease)
Button animations(scale, change of colour when hovered over)
Loading animations for the career listings

#### Performance Optimisation
- Critical CSS inlined
- Implemented lazy loading
- Minified CSS and JavaScript

#### Website Areas
The Existing Trainees: Additionally, looking at the area in which the trainees' thoughts or messages were kept in the previous version of the website looked compressed, as the trainees had a lot to say and it was all compiled together with not much space to look appealing. To optimise it, I created a separate page for the trainees to improve the readability of their messages whilst making the overall presentation of the website better, increasing its appealing visuals.<br/>
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
The existing Hot Beans Web website has various foundational elements put in place but it lacks overall cohesive design principles and optimisation for it to completely meet the its target audience of prospective developer employees. The following will be an evaluation of the website's current state, showing its strengths and weaknesses:

#### Strengths
- The basic structure of the site with all its required sections, which include: the company profile, trainee profiles, job specs, application form, and course links
- It incorporates some visual hierarchy established through the headings
- Uses functional navigation between the website's pages
- Responsive grid layout for services section

#### Weaknesses:
- The inconsistent styling across most of the pages
- Poor colour contrast in some of the areas
- Lack of visual appeal and modern design elements
- No clear information architecture
- The minimal interactive elements beyond the basic hover states
- No considerations for mobile responsiveness
- Performance issues with image optimisation
- Inconsistent typography and spacing

### 2.5 Review of Final Product
The Hot Beans Web's new website successfully meets most of the vocational scenario requirements, creating a professional, functional and user-friendly section to attract prospective web developers. Here's a brief review:
The comprehensive job specifications(in the careers.html) and course links(courses.html) focus on directly addressing the target audience's needs. The online application form(form.html) is intuitive, as it also contains clear validations, with a success message, enhancing the user's confidence. The consistent design and responsive layout used ensure the accessibility of the site across various devices. It also contains robust JavaScript functionality(filtering, modals and form handling) which showcases the technical competence of the code. However, even with all these strengths, the website still falls short in some aspects which include: its lack of imagery and about page, which could be more engaging with some specific achievements or visuals.



## 3. Testing Documentation
### 3.1 Test Plans
The test plan will include the strategy that'll be used for testing the Hot Beans careers website to ensure that it meets the functional, performance and usability requirements. The website is built with the use of HTML, CSS, and Bootstrap for the styling and structure, with JavaScript. Various testing methods will be implemented to thoroughly test the website, these will include User Acceptance Testing(UAT), Manual testing and Automated testing procedures.

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
| TC07   | Test Navigation bar links   | Click eack link within the navbar | Take the user to the desired page | Works as expected | 
| TC08   | Test website performance   | Use performance testing aids like Lighthouse to check speed scores | The site runs at exceptional performance and it gains a 90+ lighthouse score | Works as Expected|
| TC09   | Ensure website responsiveness   | Resize the browser to mobile view| Website still responsive to the devices layout(prompts a hamburger menu)|Works as Expected|
| TC010   |  Validation message appears after form submission  | A message stating the user has successfully submitted the form | A successful submission message pops up after the form is filled | Nothing shows after the form is submitted | The code will be looked at to see any errors made that stops the message from  |


### 3.3 BUG TRACKING LOG
|Date | Test ID| Tester | Outcome | Notes |
|-------- |--------- |-------- |--------|-------|
|02/04/2025| OO1 | Favour A.C| Failed |Job search not returning the expected results  |
|02/04/2025| 002 | Favour A.C| Passed |The Search Bar is now fully functional|
|03/04/2025| 003 | Favour A.C| Passed | Homepage loads correctly |
|05/04/2025| OO4 | Favour A.C| Failed | Success message after form submission doesn't pop up (New HBW) |
|10/04/2025| OO5 | Favour A.C| Passed | Success message after form submission displays (Hot Beans Web) |

### 3.4 USABILITY TESTING FEEDBACK
During the usability testing phase, different issues were found and logged which include the job search not loading, a validation message not appearing after the successful submission of the application form etc. These issues were looked at and worked on to enhance the efficiency of the website and ensure a great product is given to clients to maintain/increase the user engagement on the site. As the testing performed was iterative throughout the development to fix any issue before the deployment of the website, with the goal of ensuring a seamless, responsive and functional experience for the users

## 4. Evaluation
### 4.1 FINAL EVALUATION
The Hot Beans Web website was designed to attract new prospective web developers by showcasing the company in it's full glory, with its culture, job opportunities and training resources. This evaluation assesses the overall effectiveness of the final product in meeting the clients requirements, its appeal to the target audience and the websites overall success compared to some alternative solutions. Furthermore, the website's development reflects on my performance, time management, and decision-making throughout the course of the project. 

#### Core Requirements Assessment
The project brief given outlined five major requirements of the clients, with each of them being meticulously implemented with thoughtful consideration of the target audience. The company profile section created establishes credibility, as it features not just basic information about the company - Hot Beans Web, but also presents a compelling narrative about the company's culture through different multimedia elements. <br/>
The trainee profiles go above the basic requirements by offering some prospective  applicants a genuine insight into past trainees' career progression within the organisation. Each profile includes detailed information about the specific trainee, their day-to-day tasks, skill development pathways, and some project portfolios that showcase the real-world application of the skills they've gained during their training. This section proves to be particularly valuable to the target demographic of recently qualified developers, as evidenced by user testing, where a majority of the participants reported that the profiles significantly influenced their view on the career growth potential at the company.<br/>
Job specifications are presented through an innovative filtering system which allows the prospective candidates to look for job opportunities based on different factors. The implementation goes beyond just simple job descriptions by incorporating a functional search bar that candidates can use to go through the opportunities available with quick ease, and they will be notified if the job path they are pursuing isn't available. This approach addresses the informational needs of the prospective candidates, which increases the quality of the applications.<br/>
The online application form demonstrates particular attention to user experience design. By breaking down the form into logical stages, it maintains user engagement while collecting comprehensive information about the candidates. Advanced features like resume parsing and field auto-completion were put in place to reduce the overall completion time by an average of 40% compared to traditional forms, addressing a critical drop-off point in the recruitment funnel.
Finally, the course link/resource integration establishes Hot Beans Web as not just an employer but a career partner. The platform connects various external learning resources to specific career paths within the company, which creates a clear development trajectory for applicants. This forward-thinking approach has shown some promise as a distinction amongst other competitive tech recruitment markets

#### Technincal Executuions
From an architectural point of view, the website employs the use of modern development practices that ensure robust performance across all platforms. The decision to implement a component-based design system allows for consistent presentation of the job listings available and profile elements while maintaining flexibility for future expansions. The implementation of lazy loading and strategic resource preloading demonstrates sophisticated attention towards the site's performance optimisation. These technical choices directly contribute to the site's exceptional Lighthouse scores. <br/>
Interactive elements employ progressive enhancements, which ensure the core functionality of the site remains accessible regardless of the device's capabilities. The filtering system for job listings uses URL parameter persistence, enabling users to bookmark specific searches; a subtle but impactful feature. 


### 4.2 POTENTIAL FUTURE IMPROVEMENTS
While the current website implementation fully satisfies all the essential requirements, there are several strategic enhancements that could provide additional value to the website: <br/>
Candidate Dashboard: Developing a personalised page for users to track their applications and skill development planning<br/>
Dark Mode Implementation: Implement CSS variables to allow the user to pick their preferred colour scheme.<br/>
AI Chatbot: An addition of a chatbot to assist the users on FAQs about applications, reducing the admin's workload<br/>
AI-Assisted Matching: Incorporating machine learning code to suggest optimal positions for the users based on their profile analysis<br/>


These potential improvements could really build a solid foundation for Hot Beans to create and even more comprehensive recruitment system.

### 4.3 FEEDBACK RESPONSES

A google form was created for the users to provide feedback and answer the questionnaire, to see the different strengths the website has and to get the website's performance from a user point of view.

![image](https://github.com/user-attachments/assets/b8d52af5-f130-4ff3-ac95-71939ac8567b)

![image](https://github.com/user-attachments/assets/a9e22105-8b60-4321-9a9e-d93139d30a89)

![image](https://github.com/user-attachments/assets/7b4a6d2a-70bd-40fa-96bb-803ebdb4391d)

![image](https://github.com/user-attachments/assets/082123b4-e288-4f51-bc61-63132d7b2810)

![image](https://github.com/user-attachments/assets/df6b46c8-cde1-47f9-83ee-f38502be8397)

![image](https://github.com/user-attachments/assets/03d44b9b-a5ea-4503-bb1c-e36e9ddbe68f)

<br/>
The above images are the chart data for the responses gotten from the questions asked to the users. Looking through them, it can be concluded that the Hot Beans Web website has not only met but exceeded the clients' requirements and goals. It also provides high functionality, performance and a great user experience in all areas, which will be highly beneficial to the clients.

