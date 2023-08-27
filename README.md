# Hand In Hand

---

**Hello Fellow Coders!**

Welcome to Hand in Hand, a volunteering hub for everyone's volunteering wants and needs. This project targets anyone who is willing to volunteer to help society and the planet as a whole in any aspect, either being location or type of volunteering.

This website aims to aid not only avid volunteers but also newbies who want to start their volunteering journey! The website does this by offering various opportunities both globally or locally (based in the UK). As well as being able to sign-up for up to date information and news on new opportunities to volunteer for.

Here is a quick look at my website on a variety of device widths.

![A variety of screen widths of my website](/assets/README-file-images/variety-of-different-screen-widths-of-website.png)
Am I Responsive [Webpage](https://ui.dev/amiresponsive?url=https://cjphawes.github.io/handinhand-project-1/)

---

## The Process

#### Wiregrams

---

## Features

We have 4 pages. Landing and opportunities page, become a member page with sign-up form and a completed sign-up page giving the user visual confirmation of sign-up completion.

### Existing Features

- **Navigation Bar**
  - Featured on all 4 pages, includes the website name/logo and the navigation links. Theese are a Home, Opportunities and Become a member link.
  - It's identical on every page and there is an active styling on individual links to show the user which page they are currently on (apart from the completed signup page). This will aid the user with navigation without having to use the back button to navigate forwards and backwards.

![nav_bar](/assets/README-file-images/nav-bar-of-handinhand-project.png)

- **Footer**
  - Featured on all 4 pages, includes 2 sections, one with contact details and the other with links to social media platforms.
  - The email and phone numbers are accessible directly from the icon if the user has their email/calling set up on their device. The social media links externally go to the respective websites, this is so the user doesnt lose the page they are on, on the website.

![footer](/assets/README-file-images/footer-of-handinhand-project.png)

#### Landing Page

- **Landing Page Hero Section**
  - The landing page includes a background image relating to the future of the planet, with lower brightness, to give visual aid to the paragraph and CTA button on top.
  - CTA button (Join The Fight) is big and in the center providing visual hierarchy to the user to focus their attention on what I as the developer want them to click on, with an added visual animation of arrows pointing towards the CTA button.

![landing_page_hero_section](/assets/README-file-images/landing-page-hero-section.png)

#### Opportunities Page

- **Opportunities Section**
  - A small paragraph giving guidance on how to start their jounrey volunteering.
  - Provides a variety of horizontal card style opportunities for the user to select. They includes a background image relating to the opportunity, with an associated icon, plus a small enticing description on what it entails. A visual element added is when hovering over a oppportunity, increasing in size to help the user identify which opportunity they are focused on. The associated icon helps the user decide what type of volunteering they would like to sign-up for.
  - Each opportunity has a CTA Button and they all link to the Become a Member page. Visual aid is also given with changing background and border when hovering over it.
- **Aside section**
  - A selection of recommended external websites, using the `target="_blank"` attribute for creating external tab so users don't lose the webpage, that also help contribute to helping the planet/society with a description of what they do. This gives the user a variety of options not just from my website alone, making the user think my website is more official and professional.

![opportunity_page](/assets/README-file-images/opportunities-page.png)

#### Become a Member Page

- **Sign-up Form**
  - A visually easy form to fill out for sign-ups, asking basic information needed from the volunteers. Large in size for users to see and also `placeholder` attribute is used to aid users in case of uncertainty for inputs. Each input also has the `required` attribute so no section is missed.
  - CTA button (Get Started Now) on hover changes colour so the user knows what they're hovering on.
- **FAQ's**
  - 4 FAQ's in a dropdown style providing common answers to questions. Low transparency on the background to see the background image which relates to providing care and love to the world.

![become-a-member-page](/assets/readme-file-images/become-a-member-page.png)

#### Completed Sign-up Page

- Visualisation for the user to show the CTA button has worked and they have signed up successfully.
- Added animation of green tick pulsating for more creativity to the page and make it come alive more.

![completed-signup-page](/assets/readme-file-images/completed-signup-page.png)

### Future features

- A profile page for the volunteer once they've signed up which integrates with the future feature below.
- Favouriting volunteering opportunities, which can then be viewed in your profile section.
- Always space for more volunteering opportunities, and with more could comes a filter element for finding opportunities the user wants more easily.
- A log in feature as well as sign-up so returning users can log in.

---

## Testing

- Testing was completed in Google Chrome, Microsoft Edge and Firefox web browsers, on different devices and screen widths.

- Every single link goes to the intended location, with the speed of transfer to new page being quick.
- The sign-up form CTA button was originally an anchor element, however I found that form validation was cancelled due to not being a button element. The conumdrum I came across was whether to use the `method="GET"` and my completedsignup.html page to redirect the user too or use `method="POST"` and use the Code Institute's formdump link. I opted for the better user experience option. However with that in mind, I know I have used the incorrect method due to the nature of a form wanting to POST data not GET, in the real world I would use Javascript or another programming language to redirect the user, whilst using the `method="POST"` to ease the struggle, but with limited knowledge this was the best I could do.
- I used the Lighthouse reporting tool in Google Chrome, Microsoft Edge & Firefox to test the performance of the website.
  - First time testing the performance, images massively made the webpage load time slow aswell as the animations. To correct this I reduced my image file sizes and changed their formats to webp. However this didn't help enough on the opportunities.html page as the load time is still slow.

### Validator testing

- **HTML**
  - No errors were found using the official [W3C Validator (completed-signup.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fcompleted-signup.html)
  - No errors were found using the official [W3C Validator (member.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fmember.html)
  - No errors were found using the official [W3C Validator (opportunities.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fopportunities.html)
  - No errors were found using the official [W3C Validator (index.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Findex.html)
- **CSS**
  - No errors were found using the official [(Jigsaw) Validator](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fassets%2Fcss%2Fstyle.css&usermedium=all&vextwarning=&warning=1)

### Unfixed Bugs

- Become a member page FAQ's causes the background image to move upon opening of the individual FAQ's, I was unable to find a fix for this while using the same background image due to the dimensions of the image.

---

## Deployment

The website was deployed to Github Pages.

- To do so, follow these steps:
  **1.** From your website Github repository, navigate to **Settings**.
  **2.** Make sure your default branch is set to `main` and then, in the left-hand side drop down menu, under **Code and Automation**, select **Pages**.
  **3.** Make sure the branch selected is `main`, and upon a refresh of the page, at the top of the page automatically, a link will populate detailing your live web address.

The live link can be found here - https://cjphawes.github.io/handinhand-project-1/

---

## Credits

#### Content

- **All Pages**
  - The footer icons, including social media platform logos, were taken from [Font Awesome](https://fontawesome.com/).
    <br>
- **Landing Page**
  - I used [Chat GPT](https://chat.openai.com/) for the brief user enticing text.
    <br>
- **Opportunities Page**
  - All the aside links and description, apart from British Red Cross and WWF, are from [Climate Volunteering](https://www.climatevolunteering.com/opportunities).
  - All the card descriptions are from Chat GPT that I auto-generated.
    <br>
- **Become a Member Page**
  - Sign-up and FAQ icons were taken from Font Awesome.
  - The FAQ question and answers were taken from [International Volunteer HQ](https://www.volunteerhq.org/gb/faq/).
    <br>
- **Completed Sign-up Page**
  - The green tick icon was taken from Font Awesome.

#### Media

- **Landing Page**
  - The hero background image was taken from [Adobe Stock](https://stock.adobe.com/uk/).
    <br>
- **Opportunities Page**
- The card style opportunity background images are from [Pexels](https://www.pexels.com/) & [Unsplash](https://unsplash.com/).
  <br>
- **Become a Member Page**
  - The background image was taken from Unsplash.

---
