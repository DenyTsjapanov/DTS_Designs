# DTS_Designs

https://denytsjapanov.github.io/DTS_Designs/


## Description
This is my first website, created for the submission of my first milestone project. 
The purpose of the project is to create a landing page for a purpose of your choosing. 
Thus, I decided to create a ficticiuous website for a company, active in web design, web development and all other associated creative services. 
The website needs to have at least 3 pages (or in my case, 3 page sections), including a navigation panel and a use-friendly structure
The basic requirements for the code of the website are HTML and CSS. However, using bootstrap has been inevitable.

## UX/Design
As mentioned in the description, the website needs to have at least 3 pages. In my case, I opted for a one-page site, that scrolls through different sections.
On top you will find the company's brand name and navigation panel, which collapses when viewing the website on a mobile device. The navigation panel exists of 4 sections; Home, Services, Pricing and Contact.
Home takes back to the top of the page, as does clicking on the company brand name, "DTS", in the left top. Services, Pricing and Contact scrolls down accordingly.
The reason for choosing for such a structure, is purely simplicity. Putting myself in the place of the customer, I found that getting all the available information from a company by a simple scroll is more convenient that clicking on links.
Trying to achieve the most neutral and professional look, I chose for the "Helvetica" font, and forced this through the entire website. The reason for this is pure consistency. Personally, I find it sometimes a bit unprofessional to see different fonts used on a website. 
<br>
The 'home' section provides limited information, but enough to understand what the company does. Namely 'something with building a website'. A button is placed underneath the placeholder text to bring the customer directly to the pricing page. The reason for this is that when a customer is indeed interested in a service, he mainly wants to know what the fees are. Once the fees are 'accepted', then the customer will try to find out more about the services or features.
Scrolling down the page, the 'services'-section comes by, prividing the customer with 3 main factors why he would choose this company. This company is marketing themselves by not only building websites, but also providing photography and videography services. Thsi may be interesting for businesss that would also like to take photos of their staff.
Following that, to the right is a 'service', providing beatufil design features. And to the third 'service' is the development. All three services are accopmanied by icons to make them visually more appealing. 
<br>
Scrolling down is the 'pricing'-section, showing three tiers of service packages. Basic, plus and pro. Below these headings, the customer sees what services he gets, for what fee. Beneath the list of services, one can click on a button to initiate an order.
<br>
Lastly, below the 'pricing'-section, the customer will find a simple contact page, consisting of the 'official' brand name of the company and its address and contact details. 
![alt text](https://github.com/DenyTsjapanov/Project_1_Code_Institute/blob/master/assets/wireframes/Desktop-view.png?raw=true)
![alt text](https://github.com/DenyTsjapanov/Project_1_Code_Institute/blob/master/assets/wireframes/mobile-viewpng.png?raw=true)


<br>
## Technologies Used
### Front-end development
HTML:        Conent and structure of the website;
CSS:        Styles to the content;
Bootstrap:  Using Bootstrap was inevitsble, considering the need of beautiful style-frameworks and especially the layout;
Javascript: This was implemented by the Bootstrap CDN, and helped with the 'elapse-collapse' feature of the navigation panel when viewing the website on smaller devices.
Font-awesome: This was used for the addition of the icons in the 'services'-section. A similar thing was done during the "Rosie O'Donnel" project, which I found was quite visuall appealing.
Google Fonts: This was used for implementing fonts to the site.

### Software
VisualStudioCode:   During the course, we have been using GitPod. However, as much as I wanted to like it, I found it to be buggy and at times too frustrating. Thus, I switched to VSCode, which made life a bit easier. Installing Git and linking GitHub was quite a challenge, but it worked and thus Git and GitHub was sued for uploading the workspace anf version control.
GitHub:   Version control and publishing the website.

## Testing
Testing was done mainly manually. As I was writing code in VSCode, the index.html file was saved locally on my machine, and I opened the page to see the changes. If the changes I was meaning to implement turned out well, I then tried to "clean" the code. When usiong Bootstrap, I have come to some difficulties, namely in the styling. Often, as I would use a code from the Bootstrap framework, and would change the style of the code, the result would not be visible. Using Chrome's 'Inspect' feature to view the code in real-time, I came across a specific style from Bootstrap that often has an additional style to it, namel "!important". After trying to implement this addition to the style codes that did not work when simply adjusting the CSS of the Bootstrap framework, it worked. Thus, in the CSS you will see some styling is forced using this "!important" addition. I realise that this makes for a clutchered code, and I will try to fix this in future updates and projects. For the time being, I just went with 'what works'. 

## Deployment
Since I decided to leave GitPod, I fully commited to VSCode. I then installed Git (and Gitbash) to have version control working on VSCode. This isntallation made it easier than entering commands in the terminal. After installing Git and linking to my GitHub account, I was able to easily commit version to GitHub, with only one step remaining: git push. This I did through the terminal by simply adding "git push". After all changes where updated in my GitHub repo, I then decided to publish my website. This is done my going to the "Settings" section of my repo and scrolling down. NB. All repos created from VSCode directly were made private. I first had to make these public, prior to publishing the website.
<br>
To run the code locally, download the repo to your local machine, making sure that all files are present and accessible. Then run "index.html".

## Credits
Reuben Ferrante:     During the two short calls we had, Mr. Ferrante has been extremely supportive in helping me understand some of the matters I was have difficulties with.
<br>
Balsamiq:            A great little tool to create mockups for a website. The enclosed pictures are a result of their wireframes.
<br>
W3Schools:           W3Schools is a great way to find out answers to all questions related to HTML or CSS. Each time I was stuck, I was able to find a solution with their help.
<br>
Bootstrap:           Basically every design feature is thanks to Bootstrap. StartBootstrap is a great feature if you want to get some ideas for a website structure of design features. 

