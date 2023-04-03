

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

# Semantic HTML Elements:
I replaced all div tags in order to make the HTML document easier to navigate. I utilized the header, hgroup, h1, h2, h3 and section elements. I have left comments in the HTML document to note where changes were made, what those changes are and why I chose to make them.

HTML element structure:
I viewed this project as 4 distinct parts; the header, the footer, the main content and the aside. I organized the elements with the heading first and footer last. In the heading I organized I used the h1 element as it was the first heading to appear. Within this I included the nav element in which I put the ul. Before the pirmary content I added a section dedicated to the largest image. I did this to emphaize that the image stood alone apart from the header and the content, and consequently easier to find in the HTML file. Within the section whose class is content I used the hgroup element to provide clarity that there were three sperate sections within. I used the same organization structure for each hgroup; img, h2 and p. I used h2 for each hgroup because all needed to be identical in styling. I chose to put the main content above the aside. The main content contains the most information regarding the company, and the aside contains information that is tangential. I once again used hgroups to organize the three sections in the aside. Each hgroup in the asside used the same organization structure; h3, img and p, for the same purposed as the hgroup with the main content. The footer came last. It is of notes that i used the h2 element in order to ensure continuity in formating with the main content.

alt attributes:
Alt attributes were added to increase web accessiblity. Descriptions were chosen using the context of the content it related to, as well as a visual description.
