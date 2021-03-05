# Milestone Project 1 - Personal Profile - readme

## 1. Introduction

This readme file contains the documentation associated with the first milestone project for the Code Institute Diploma in Software Development. This project milestone submission will consist of a personal portfolio site for me.

The goal of the website is not simply to re-tell the contents of my CV, but to provide an insight into my work experience and what I might be able to do for a client or potential employer.

## 2. Business Requirements & Use Cases

The use cases listed below have been numbered so that they may be referenced by the test document.

**Use case 1:** As a site visitor and a recruiter I want to know whether Chris Heisig is potentially the right candidate for my client.

**Use case 2:** As a potential employer I want to determine if Chris Heisig has the appropriate career background.

**Use case 3:** As the site owner I want to present my work experience and my skills in the best possible light to get hired.

**Use case 4:** As the site owner I want potential clients to learn what other skills and interests I have.

**Use case 5:** As a visitor to the website, want to be able to read its contents clearly on devices with different screen widths.

## 3. User Experience

### 3.1 Strategy

**3.1.1** To align with the Business Requirements and Use Cases.

## 3.2 Scope

The web site will display information demonstrating my work skills and work history in a clear and consistent manner regardless of the device used to view it.

Pages will be structured to allow future updates to be made without the need to re-factor the HTML or CSS

### 3.3 Structure

The web site will consist of 6 pages allowing information to be revealed in a structured way.

- The landing page

- A skills page

- A career history page

- A page opening up to a pdf of my CV

- A blog of my most recent projects

- A contact page

### 3.4 Skeleton

The following requirements have been identified at this level and referenced for testing purposes.

**3.4.1** A navigation bar will allow the visitor to easily access available pages.

**3.4.2** At small screen widths (320px) the navigation bar will collapse to an icon.

**3.4.3** Clicking on the collapsed icon will reveal the navigation bar vertically aligned.

**3.4.4** To aid visitor navigation, the navigation bar items will highlight indicating the page currently being displayed.

**3.4.5** Hovering above a navigation bar item will result in that navigation bar item being highlighted.

**3.4.6** With the exception of the page leading to the CV, all pages will display the header and footer in the same position.

**3.4.7** The user will always be able to navigate back to the home page.

**3.4.8** Each page will include a common banner to uniquely identify the web site.

**3.4.9** Clicking on icons located in either the header or footer will result in a successful hyperlink to the selected web site.

**3.4.10** It will not be possible to send me a message from the contact page without completing all the necessary fields.

**3.4.11** If the site visitor completes all the fields on the contact page and clicks on the submit button, then she/he will receive a confirmatory notification message.

### 3.5 Surface

The following requirements have been identified at this level and referenced for testing purposes.

**3.5.1** All pages will render to provide a readable display at 1206px, 768px and 320px screen widths. 

**3.5.2** The design will use a limited pallet of colours (less than 7).

**3.5.3** Each page will be structured using the "rule of three" unless this makes the page unreadable.

**3.5.4** If using the "rule of three" makes the page unreadable on a smaller screen, then in the first instance content will be stacked.

**3.5.5** If stacking text is not sufficient for making a page readable at a small screen width, then images and icons will be hidden from view.

### 4.0 Non Functional Requirements

**4.1** The HTML code will be submitted for checking by a code validator.

**4.2** The CSS file will be submitted for checking by a code validator.

**4.3** Time require load a typical page will be checked.

### 5.0 Development Approach

The development of the HTML and CSS code started with a design of each of the 5 pages (the copy of my CV in pdf makes 6) as a wireframe with each web page being represented by 3 [wireframe views](cv_wireframes.bmpr), one for each screen width (1026px, 768px and 320px). The wireframes detail the header, footer and main body of each page and how I wanted rows and columns to appear. As the wireframes are not scaled, the readability of the final web page was not easily determined.
Using the wireframes, I then developed the basic structure for the index page with section elements, a header and a footer. At this stage the content remained very basic with little or no styling. At this
stage I ignored the requirements for a responsive design. Once the index page provided some basic structure, I then used the index page code to create the other pages. With the basic structure in place for all pages, I started to record bugs as I came across them.

Next I addressed the requirements of the navigation bar and developed sufficient code to enable navigation between the different pages. While basic page navigation functioned, styling and the responsiveness of the design to different screen widths was not included.

I then added content to the main sections in each page and developed the contact page futher. As sending emails from within HTML code is beyond the scope of this project, I was advised to create a further page to be displayed when the submit button is clicked.

With this in place, started to address the requirements for a responsive design, testing often to check progress. I used a snippit of HTLM code provided by the instructor during one of the lessons to compress the navigation bar to an icon at a screen width of 320px, but adapted this to operate on the right hand side of the page rather than the left.

It was at this point that I realises it would be difficult for a visitor to read pages with three columns at a screen width of 768px. As a consequence, I re-designed pages with three columns of text to stack rather than appear inline.

From this point onward, I started to iteratively refine the code for each page and fix the bugs that I had recorded.

I then moved on to adding more styling. Finally, I used an online colour picker to identify the colours in the image running across the screen and used these to style other elements of the design.

Once happy with the design of each page, I then re-tested each page and checked the flow and spelling of the text. I then asked someone unfamiliar with the design to navigate their way through the web site. After correcting any last minute bugs, I was then ready to deploy using GitHub Web
Pages.

Both the HTML source files and the CSS source file have been divided into section by comments to enhance readability of the code.

I realise that there is probably a better way of appraoching the design, with no actual experience, this was no apparent. 


### 6.0 Initial Deployment

This milestone project was deployed at Milestone project 1 using Github Pages.

The associated Github repository can be found at [Milestone-1](https://chrish2727.github.io/Milestone-1/)

### 7.0 Update and Maintenance

The HTML code associated with each of the web pages is identically structure, with a header, footer, a section containing a central banner and one or more other sections that have different content depending on the information that it is intended to impart.

![Code Snip](Testimages/Codesnip.jpg){width=80%}

*fig: HTML Code Structure*

This should make it easy another coder to enhance or modify.

Note, that external hyperlinks are at the bottom of the script so that they load last allowing the main body of the page to render.


### 8.0 Design Constraints

The web pages associated with the URL www.exertus-solutions.co.uk. There is a hyperlink to www.exertus-solutions.co.uk at the top right of the header.

Emails sent from the contacts page do not reach a nominated email address and the response message is a dummy.

### 9.0 Future Enhancements

A further page could be added to highlight some of the interesting projects that I have undertaken. These projects demonstrate my passion for IOT and how this technology may be harnessed to monitor our environment for polution at a macro level. It also demonstrates my skills as a hardware engineer, and a developer of software for micro-controller applications. Epecially if the micro-controller is a low-cost and high performance device as may be found in billions of domestic products.

### 10.0 Defect/Resolution Log

|Date|Defect Description|Solution|
|---|---|---|
17-Feb-21|Although basic structure developed, styling outstanding|2-Mar-21 - styling improved	stop when good enough!|
21-Feb-21|At lower screen sizes when the Nav Bar collapses into an icon ok, the Nav items are however not displayed|Fixed 27-Feb-21 nav-bar-collapse implemented correctly	
21-Feb-21|Pages are not responsive to lower screen widths|Fixed 28-Feb-21	Unecessary icons and images also hidden at lower screen widths
20-Feb-21|Nav bar pills remain the standard blue when activated rather than changing to the selected colour|Fixed 28-Feb-21 default styling overwritten	
26-Feb-20|Message submit button does not hyperlink correctly|Fixed 26-Feb-21 Clicking on the submit button causes a hyperlink to acknowledgement page from where the user can return to the main web site	Note, that a normal response would be an email fired of to a nominated address
1-Mar-21|Column widths too narrow when viewed on a 768px screen|1-Mar-21 Fixed, content now displayed in rows at 768px.
1-Mar-21|Company icon (top left of the image) fails to hyperlink correctly|1-Mar-21 Fixed, no hyperlinks to an external web page. The external webpage is still under construction but deemed outside of the submission
2-Mar-21|Inconsistent colour pallet used across web pages|Fixed. The banner that is common to all pages was scanned with an on-line colour picker and the primary colours identified used as background.
3-Mar-21|CCS validation checker throws up a parse error.|Not fixed.

### 11.0 Acknowledgements

- Extensive use was made of the html CCS and bootstrap code referenced in the training material for this course.

- John Duckett's reference book HTML & CSS design and build websites provided an invaluable source of basic information.

- Bootstrap online documentaion provided useful references.