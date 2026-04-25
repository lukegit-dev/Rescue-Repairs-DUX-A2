# Rescue Repairs
## Design
### Aims & Objectives
The aim of Rescue Repairs is to give customers a reliable service when they need to upgrade or repair a system they have. The site is designed to be user-friendly with clear and easy navigation throuhout the site.
### User stories (informed design)
### Revised Wireframes
1. The home page design was revised to show a box containing the text of who Rescue Repairs are, and their goals, compared to just having text in the centre of the screen and being Lorum Ipsum.
2. For wireframe images 2 and 3, they displayed a search field for each component for you to upgrade, and a second page for repairs with a drop down menu. I combined both to avoid confusion with drop down categories instead of a search feature as I included a request text box where the customer can include any relevant information they would like to add to their new system / fixed.
## Development
### Screenshots & Demonstration of design
<img src="images/Demonstration%201.png" alt="Home"></img>
<img src="images/Demonstration%202.png" alt="Upgrade & Repairs"></img>
<img src="images/Demonstration%203.png" alt="Contact Page"></img>
<img src="images/Demonstration%204.png" alt="Contact Page"></img>
### Reflection
Designing the site, my idea was to use a white background and blakc text for good contrast. Additionally, I used the sans-serif font for easier readability and being more dyslexia friendly. The navigation is shown at the top of each page with clearly defined categories to help the user decide where they want to go.

On the Home page, I designed boxes with clear titles, and relevant text. The Upgrades & Repairs have options which you can choose from and a submit button. Similarly on the Contact page, you are required fill out each box to submit, otherwise it will prompt the user to fill it in.
### Deployment Page
## Testing
### Manual Testing
For Upgrade & Repair options test:
1. The form can be submitted empty. I used a `required` tag to make sure all form boxes are filled in
2. The form category changes when a different service is selected. This issue was found and fixed before the commit, where I did not clear the innerHTML of the previously chosen option, causing this bug. The fix now shows the default category option for "Upgrade" being SSD Upgrade, and switching service to "Repair" changes the category to Monitor issue.
3. Different categories can be listed - Added `<option></option>` tag where each different option is listed within each category when a service is selected.
### Automated
#### W3C HTML Validator
Previously, I had a couple errors via the HTML Validator shown below. The new git commit fixes are labelled to show this. 
<img src="images/W3C%20HTML%20Validator.png" alt="HTML Validator"></img>
For `<html>` tags at the top of my HTML files, I will include `lang="en"` so browsers and screen readers know what language the page is in to avoid getting wrong pronounciations ([validatehtml.com](https://validatehtml.com/blog/common-html-errors), 2026).
#### Google Lighthouse
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
### User stories (bugs & fixes)
Coming soon...
