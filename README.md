# Southern Tool Supply

STS is intended for the B2B commercial buyer market in the manufacturing sector. A large portion of the role requires the intended user to
 juggle multiple sources that generally do not have an online presence to obtain all the parts
and supplies needed to keep their produciton lines running. STS attempts to fill this void by providing the user the ability to research, connect, and appraise STS online.
 
## UX

The site is intended for the b2b commericial purchaser, this role is typically rewarded for streamlining the process to obtain and keep the needed materials on-site. The problem being the incredibly niche
market causes a lack of healthy competition and lack of an online presence for most know vendors. This site will allow the customer to get prompt access to support, sales and customer service teams to resolve
any issue they may have. 

as an end user, i would like to have easy to access information so that i dont have to call everytime i need something. 

as a mangager, i would like to see my supply network, so that i can get a clear picture of the efficiency of my team.

as a small business owner, needing to look hard for supplies takes away time from other tasks, id like that to be streamlined to make my job easier.

## Wireframe

links/images from Balsamic go here.


## Features



### Existing Features

Feature 1: Mailing list: the mailing list is a simple but effective tool to keep users informed and increase site traction

Feature 2: about section: provides a background of the company using a headshot of the owner and a value statement to foster a sense of trust and familiarity with the user.

Feature 3: Contact form: provides an easy way for the customer to get in touch for any issue or request for information that they have. 



### Features Left to Implement
- An online catalog to provide some of the less technical parts in an easy to read format

- an employee directory to provide specific contact info the customer is trying to find

-a login page that saves the user's info and streamlines the buying process

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

[HTML](https://html.com)
    - the project uses **HTML** to layout information in a meaningful way that can be read by a browser

[CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - the project uses **CSS** to add color and effect to HTML

[BootStrap](https://getbootstrap.com/)
    - The project uses **BootStrap** to simplify mobile responsiveness

[JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. go to contact form postion of page 

    2. Try to submit the empty form and verify that an error message about the required fields appears

2. Navbar:
    1. check that each location on the navbar functions as expected

    2. ensure that the nav postions are far enough apart to merit their own tag

3. Value statement:
    1. on resize value section text overlaps on to owner picture

    2. eliminated section on displays smaller than medium to save on small screen realestate

4. Jumbotron:

    1. text overflow on displays smaller than 400px

    2. @media query to change font size to allow for smaller displays

##automated testing##

www.w3.org was used to verify the integrity of both HTML and CSS 

##Screen responsiveness##

on displays smaller than 400px the jumbotron heading changes font sizes to prevent text overflow

on displays smaller than medium to owner picture and value statement disappear to save on screen realestate and simplify the site


##notes of interest##

figuring out the jumbotron issue was challenging due to finding the right method of resising the header to keep the text from spilling out, i noticed in the chrome dev tools that the
natural font size for the h1 header is 2.5rem and ended going with that. 

the owner pic and value statment kept running over eachother due to not having an image fluid attribute to the owner pic, CSS-tricks led me to the solution

## Deployment

starting with previews and testing from GitPod ports and moving to GitHub pages,
filenames had to be changed

the code remains on the masterbranch

to display the site locally, download the project from the host on github and laundch index.html with your preferred
internet browser. While ensuring to maintain the original file structure to keep the links functional.




## Credits

a lot of time was spent between StackOverflow and w3schools for troubleshooting and they were essential to solving issues

https://css-tricks.com/ - this is an AWESOME resource for obscure CSS questions and is more explanatory that StackOverflow






### Content
- The text for the value statement was copied from the L.L. Bean and modified some to fit the feel of the site.

### Media
owner pic, callout image, and diamond plate background are from a  free use image site called [PixBay](www.pixbay.com)

warehouse image pulled from this article at  [Shopify](https://www.shopify.com/enterprise/international-warehouses-ecommerce-guide)

order template came from [SmartSheets](www.smartsheets.com) 

### Acknowledgements

-Matt Rudge for the WhiskeyDrop website, without it this would have been much more difficult

-the PeerCodeReview on slack provided me with a lot of examples of what the MS1 project should look like and helped me come up with my own ideas


