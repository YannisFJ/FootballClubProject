# CSS Wanderers FC 

Milestone Project 1: User-Centric Frontend Development 

The website I have created is for a fictional football team, which I have named CSS Wanderers FC. Throughout development, the site went through different iterations but always stuck to the same basic principle – to provide relevant content for existing and potential fans. 
Consequently, news, tickets, and video highlights were among the more important priorities.

 
## Demo
 
A live demo will be found in this section

## UX

From a UX/UI perspective, I wanted to easily satisfy the users specific goals whilst having a visually appealing design. The final layout followed the premise of my original wireframe, but I decided to cut out certain features (e.g. the ‘player rating’ carousel) for the sake of a cleaner and simpler site.

The website is for two different types of users:

1. Existing fans are primarily concerned with news updates, highlights and how to obtain tickets. As such, the most prominent feature when entering the site is a responsive jumbotron that outlines important club news. Furthermore, because users’ eyes are typically drawn to the top left of the screen, I included ‘news’, ‘tickets’ and ‘highlights’ closest to the top left of the navigation bar. This way, people can very quickly identify ways to access the specific content they have come for.

My project also helps existing fans achieve their goals by clearly outlining the sites key features in the navbar, outside of a dropdown menu (above 768px). I picked this approach so that users who come to the site for a specific purpose (like wanting to quickly buy tickets) could instantly identify the relevant place to click.

Each section of the site is also clearly labelled with typography that I believe is very well suited to the site. Due to my chosen colour scheme, it is also very clear when exiting one section and entering another. This helps users clearly identify where they are.

2. I wanted new users to receive a brief overview of the club’s history and opportunities such as stadium tours or venue hire. This way, they would understand the clubs’ ethos and what we can do for them. In the ‘Membership & Events’ section, I provided an attractive-looking and simple overview of the services on offer.

Each button, if clicked on, will load a separate tab that has the relevant service.
Additionally, potential fans might also be interested in casually buying tickets. This is why I designed the ‘tickets’ section to have all upcoming matches, coupled with the date of each one immediately available. This means the interested users can quickly ascertain which match would be best for their schedule. 

Some user stories:

•	As an existing fan, I want to effortlessly find the latest news on my team.

•	As an existing fan, I want to be directed to where I can seamlessly find ticket information, to determine if I can attend.

•	As a potential fan, I want to learn more about this club.

•	As a potential fan, I want to know what else the club has to offer besides football.

•	As a potential fan, does this club have any social media accounts?

•	As a potential fan, is there a newsletter I can use to find updates?

Side note:
The final colour scheme (gold and dark grey) was a custom design that I thought worked really well. Early in the design process, I decided to make my navbar a ‘navbar-inverse’ (turning it dark grey) for the sake of differentiating my site. I then realised that gold contrasts fantastically with this shade of grey and decided to make these my club colours – creating a modern feel that is reminiscent of teams like Watford and Borussia Dortmund. 

Wireframes link:
https://github.com/YannisFJ/milestone-project/tree/master/wireframes

### Technologies Used

1. HTML5 – used to write my site: https://www.w3.org/html/

2. CSS – used to customise my site and make it responsive: https://www.w3.org/Style/CSS/

3. Bootstrap (3.3.7) – used for great features and modern look. Carousel, thumbnails, scrollSpy and modals were made possible: https://getbootstrap.com/docs/3.3/css/


### Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

## Existing Features

•	Scroll behaviour – I used the CSS ‘scroll-behaviour’ property to implement smooth scrolling for users when they click a section on the navbar.

•	ScrollSpy – I used Bootstraps’ ScrollSpy feature to make it even clearer to the user which section of the website they’re on.

•	Hover – Utilised an aesthetic hover effect for list items on the navbar and footer.

•	Modals – Used modals that are triggered by the ‘search’ button and ‘subscribe’ button, making it clear to the user what the next steps are.

•	Carousel – The carousel in the news section was used to make a better landing page.

•	Responsive text – certain text (e.g. footer and club history) is very responsive. This was to conserve more screen real-estate on smaller devices. For example, the footer says, ‘Follow CSS Wanderers’ on mobile, but ‘Follow CSS Wanderers on social media!’ on larger devices. 

•	_blank Links – All button links open a different tab.

## Features Left to Implement

For my next project I am excited to add more functional features, such as the possibility of ‘sign in’ and ‘sign up’ buttons. I initially included them in this project, but I removed them to promote a more simple design.

## Testing

The existing and “potential” fan user stories achieved my intended outcome of providing easy access to tickets, highlights, news and showcasing the history of the club. In the carousel section, they can read (and click on) all the latest headlines, regardless of device. If they are viewing on mobile, then the background will be the club’s famous gold colour scheme. If viewed on desktop, this section has a nice background of a football pitch. 

Users are also able to find social media links by clicking on the icons in either the navbar (top right) or footer. All links to social media change colour when hovered on. This essentially acts as feedback to let the user know that the link is functional. Furthermore, I used “target=_blank” for all links.

Users are also able to easily catch up on video highlights, which I have tested thoroughly. During development, there was a problem that meant videos wouldn’t show up on smaller devices. I later realised this was due to my own inline-styling and rectified the problem. Now, videos can play on any resolution. Here is an image of all 4 videos being played simultaneously (not that any sane person would do this:

They are able to learn the history of the club in the ‘club history’ section and can click on a link that will take them to learn more. 

If you try to submit an invalid email address in the ‘subscription’ section, there will be an error noting the invalid email address. 

By clicking on the links in the navbar, the ScrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested across several browsers, including Chrome, FireFox and Safari. I also tested it on iPhone 5, 8 Plus, Samsung Note 9 and iPad pro.

# Bugs:

Through testing, I discovered a few problems. There were only two that I haven’t yet addressed:

•	The smooth scrolling effect did not work on Safari

•	In the subscription section, if you don’t enter a correct value (email address) then there will be an error message. However, the bug is that the ‘confirmation’ modal will still appear if you click the button. 

Examples of testing process:

1.	Video Highlights:
Click ‘Video Highlights’ on the navbar >	After being taken to the highlights section, click on a video at all the different breakpoints and browsers >	Try the same thing in landscape mode

2.	Tickets
Click ‘Tickets; on the navbar > After being taken to the tickets section, see if the ticket information is still consistent on the different breakpoints and browsers > Check the links still open a different tab > See if the images fail to load on different browsers.

## Deployment

The CSS Wanderers website is hosted on GitHub pages, deployed directly from the master branch. As such, it will automatically update if there are new commits to the aformentioned branch. If you want to run the site locally, you can clone this repository directly into an editor by pasting git clone https://github.com/YannisFJ/milestone-project.git into your terminal.

## Credits

### Content
All content, unless otherwise stated is written by me. In addition to composing the code, I created a fictional backstory for the football club in the ‘Club History’ section and made a fake fixture list.

### Media
The photos used in this site were obtained from Pexels and Unsplash.

The videos in the ‘video highlights’ section are from YouTube.

### Acknowledgements

•	During my initial research, I looked a sites for numerous football teams, including Barcelona FC, Arsenal, Spurs, Manchester United, Manchester City, AS Monaco, Inter Milan and others I’m sure I’ve forgotten! These sites helped me ascertain what is most important to new visitors on a football website.

•	I used the Bootstrap website extensively to understand the different possibilities. This is what introduced me to carousel and thumbnails.

•	The CSS code to make a ‘flexible’ video (class=”flex-video”) within the thumbnail was found on Stack Overflow and is appropriately labelled in my code.

•	The slightly convoluted code used to accurately give my Instagram icon a suitable background was also found online, though I can’t remember exactly where. 
