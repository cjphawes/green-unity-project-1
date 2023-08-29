# Hand In Hand

---

**Hello Fellow Coders!**

Welcome to Hand in Hand, a volunteering hub for everyone's volunteering wants and needs. This project targets anyone who is willing to volunteer to help society and the planet as a whole, this being by location or type of volunteering.

This website aims to aid, not only avid volunteers but, newbies who want to start their volunteering journey! The website does this by offering various opportunities both globally or locally (based in the UK) and being able to sign-up for up to date information and news on new opportunities to volunteer for.

Take a look at my website [Here!](https://cjphawes.github.io/handinhand-project-1/)

Here's a quick glance at my website on a variety of device widths.

![A variety of screen widths of my website](/assets/readme-file-imgs/variety-of-different-screen-widths-of-website.png)

- Am I Responsive [Webpage](https://ui.dev/amiresponsive?url=https://cjphawes.github.io/handinhand-project-1/)

---

## The Process

#### Wireframes

This was my first design I wanted to acheive. Initially, I set out to create one webpage with multiple sections. As you can see, it has slightly changed due to me splitting it down into multiple pages, however the majority of elements remain included.

![first-initial-design](/assets/readme-file-imgs/first-wireframe-design.svg)

##### Header Section [Take me there!](#navigation-bar)

- This remains almost exactly the same, just with fewer links in the navigation bar.

##### Hero Section [Take me there!](#landing-page-hero-section)

- This has slightly changed, albeit I still kept the description text and CTA button with background image. But I decided to opt out for the email notifications and turn that into a whole page with the [Become a Member page](#become-a-member-page).

##### Endorsement Section

- I decided to completely remove this section due to uncertainty of copyright issues with using certain companies logos.

##### Opportunities Section [Take me there!](#opportunities-section)

- I took some elements of this design and implemented them while also adding additional elements, such as the [Aside Section](#aside-section).

##### Footer Section [Take me there!](#footer)

- This has remnants of the original design, however some elements have moved around the footer section while removing a title, link row and a few more links.

---

## Features

There are 4 pages for the user to navigate around. A [Landing Page](#landing-page), an [Opportunities Page](#opportunities-page) with all the options for volunteering, a [Become a Member Page](#become-a-member-page) with a sign-up form and a [Completed Sign-up Page](#completed-sign-up-page), giving the user visual confirmation of their successful sign-up form.

### Existing Features

##### Navigation Bar

- Featured on all 4 pages, it includes the website name/logo and navigation links. These are Home, Opportunities and Become a member links.
- The logo is interactive, allowing the user to click on it to return to the home page.
- It's identical on every page and there is an active styling on the individual link related to that page, to show the user which page they are currently on (apart from the completed signup page). This will aid the user with navigation without having to use the browsers back and forwards button to navigate.

![nav-bar](/assets/readme-file-imgs/nav-bar-of-handinhand-project.png)

##### Footer

- Featured on all 4 pages, it includes 2 sections, one with contact details and the other with links to social media platforms and the copyright notice.
- The email and phone numbers are accessible directly from the words themselves, if the user has their email/calling set up on their device. On smaller screen widths they are underlined for user visualisation that they are clickable links.
- The social media links externally go to their respective websites, this is so the user doesnt lose the page they're on within the website.

![footer](/assets/readme-file-imgs/footer-of-handinhand-project.png)

#### Landing Page

##### Landing Page Hero Section

- It includes a background image relating to the future of the planet, with low brightness, to give visual aid to the paragraph and CTA button on top.
- The CTA button is big and in the center providing visual hierarchy to the user to focus their attention on what I as the developer want them to click on, with an added visual animation of arrows pointing towards the CTA button.

![landing-page-hero-section](/assets/readme-file-imgs/landing-page-hero-section.png)

#### Opportunities Page

##### Opportunities Section

- There's a small paragraph giving guidance on how to start their journey volunteering.
- It provides a variety of horizontal card style opportunities for the user to select. They include a background image relating to the opportunity, with an associated icon, plus a small enticing description on the opportunity entails. A visual element added is when hovering over a oppportunity card, increasing in size to help the user identify which opportunity they are focused on.
- The associated icons help the user further identify which type of volunteering they have available to them.
- Each opportunity card has a CTA button, that all link to the Become a Member page. Visual aid is also given with changing the background and border when hovering over it.

##### Aside section

- I have added selection of recommended external websites, that help contribute to helping the planet/society with a description of what they do. This gives the user a variety of options not just from my website alone, making the user think my website is more official and professional. I also used the `target="_blank"` attribute, for creating external tab so users don't lose the webpage.

![opportunity-page](/assets/readme-file-imgs/opportunities-page.png)

#### Become a Member Page

##### Sign-up Form

- A visually easy form to fill out for new sign-ups, asking for basic information needed from new volunteers. It's large in size for users to see and the `placeholder` attribute is used to aid users in cases of uncertainty for inputs. Each input also has the `required` attribute so no section is missed.
- The CTA button, on hover, changes colour so the user knows what they're hovering over.

##### FAQ's

- There's four FAQ's in a dropdown style, providing common answers to questions. Low transparency is used on the background to make the background image, relating to providing care and love to the world, and text stand out more to the user.

![become-a-member-page](/assets/readme-file-imgs/become-a-member-page.png)

#### Completed Sign-up Page

- This shows visualisation for the user, showing the CTA button has worked and they have successfully signed up.
- There's an animation of green tick pulsating, adding more creatviity to the page and make it come alive more.
- There's two redirection links, back to the landing page and opportunities page in case they want to continue browsing the website without using the browsers back/fowards buttons.

![completed-signup-page](/assets/readme-file-imgs/completed-signup-page.png)

### Future Features to Implement

- A profile page for the volunteer once they've signed up.
- Favouriting volunteering opportunities, which can then be viewed in your profile section.
- A log-in feature as well as sign-up so returning users can log in to their profile.
- A filtering element for finding opportunities the user wants more easily.
- A visual map for showing the user where in the world the opportunities are located.

---

## Testing

- Testing was completed in Google Chrome, Microsoft Edge and Firefox web browsers, on different device screen widths.
- Every single link goes to the intended location, with the speed of transfer to new page being quick.
- The sign-up form CTA button was originally an anchor element, however I found that form validation was cancelled due to not being a button element. The conumdrum I came across was whether to use the `method="GET"` and my completedsignup.html page to redirect the user too or use `method="POST"` and use the Code Institute's formdump link. I opted for the better user experience option. However with that in mind, I know I have used the incorrect method due to the nature of a form wanting to **POST** data not **GET**. In the real world, I would use Javascript or another programming language to redirect the user, whilst using the `method="POST"` to ease the struggle, but with limited knowledge, this was the best I could do.
- I used the Lighthouse reporting tool in Google Chrome, Microsoft Edge & Firefox to test the performance of the website.
  - First time testing the performance, images massively made the webpage load time slow aswell as the animations. To correct this I reduced my image file sizes and changed their formats to webp. However this didn't help enough on the opportunities.html page as the load time is still slow.

### Validator testing

##### HTML

- No errors were found using the official [W3C Validator (completed-signup.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fcompleted-signup.html)
- No errors were found using the official [W3C Validator (member.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fmember.html)
- No errors were found using the official [W3C Validator (opportunities.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fopportunities.html)
- No errors were found using the official [W3C Validator (index.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Findex.html)

##### CSS

- No errors were found using the official [(Jigsaw) Validator](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fcjphawes.github.io%2Fhandinhand-project-1%2Fassets%2Fcss%2Fstyle.css&usermedium=all&vextwarning=&warning=1)

### Unfixed Bugs

- Become a member page FAQ's causes the background image to move upon opening of the individual FAQ's, I was unable to find a fix for this while using the same background image due to the dimensions of the image.

---

## Deployment

The website was deployed to Github Pages.

- To do so, I followed these steps:
  **1.** From your website Github repository, navigate to **Settings**.
  **2.** Make sure your default branch is set to `main`, in the left-hand side drop down menu, under **Code and Automation**, select **Pages**.
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
  - The individual card icons are taken from Font Awesome.
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
