## Wireframe Assessment - Portfolio Design

### Moodboarding and Colour Scheme
___
#### Colour Scheme
I want this portfolio page to be cohesive in its design, and also for the colour scheme to have some longevity. For this I would use a Monochrome or Analogous theme with bold colours only being used for emphasis and animations.  
Will stick to blues, purples and deep reds and reconsider as I go. Would like to use a gradient background for the main section from a slightly saturated blue to a desaturated grey blue.
Colours as below:
- Font Colours
    - Light to contrast dark background colours, dark to contrast light backgrounds
    - All sticking to theme colour pallette
- Header 
    - Darkest shade of chosen colour
    - Nav buttons to be light tint of chosen theme colour w/ dark shadow to pop
- Main
    - Background: Muted version of theme colour, gradient to grey in bottom right corner
    - Cards: Darker shade of chosen colour w neon glow border
- Footer
    - same colour as header to create clean and cohesive look

### Moodboarding
<img src="https://codehalweb.com/wp-content/uploads/2023/05/thumbnail-12-741x486.jpg" alt="Example of Web Portfolio Design" width="400px">

#### Colour Palette Options
<img src="./assets/bluescale.png" alt="Colour Palette for Monochrome Blue Design Theme" width="400px">
<img src="./assets/BRP Colour Scale.png" alt="Colour Palette for Blue Purple Red Design Theme" width="400px">

#### Font Family
- Consider old school courier/terminal fonts
- If this is not stylistically cohesive then look for sans serif font style groupings

### Pages and Sections

The home page is the base for explaining who I am and what my skills are/will be. The information here should be enough to form an idea of what the portfolio website is trying to achieve, with further details provided on all child pages. Nav bar reflects the priority of other pages on the site, with projects, work history and finally contact as the heirarchy. The footer is present on all pages and has direct contact details as well as links to social media and git.
___
#### Header, Footer and Navbar
Header is simple clean design static formatting for all subpages:
- Logo/Profile Picture top left image
- Nav bar 
    - 4x clickable anchor link buttons
        - Home
        - Projects
        - Work History
        - Contact  

Footer contains: 
- Copyright information 
- Social media clickable links (circular icon style)
- direct contact info (email mailto link)

#### Home page (index.html) 
 All information listed below is in the "MAIN" section of each page
Main
Landing page with "about me" section, including basic personal information, hobbies and interests.  
Will use static elements and containers including large profile image. 
Animation can go here: 
- fade in for "about" section 
- Grayscale colour fade in for large photo

#### Projects
Flexbox and Card divs for projects with the following in each:
- Image Thumb - code snippet for each project
- Project Title - Title 
- Description of project and skills/languages used
Can link to all repos on GitHub directly through clickable image thumb, as well as upcoming assessments in the DEV1001/1002 modules.

Ideally use shadow and/or neon effect to add emphasis to each, with hover psuedoclass.  
Ideas for unique hover animations:
- Neon colour change effect on hover
- Grayscale all other cards on hover? 
	- This one would be a challenge as we haven't really covered this on any lessons, would look cool though to emphasise the one card!

#### Work History
Formatting similar to above, with additional details below:
- Scale animation on hover
- Other job experience including ZV & skills, Brooksfield & skills. 
- Excel file snippets (macros and logic strings)
- Link to file on html page - Resume.PDF  
- Any external links to websites as needed!

## Responsive Design
__
### Mobile Device
Max Screen width 600  
- No hover animations for any sections  
- adjust font size with dvw
- adjust home page detail 
- re-display card content as single scrollable column
- thumbnail image spin animation on click/touch?
- adjusted element size with dvw


### Tablet Device
max screen width 820  
- No hover animations for any sections  
- re-display card content as dual scrollable columns
- thumbnail image spin animation on click/touch?
- adjusted element size with dvw



## References: 
|Concept|Websites Used| Used for |
|:---:|:---:|:-----:|
|Device Pixel Sizes|https://www.browserstack.com/guide/ideal-screen-sizes-for-responsive-design | Used to correctly represent screen size in wireframe for iPad, iPhone|
|Colour Theory| https://codehalweb.com/complete-responsive-personal-portfolio-website/ | Used reference image as part of Moodboarding