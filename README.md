# Challenge 2: Sample Application Portfolio

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

HTML Structure:
For this assignment, I wanted to make sure that the "foundation" of my page was created before I put in personal information. I created my HTML file firt. I utilized Lorem Ipsum to fill in title and text. I focused on organization of semantic elements. Following this, I chose classifications for sections that would be styled differently. 

CSS Structure:
Once my HTML document was organized, I begain working on polishing in my CSS file. I turned my attention to color coordination and font combinations. I realized quickly this was unwise, and restarted. I prioritized styling the layout of my webpage. I worked from the top down, structuring the header first, and working sequentially through to the footer. Upon reflection, I would likely structure the footer and header at the same time due to their similarities. I am a marvel fan, so I used photos of female marvel characters to provide me a visual of the layout. This would prove problematic, and I will address this further down the document. I chose to structure my document using the dimension of a cell phone.

Responsive Layout:
Before styling, I then worked on my responsive layout. I had several issues with this. Because I had put pictures in that were not cohesive in size, the portfolio did not look neat. My code was also too messy to find where to make changes. Therefore, I restarted my code for a second time. I sized images so that they shared the same dimensions. Once I had those in place, I put borders around different sections. This helped me to visualize what elements and classes were being edited. I decided to copy the attributes that would need to be resized in response to screen sizes and copied those into a media query. I then edited those to fit a screen larger that 720 px to stack the application links differently. 

Polishing:
I did minimum polishing. I used relative and absolute positioning to make headers lie ontop of images. I also made it so that the font color changed images that were on screens that were more than 720 px wide. This was done because the text was too dark ontop of the images. 

Application Links:
I originally linked my website to the Blackwidow Image. However, because I had used a z-index of -1, the link was lost. To correct this, I add the link to the entire section classified as "first-applicaiton"


![Hailey Hughes Portfolio (1)](https://user-images.githubusercontent.com/127250721/229609468-00206eb2-63f8-4c3a-a71d-8b0b2dcb3faf.gif)



