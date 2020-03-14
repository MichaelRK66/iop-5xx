# iop-5xx

https://michaelrk66.github.io/iop-5xx/

WEB-240 RWD inside-out project - iop-5xx
STEP-500.0 | Branch 500-0
- added starter template to begin project
- pulled template via https://github.com/BlackrockDigital/startbootstrap-scrolling-nav

WEB-240 RWD inside-out project - iop-5xx
STEP-501.0 | Branch 501-0
- Update title in head to: welcome to me | Michael Koros
- change header bg class from primary to secondary
- Add image to header: http://via.placeholder.com/150x150
   - alt should be full name
- Update h1 in header to: Michael Koros
- Update tagline in header to: ...inspired innovative technology enthusiast & advocate.
- Removed the Services section and it's corresponding navigation link
- Updated the h2 for about to: Who I am...
- Updated the h2 for contact to: Contact me
- Added the following sections and their corresponding navigation links
    - Experience
        - h2: What I have done...
        - content: Experience: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut optio velit inventore, expedita quo laboriosam possimus ea consequatur vitae, doloribus consequuntur ex. Nemo assumenda laborum vel, labore ut velit dignissimos.
    - Education
        - h2: What I have learned...
        - content: Education: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut optio velit inventore, expedita quo laboriosam possimus ea consequatur vitae, doloribus consequuntur ex. Nemo assumenda laborum vel, labore ut velit dignissimos.
    - Skills
        - h2: What I can do...
        - content: Skills: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut optio velit inventore, expedita quo laboriosam possimus ea consequatur vitae, doloribus consequuntur ex. Nemo assumenda laborum vel, labore ut velit dignissimos.
    - Interests
        - h2: What inspires me...
        - content: Interests: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut optio velit inventore, expedita quo laboriosam possimus ea consequatur vitae, doloribus consequuntur ex. Nemo assumenda laborum vel, labore ut velit dignissimos.
    - Awards
        - h2: What makes me proud...
        - content: Awards: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut optio velit inventore, expedita quo laboriosam possimus ea consequatur vitae, doloribus consequuntur ex. Nemo assumenda laborum vel, labore ut velit dignissimos.
- updated the footer div container p Copyright &copy;  Your Website 2019 to iop-5xx.mikekoros.com 2020.

WEB-240 RWD inside-out project - iop-5xx
STEP-502.0 | Branch 502-0
- Updates & WP Site Changes
	- added and activated a new theme
		- WP Bootstrap Starter
		- Version: 3.0.11 
		- By Afterimage Designs
	- added following pages to http://iop-5xx.mikekoros.com/welcome-to-me/ WordPress site
	- welcome to me (nested home, about, experience, education, skills, interests, awards, & contact pages below)
    	- home
        	- copied content from header in to this page
        - about, experience, education, skills, interests, awards, contact
            - copied the content for each of the pages from the static site
            	- updated pages with <p>-from me</p> to easily validate successful API calls 
        - no content added to the "welcome to me" page - used as parent for API calls
        
WEB-240 RWD inside-out project - iop-5xx
STEP-502.0 | Branch 502-0
- README.md file changes
	- prepended the title to the production site link
	- added link to GitHub Pages to the top of the content
- index.html
	- code changes https://www.diffchecker.com/TIzg6HtF
		- code compare shows many changes because of nesting code inside main element
    - removed comments and cleaned code
    - added main element and nested all section elements inside of it
    - added link to Font Awesome Free 5.9.0 by @fontawesome via https://fontawesome.com to bottom of body for cog in splash screen
    - added link to app.js to bottom of body created in this step
- app.js
	- created in this step
    - code changes https://www.diffchecker.com/44lVfHq9
          