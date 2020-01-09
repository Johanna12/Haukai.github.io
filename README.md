# The Haukai Restaurant
This web application enables users to make bookings at the Haukai restaurant in Kerikeri.

1.	(C) Accessibility Guidelines

Accessibility is designed to help people of all learnings to use the worldwide web.  This means that web applications should be designed with various disabilities in mind, so that users with disabilities in sight, sound, movement or cognitive difficulties might still be able to access information on the internet.  Accessibility might also include the elderly, mobile users, users on a slow internet and users with a temporary disability.  Making this website accessible meant that the following changes had to be made:

    1.	The header labels of <h1>, <h2>, … <h5>.  This means that the headers had to be in order.
    2.	Tabular data had to be arranged with ids and headers.
    3.	Images required an alt text to tell the user what the pictures.
    4.	The blue colour was chosen for the headings to help colour-blind people, since blue is a better colour for them.
    5.	Content is accessible with the keyboard.  This is created by using the <a> element to enable a clickable link to another website          or webpage.  The <a> element is usually followed by the “href”.  
    6.	ARIA (Accessible Rich Internet Applications) is a set of attributes in Java script to help users with disabilities access           information.  Roles are written in the code.  The roles in this web application are:

        •	Image: the “div role=”img” with aria labelled a description of the image.
        •	Lists: The role=”list box” for the carousel.
        •	Role for “lists”.

1.  	(E)  Security issues

The importance of security for websites includes correct coding especially when creating forms.  The code SQL injection can occur when forms have not been coded with proper coding.  Another security issue is when creating logins and passwords.  Passwords that are not encrypted either in storage or transit are at more risk of interception.  The use of https rather than http is also advisable so that a proper security certificate is used especially if personal information of customers such as credit card details, name, address, etc is submitted via servers. 

HTTP caching and Content Delivery Networks (CDN)
HTTP caching occurs when a browser saves the sessions of users browsing the internet and returns these resources when requested again later.  If a browser uses a local cache then it avoids the HTTP request, fetching previous resources quickly.  Web caches reduces network traffic, latency and the time it takes to display the image.  
Content Delivery Network (CDN) is hosting that can be used instead of standard hosting when you load some of the traffic off from cloud-based servers.  They operate on servers that are distributed across several data centres.  CDN can reduce your page loading time, more manageable traffic, a securer network, reduced downtime issues and offers much more.  CDN also keeps sites secured with updated TLS/SSL certificates ensuring that authentication, encryption and integrity is maintained. CDN cuts down bandwidth and can help improve responsiveness in the website.

2.	(B) Responsive Design

Bootstrap 4
To make the website application responsive, the Bootstrap 4 framework was used.  Bootstrap consists of HTML, CSS and Java script.  It follows the standards for responsive design allowing users to view web applications on any screen size.  The application program of Bootstrap responds to the http request and outputs a dynamic web page with html elements.  To use the framework, we insert links to jQuery, bootstrap of CSS and js files.  Bootstrap was used for the Haukai website.  To ensure the responsive design in the website, the following elements and responsive principles was applied to the code.

Embed 
The div class “embed-responsive embed-responsive-16by9” tag and the iframe class of “embed-responsive-item” was used in the html code for the bootstrap framework.  

Viewport
To make the website application responsive, the viewport code was also applied:
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

CSS Design
Using bootstrap is quite simple.  The Bootstrap software program already comes with CSS styling and references to their style sheets is by simply linking the CSS sheets to the web page such as:
<link href="css/modern-business.css" rel="stylesheet">


2. 	(C) Trailing Whitespaces

Trailing Whitespaces is a software program that is installed into Visual Code to find the extra spaces in code, or tabs after the last non-whitespace character on the line until the new line.  There are 25 Unicode characters that are considered whitespace.  Removing white space helps developers code with speed.  If edits are to be made, the cursor will go to what ever the “end of the line” is, and if the end of the line has 3 or 4 characters to remove then, it was not the end of the line.  This takes up extra time to remove, before adding a new line of code.  Another reason is that when there are string literals that span multiple lines, trailing whitespace can make the output string look incorrect when its used. 

 
2.	(D) Chrome’s DevTools

Chrome Dev Tools is a program that detects network activity.  The tool offers a network panel page that will search a page that you request to record the loading time.  Testing the page requires the following steps:
1.	Click onto the Google Chrome browser.
2.	Type in the web page or open the web page on your local directory.
3.	Click on the right-side icon of three dots lined vertically.
4.	Click on “More Tools”.
5.	Click on “Developer Tools”.
6.	In the right-side panel, search along the header and click on the “Network” tab.
7.	Refresh the web page.
8.	Page loading time can be viewed on the bottom half of the network page and check the “Time” tab to see the loading time.
In the Haukai website, the page loading time for all pages:
•	Contact page = 3.4 s or 195 ms
•	Disclaimer = 272 ms
•	Home = 256 ms
•	Hours = 1.81 s
•	Map = 1.22 s
•	Menu = 307 ms
•	Reservations = 2.7 s
•	Privacy = 257 ms

In all, the testing was quite successful.  
