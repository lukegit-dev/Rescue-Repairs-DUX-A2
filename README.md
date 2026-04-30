# Rescue Repairs
# Table of Contents
- [1. Rescue Repairs](#rescue-repairs)
  * [1. Design](#1-design)
    + [1.1 Aims & Objectives](#11-aims--objectives)
    + [1.2 Initial design](#12-initial-design)
    + [1.3 Revised Wireframes](#13-revised-wireframes)
  * [2. Development](#2-development)
    + [2.1 Screenshots & Demonstration of design](#21-screenshots---demonstration-of-design)
    + [2.2 Reflection](#22-reflection)
    + [2.3 Deployment Page](#23-deployment-page)
  * [3. Testing](#3-testing)
    + [3.1 Manual Testing](#31-manual-testing)
    + [3.2 Automated](#32-automated)
      - [3.2.1 W3C HTML Validator](#321-w3c-html-validator)
      - [3.2.2 Google Lighthouse](#322-google-lighthouse)
  * [4. Revised User Stories](#4-revised-user-stories)
  * [5. References](#5-references)
## 1. Design
### 1.1 Aims & Objectives
The aim of Rescue Repairs is to give customers a reliable service when they need to upgrade or repair a system they have. The site is designed to be user-friendly with clear and easy navigation throuhout the site.
### 1.2 Initial design
I decided I would create a simple looking website in line with the user stories with great accessibility on navigating the site and reading easily.
### 1.3 Revised Wireframes
1. The home page design was revised to show a box containing the text of who Rescue Repairs are, and their goals, compared to just having text in the centre of the screen and being Lorum Ipsum.
2. For wireframe images 2 and 3, they displayed a search field for each component for you to upgrade, and a second page for repairs with a drop down menu. I combined both to avoid confusion with drop down categories instead of a search feature as I included a request text box where the customer can include any relevant information they would like to add to their new system / fixed.
## 2. Development
### 2.1 Screenshots & Demonstration of design
<img src="images/Demonstration%201.png" alt="Home"></img>
<img src="images/Demonstration%202.png" alt="Upgrade & Repairs"></img>
<img src="images/Demonstration%203.png" alt="Contact Page"></img>
<img src="images/Demonstration%204.png" alt="Contact Page"></img>
### 2.2 Reflection
Designing the site, my idea was to use a white background and blakc text for good contrast. Additionally, I used the sans-serif font for easier readability and being more dyslexia friendly. The navigation is shown at the top of each page with clearly defined categories to help the user decide where they want to go.

On the Home page, I designed boxes with clear titles, and relevant text. The Upgrades & Repairs have options which you can choose from and a submit button. Similarly on the Contact page, you are required fill out each box to submit, otherwise it will prompt the user to fill it in.
### 2.3 Deployment Page
You can find the website on [github-pages](https://lukegit-dev.github.io/Rescue-Repairs-DUX-A2/).
## 3. Testing
### 3.1 Manual Testing
For Upgrade & Repair options test:
1. The form can be submitted empty. I used a `required` tag to make sure all form boxes are filled in
2. The form category changes when a different service is selected. This issue was found and fixed before the commit, where I did not clear the innerHTML of the previously chosen option, causing this bug. The fix now shows the default category option for "Upgrade" being SSD Upgrade, and switching service to "Repair" changes the category to Monitor issue.
3. Different categories can be listed - Added `<option></option>` tag where each different option is listed within each category when a service is selected.
### 3.2 Automated
#### 3.2.1 W3C HTML Validator
Previously, I had a couple errors via the HTML Validator shown below. The new git commit fixes are labelled to show this. 
<img src="images/W3C%20HTML%20Validator.png" alt="HTML Validator"></img>
For `<html>` tags at the top of my HTML files, I will include `lang="en"` so browsers and screen readers know what language the page is in to avoid getting wrong pronounciations ([validatehtml.com](https://validatehtml.com/blog/common-html-errors), 2026).
#### 3.2.2 Google Lighthouse
Here are meaningful images on a Google Lighthouse Analysis I ran, shown below.
<img src="images/Google%20Lighthouse.png" alt="Google Lighthouse Review"></img>

Insights:

<img src="images/Google%20Lighthouse%20NDT.png" alt="Google Lighthouse Review"></img>
<img src="images/Google%20Lighthouse%20Cache%20%26%20Render.png" alt="Google Lighthouse Review"></img>

Accessiblity:

<img src="images/Google%20Lighthouse%20Accessibility%20Landmark.png" alt="Google Lighthouse Review"></img>

SEO:

<img src="images/Google%20Lighthouse%20SEO%20Meta%20description.png" alt="Google Lighthouse Review"></img>

As of now, no bugs remain unsolved.
## 4. Revised User Stories
Name: Jay

Group: Frequent visitor.

Background: Being a Youtuber, Jay works with video and audio software such as Adobe Premiere to create his videos. Since birth, having dyslexia has made it tricky for him to read words. Because of this, he prefers having 1-to-1 conversations with people which he does by livestreaming, calling his friends, and going out a lot. Story: As a frequent visitor, I want to find their mobile number quickly so I can talk about preinstalled software on my custom-built PC they made for me, so that I get real-time feedback and can solve problems and queries quicker. Tasks: Navigate to the general customer support page.

Criteria: Given that Jay is dyslexic and prefers speaking than texting, needs to find the mobile number of our company when he needs PC support, then should add a mobile number at the footer of our page in a dyslexia-friendly font like sans-serif.

**Requirements Met?** Yes. Added criteria described.

Name: Chad

Group: First-time customer.

Background: Chad works as a graphics designer using tools like Photoshop (What Does a Graphic Designer Do? (And How to Become One) | Coursera). He is good at designing logos and adverts, but can get easily overwhelmed when having long, technical instructions to follow. He is a visual learner and prefers step-by-step instructions and likes working independently. Story: As a first-time customer, I want to quickly seek what upgrade options are available as my PC is running slower having used it for multiple years. I want to feel confident when choosing what to upgrade as I know they can be expensive. Tasks: Navigate to the PC parts picker page.

Criteria: Given that Chad is a visual learner, our page should have a clear category tree for easy navigation. On the page, we can have text boxes to search for PC specification parts which are compatible with his current build, along with a part (replace) installation guide consisting of clear, concise, step-by-step instructions with images on how to do so.

**Requirements Met?** Yes. Clear navigation through obvious titles and forms, coloured boxes for information on home page gives the user something to focus more on.

Name: Millie

Group: Returning visitor.

Background: Working as a full-time software developer manager, Millie relies on her PC for meetings, programming, and supporting others with remote access tools. With busy deadlines and managing others, she strives to be efficient at her job, and hates waiting around. Story: As a returning visitor, I want to quickly repair my PC as I need it for my remote work, I cannot wait hours so want a same day repair, and am willing to pay them extra for it. Tasks: Navigate to the booking scheduler / PC repair page with a phone number she can ring.

Criteria: Headings for scheduling a repair, pricing, and a phone number. A form to fill out should contain necessary information (name, address, card information, etc..), and an appointment day and time (e.g. same-day repair or DD/MM/YYYY @ 12:30), along with a mobile number at the footer if they prefer to call (which may suit Millie better considering her urgency).

**Requirements Met?** Yes. Hyperlinks were added in the home page boxes, along with the navigation bars at the top to make it easy for Millie to access contact forms. Additionally, the form is not complex, has a clean layout, and a footer page at the end of the website is always visible with a phone number she could click and call.
## 5. References
Reference listmozilla.org (2024). What are hyperlinks? - Learn web development | MDN. [online] MDN Web Docs. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Web_mechanics/What_are_hyperlinks.

Randomblue (2011). CSS: center element within a element. [online] Stack Overflow. Available at: https://stackoverflow.com/questions/6810031/css-center-element-within-a-div-element.W3Schools (2019).

HTML Startup. [online] W3schools.com. Available at: https://www.w3schools.com/TAgs/tag_html.asp.W3Schools (2020).

HTML Colors. [online] W3schools.com. Available at: https://www.w3schools.com/html/html_colors.asp.W3Schools (2023a).

HTML Forms. [online] W3schools.com. Available at: https://www.w3schools.com/html/html_forms.asp.W3Schools (2023b).

HTML Responsive Web Design. [online] W3schools.com. Available at: https://www.w3schools.com/html/html_responsive.asp.W3schools (2019).

Learning CSS Basics. [online] W3schools.com. Available at: https://www.w3schools.com/Css/css_intro.asp.w3schools (2019).

Window alert() Method. [online] W3schools.com. Available at: https://www.w3schools.com/jsref/met_win_alert.asp.
