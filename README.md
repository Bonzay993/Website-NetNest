# NetNest Website

Welcome to the NetNest Website project! This website is designed to showcase the services and offerings of NetNest, a business specializing in hosting services.

## 1. Purpose of the Project

The purpose of this project is to create an online platform where users can explore the services provided by NetNest, learn about different hosting solutions, and get in touch for further inquiries or purchases. It aims to provide a comprehensive overview of NetNest's offerings while offering a seamless user experience.

## 2. User Stories

- As a user, I want to easily navigate through the website to find information about NetNest's services.
- As a user, I want to understand the features and benefits of different hosting solutions offered by NetNest.
- As a user, I want to be able to contact NetNest easily for inquiries or to discuss custom solutions.
- As a user, I want to explore customer testimonials to gauge the reliability and quality of NetNest's services.

## 3. Features

### Responsive Design
- **Mobile-Friendly Layout:** The website is designed to be fully responsive, ensuring a seamless experience across desktops, tablets, and mobile devices.
- **Flexible Flex System:** Uses a flexible Flex system that adapts to various screen sizes and orientations, providing an optimal viewing experience.

### Hosting Services Information
- **Feature Comparison Tables:** Interactive tables that allow users to compare the features of different hosting plans side by side.
- **Pricing Information:** Clear and transparent pricing details for each hosting plan, including any discounts or special offers.

### Customer Testimonials
- **User Reviews:** A section dedicated to customer testimonials, showcasing positive feedback and experiences from current clients.
- **Star Ratings:** Visual star ratings to quickly convey customer satisfaction levels.

### Contact Form
- **Inquiry Form:** A comprehensive contact form for users to submit inquiries, request quotes, or ask for support.
- **Spam Protection:** Built-in CAPTCHA or similar mechanisms to prevent spam submissions.
- **Contact Details:** Display of additional contact details, including phone numbers and email addresses for direct communication.


## 4. Future Features

- Integration with a knowledge base or FAQ section to address common queries.
- Live chat support for real-time assistance.
- Client dashboard for managing hosting accounts and accessing support resources.
- Integration with popular content management systems for seamless website setup.

## 5. Typography and Color Scheme

- **Typography:** The website utilizes a clean and modern Lato and Roboto font for readability and professionalism.
- **Color Scheme:** The color palette includes shades of blue and gray to convey trustworthiness and professionalism. Accent colors are used sparingly to highlight important elements and calls to action.

## 6. Wireframes

Wireframes for the website can be found in the `wireframes` directory of this repository. These wireframes provide a visual representation of the layout and design of the website pages.
 <p align="center">
   <img src="https://github.com/Bonzay993/Website-NetNest/blob/main/wireframes/Website-Desktop.jpg" style="width:60%; margin: 0 auto;"> 
 </p>

## 7. Technology

  - **HTML5:** Provides the structure and content of the website.
  - **CSS3:** Used for styling and layout, ensuring a visually appealing design.
  - **JavaScript:** Adds interactivity and dynamic content to the Help section of the website.
  - **Font Awesome:** Provides scalable vector icons that can be customized with CSS.

## 8. Testing

### 8.1 Code Validation

Ensuring the quality and correctness of the code is crucial for a robust and reliable website. The HTML and CSS code for the NetNest Website has been validated using the W3C validation services.

#### HTML Validation
- **W3C HTML Validator:** The HTML code has been checked using the W3C HTML Validator to ensure it follows the standards and is free from errors.
  - [Validate HTML](https://validator.w3.org/)

#### CSS Validation
- **W3C CSS Validator:** The CSS code has been validated using the W3C CSS Validator to ensure it meets the standards and is error-free.
  - [Validate CSS](https://jigsaw.w3.org/css-validator/)

#### Ligthouse Report
<p align="center">
  <img src="https://github.com/Bonzay993/Website-NetNest/blob/main/testcases/img/lighthouse-report1.png" style="width:80%;">
  <img src="https://github.com/Bonzay993/Website-NetNest/blob/main/testcases/img/lighthouse-report2.png" style="width:80%;">
</p>

### 8.2 Test Cases

For detailed test cases and steps to test the website, please refer to the [Test Cases](https://github.com/Bonzay993/Website-NetNest/wiki/Test-Cases) Wiki.

### 8.3 Fixed Bugs

For detailed changes and fixes, please refer to the latest [Releases Page](https://github.com/Bonzay993/Website-NetNest/releases)

### 8.4 Supported screens and browsers

#### Supported Screens
This website is designed to be responsive and works seamlessly across various screen sizes, including:
- Desktop screens (1200 pixels and above)
- Tablets and small laptops (976 pixels and above)
- Mobile devices (less than 976 pixels)

#### Supported Browsers
The website is compatible with all modern browsers, including:
- Google Chrome (latest versions)
- Mozilla Firefox (latest versions)
- Safari (latest versions)
- Microsoft Edge (latest versions)
- Opera (latest versions)

#### Simulators Used for Testing
To ensure the website looks great on all devices and browsers, the following simulators were used:
- Chrome DevTools Device Mode
- Firefox Responsive Design Mode
- Safari Web Inspector
- Microsoft Edge DevTools
- Opera Developer Tools

## 9. Deployment

### 9.1 Gitpod 

#### 1. Linking the Repository to GitHub

 **Clone the Repository:**
   - Open a terminal.
   - Navigate to the directory where the repository should be cloned.
   - Use the following command to clone the repository:
     ```bash
     git clone https://github.com/Bonzay993/Website-NetNest.git
     ```

 **Link to GitHub:**
   - Navigate into the cloned repository directory:
     ```bash
     cd Website-NetNest
     ```
   - Link the local repository to the GitHub repository:
     ```bash
     git remote add origin https://github.com/Bonzay993/Website-NetNest.git
     ```

 **Push Your Code:**
   - Push local changes to GitHub:
     ```bash
     git push -u origin main
     ```
   - Replace `main` with the name of the main branch if it differs.

#### 2. Opening the Workspace in Gitpod

 **Access Gitpod:**
   - Go to [Gitpod](https://gitpod.io/) and sign in with your GitHub account.

 **Open Workspace:**
   - Open the repository directly in Gitpod by appending `gitpod.io/#` to the repository URL:
     ```
     https://gitpod.io/#https://github.com/Bonzay993/Website-NetNest
     ```
   - This URL will automatically open the repository in a Gitpod workspace.

#### 3. Configuring Gitpod Extensions

Gitpod allows enhancing the development environment with extensions. Here are recommended extensions:
Install in Gitpod:
     - Open Gitpod.
     - Go to Extensions.
     - Search for "VSCode Icons" and click Install.

 **Live Server:**
   - Automatically reloads the website when files are saved.
   
 **Prettier:**
   - Code formatter that maintains code cleanliness and consistency.
   
 **VSCode Icons:**
   - Adds icons to files and folders in the file explorer for better navigation.
     

### 9.2 GitHub Pages

#### Setting Up GitHub Pages

1. **Navigate to Repository Settings:**
   - Go to the GitHub repository: [Website-NetNest](https://github.com/Bonzay993/Website-NetNest).
   - Click on the "Settings" tab.

2. **Select Source Branch:**
   - Scroll down to the "GitHub Pages" section.
   - Under "Source", select the main branch (e.g., `main`) from the dropdown.
   - Click on "Save".

3. **Access the Deployed Site:**
   - After saving, scroll back down to the "GitHub Pages" section.
   - A green success message will display with the site's URL.
   - The site will be published at:
     ```
     https://Bonzay993.github.io/Website-NetNest
     ```
   - It may take a few minutes for the site to be accessible after the initial setup.

#### Updating the Deployed Site

Whenever new changes are pushed to the main branch on GitHub, GitHub Pages will automatically rebuild and update the site.

## 10. Credits
**[Font Awesome](https://fontawesome.com/search)** - Custom fonts


