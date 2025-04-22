## Wireframe Assessment - Portfolio Design

### Moodboarding and Colour Scheme
___
### Moodboarding
I want this portfolio page to be cohesive in its design, and also for the colour scheme to have some longevity. That means not using and trendy palettes or overly glitzy/gradiented/energetic colours, and usign a simple and reflexive design. Mainly I want this website to show off some of my skills, and to show a little of my personality!

I found this example of a portfolio page, and really liked the different sections and content! It's a good example of essentially what our portfolio assignment boils down to. I have not used any code but really enjoy the colour scheme and overall cohesive design.  

<picture>
<img src="https://codehalweb.com/wp-content/uploads/2023/05/thumbnail-12-741x486.jpg" alt="Example of Web Portfolio Design" width="400px">
</picture>  

An example of colour schemes and design. *Codehal, viewed 2025*

#### Colour Scheme
For this I would use a Monochrome or Analogous theme with bold colours only being used for emphasis and animations.  
Will stick to blues, purples and deep reds and reconsider as I go. Would like to use a gradient background for the main section from a slightly saturated blue to a desaturated grey blue.  
Colours as below:
- Font Colours
    - Light to contrast dark background colours, dark to contrast light backgrounds
    - All sticking to theme colour pallette
- Header 
    - Darkest shade of chosen colour palette
    - Nav buttons to be light tint of chosen theme colour w/ dark shadow to pop
- Main
    - Background: Muted version of theme colour, gradient to grey in bottom right corner
    - Cards: Darker shade of chosen colour w neon glow border
- Footer
    - same colour as header to create clean and cohesive look



#### Colour Palette Options
**Option 1**  
The first colour scheme option is for a monochrome palette of muted blues. I really enjoy this colour scheme as blues tend to evoke calmness and reliability, and greys stability and strength of character. The addition of the darkest blue also is close to black which is mystery and sophistication.  

<picture>
<img src="./assets/bluescale.png" alt="Colour Palette for Monochrome Blue Design Theme" width="400px">
</picture>  

Monochrom colour palette example. *Coolors, viewed 2025*

**Option 2**  
The second colour scheme is a little more diverse, with a few extra colours to add some highlighting and details. Since a portfolio is so important to your ongoing success and hirability as a developer, I would like to use this if not initially but in future to really bring particular focus to certain elements and aspects of the page.   

<picture>
<img src="./assets/BRP Colour Scale.png" alt="Colour Palette for Blue Purple Red Design Theme" width="400px">
</picture>  

Three colour palatte example. *Paletton, created 2025*  
Overall I would love to at some point really bring in some fun to the page and link to alll major projects with their associated terminal colour schemes! That seems like it would be a great way to integrate a sense of familiarity to each project. If you see the Ubuntu colour scheme? That's probably been designed in Ubuntu!

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
- Name & Github Handle Logo top right above nav buttons

Footer contains: 
- Copyright information 
- Social media clickable links (circular icon style)
- direct contact info (email mailto link for desktop, email address for mobile and tablet users)

#### Home page (index.html) 
Main  
Landing page with "about me" section, including basic personal information, hobbies and interests, as well as what programming/design languages I have experience with.
Will use static elements and containers including large profile image. 
- Animations
    - fade in for "about" section 
    - Grayscale colour fade in for photo
    - rotation animation for large photo

#### Projects
Main  
Flexbox and Card divs for projects with the following in each:
- Image Thumb - code snippet for each project
- Project Title - Title 
- List of skills/languages used
Alongside the card container will be a "Project Details" section with further detail for each project.
Link to all repos on GitHub directly through clickable image thumb, as well as upcoming assessments in the DEV1001/1002 modules.
Card will also be clickable to link to the correct detail section.

Ideally use shadow and/or neon effect to add emphasis to each, with hover psuedoclass.  
Ideas for unique hover animations:
- Neon colour effect on hover
- Grayscale all other cards on hover? 
	- This one would be a challenge as we haven't really covered this on any lessons, would look cool though to emphasise the one card!
- Scale increase on hover to add emphasis and make text more readable?

#### Work History
Main  
Formatting similar to above, with additional details below:
- Scale animation on hover
- Other job experience including ZV & skills, Brooksfield & skills. 
- Excel file snippets (macros and logic strings)
- Link to file on html page - Resume.PDF  
- Any external links to websites as needed through thumbnail for each job

## Responsive Design

### Mobile Device
Max Screen width 600  
- No hover animations for any sections  
    - Animation for each thumbnail to imply that links are clickable
- adjust font size using most appropriate industry standard responsive formatting
- display all content in one scrollable section
- adjusted element size with dvw


### Tablet Device
max screen width 820  
- No hover animations for any sections  
    - Animation for each thumbnail to imply that links are clickable
- re-display card content as dual scrollable columns
- adjusted element size with dvw
- adjust font size using most appropriate industry standard responsive formatting


___
 
|References|
|:---:|
|Browserstack 2025, *Ideal Screen Sizes for Responsive Design*, viewed 18 April 2025, https://www.browserstack.com/guide/ideal-screen-sizes-for-responsive-design | 
|Codehal 2023, 'Complete Responsive Personal Portfolio Website usign HTML, CSS Javascript', online image, 8 May, viewed 18 April 2025, https://codehalweb.com/complete-responsive-personal-portfolio-website/ |
|Coolors 2025, The super fast colour palettes, online image, created 18 April 2025, https://coolors.co/|
|Paletton 2014, *The Colour Scheme Designer*, online image, created 18 April 2025 https://paletton.com/| 