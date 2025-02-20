# Ramaas-Software-Services-Web-Application-Project

Ramaas Software Services is a London-based IT company specializing in bespoke application development, UI/UX design, hosting, and domain registration services. Established in 2002, the company is dedicated to delivering customer-oriented solutions effectively and on time. 
ramaas.com
Project Overview: Global Somali Diaspora
The Global Somali Diaspora (GSD) project aimed to create a platform to unite and mobilize Somali communities worldwide. The primary objectives were to advocate for the integration of Somali diaspora communities within their host nations, preserve cultural heritage, and encourage contributions to Somalia's peacebuilding and development efforts.
Team Structure and Responsibilities
The development of the GSD web application involved several specialized teams:
1.	Project Management Team: Oversaw project timelines, coordinated between teams, and ensured alignment with GSD's mission and goals.
2.	Business Analysis Team: Gathered requirements from stakeholders, analyzed user needs, and translated them into technical specifications.
3.	UI/UX Design Team: Crafted the visual design and user experience, focusing on creating an intuitive and engaging interface.
4.	Front-End Development Team: Implemented the designs into functional web pages, ensuring responsiveness and interactivity.
5.	Back-End Development Team: Developed server-side logic, managed databases, and ensured seamless data integration.
6.	Quality Assurance (QA) Team: Tested the application for bugs, ensured functionality, and verified performance across devices and browsers.
7.	DevOps Team: Handled deployment, server management, and maintained the hosting environment.
Your Role in the Front-End Development Team
As a member of the front-end development team, my contributions were pivotal in bringing the UI/UX designs to life. My specific responsibilities included:
•	Navigation and Hamburger Menu Development: You implemented a responsive navigation system, including a hamburger menu for mobile devices, ensuring users could easily access all sections of the site regardless of the device used.
•	Colour Scheme Implementation: Collaborating closely with the design team, you applied the chosen colour palette across the website, maintaining visual consistency and enhancing the user experience.
•	Layout and Frame Structure: You developed the structural layout of various pages, ensuring that content was organized logically and presented clearly. This involved creating responsive grid systems and ensuring compatibility across different screen sizes, by using media queries for an example.
•	In developing the Global Somali Diaspora website's front-end, I focused on creating a responsive layout that adapts seamlessly across various devices. This was achieved by implementing a CSS Grid system in conjunction with media queries to adjust the page's structure based on the viewport width.
•	Responsive Grid Layout Implementation
•	The layout was designed to display content in a four-column grid on desktop screens. As the screen width decreases, the number of columns reduces to maintain readability and usability:
•	Desktop View (Width ≥ 1200px): A four-column layout showcases multiple content sections side by side, providing a comprehensive view.
•	Tablet View (800px ≤ Width < 1200px): The layout transitions to a three-column grid, ensuring content remains legible without excessive scaling.
•	Mobile View (Width < 800px): A single-column layout is adopted, presenting content in a vertical stack for optimal mobile viewing.
•	Utilizing CSS Grid and Media Queries
•	To implement this responsive design, I employed CSS Grid for defining the layout structure and media queries to adjust the grid configuration at specified breakpoints. Below is a simplified example illustrating this approach:




/* Base styles for mobile-first approach */
.container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
  }
  
  /* Tablet view: 3-column layout */
  @media (min-width: 800px) {
    .container {
      grid-template-columns: repeat(3, 1fr);
    }
  }
  
  /* Desktop view: 4-column layout */
  @media (min-width: 1200px) {
    .container {
      grid-template-columns: repeat(4, 1fr);
    }
  }












In this code:
•	The .container class is set to display: grid, establishing a grid layout.
•	grid-template-columns: 1fr; defines a single-column layout by default, suitable for mobile devices.
•	Media queries adjust the grid-template-columns property based on the viewport width:
o	At a minimum width of 800px, the layout changes to three equal-width columns.
o	At a minimum width of 1200px, the layout expands to four equal-width columns.
This approach ensures that as the viewport width increases, the layout adapts accordingly, enhancing user experience across different devices.
Navigation and Hamburger Menu
For the navigation, I implemented a responsive design that transforms the traditional menu into a hamburger menu on smaller screens. This conserves screen space and maintains accessibility. Using media queries, the navigation adapts as follows:
•	Desktop View: The full navigation menu is displayed horizontally across the top of the page.
•	Mobile View: The navigation collapses into a hamburger icon. When clicked, it reveals a vertical dropdown menu.
This transformation is achieved by toggling CSS classes and utilizing JavaScript to handle the menus expand/collapse functionality.





Project Outcome
The successful collaboration among the teams resulted in the launch of the Global Somali Diaspora website. The platform effectively serves as a hub for Somali communities worldwide, offering resources, event information, and opportunities for engagement. Your contributions to the front-end development were instrumental in creating an accessible and user-friendly interface that reflects the organization's mission and values.
By detailing your specific roles and the collaborative efforts involved in this project, you can showcase your practical experience and understanding of web development processes, which will be valuable in your software engineering career pursuits.
