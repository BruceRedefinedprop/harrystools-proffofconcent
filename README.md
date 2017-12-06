 # Harry Tools Real Estate Modeling Website
 ## Milestone Project for User Centric Front End Development Module
 *****************************************************************************
 
 ### 1. Project Scope
 
    Harry's Tools is a proposed company whose product is software to enable the rapid creation
    of financial proformas for real estate projects.   The scope the project for is to develop the static front-end portion 
    of the Harry's Tools website.   The goal of the current website is to describe the features, pricing and 
    means to sign up for the service.  It includes stubs to enable anyone to reach Harry's Tools using 
    a contact form and for existing customers to sign in.  We hope the front-end provides an intuitive and visually 
    appealing overview  and entices customers to sign up. It's my intention to continue to buildout 
    this project as the course progresses.


### 2.  Structure

    a. index.html - is the home / landing page.  It highlights the major features and benefits and is targeted
       to an commercial real estate professional.    Note in the banner menu, the "features" button points back to the 
       home page and is currently a placeholder.  As our application backend is developed, and the detailed features 
       become clearer, this page will be created.  The basic page form with its top menu, callout and footer is used 
       throughout the site.   Note that picture changes per page, so try to guess the city in the background.  
       Also, the menu changes per page, dropping the reference to the current page.   User's can always go home by clicking
       the Harry Tools logo.  The logo was developed using a Google provided font.   
   
     b. pricing.html - provides a simple display for our pricing plans and button for sign up.  Each page's
        sign up button (in the Call-out) opens up the sign up page in a new tab.
    
     c. signup.html -  provides a template for accepting a customer's personal information.  This page 
        is  a stub with some live features for the purposes of the course such as the use of form validations to 
        ensure items like an email address is added in a proper format or ability to initiate a file loader to select 
        a personal profile picture.   It is assumed, that some point later in the course, this page will be modified 
        and built out to support a complete sign-up process including the necessary ecommerce elements.
    
     d. usecase.html - the use case page continues to use the basic template of a standard banner menu and page format seen on our 
        web pages and provides descriptive narratives of the platform targeted to specific customer segments.
        The one item that will be improved later is the email link on the bottom of page.  Currently, it uses a fictitious  
        email address info@harrytools.com and it is linked to the contact page.   When clicked, the contact opens in another tab.  
        In the future, I will open up an email form.
        
    e.  about.html - provide overview of Harry's Tools story.   This page is basically paragraph text added to our 
        template.  The one unique feature is link under "Useful Resources" opens up a youtube video.   This video
        was added for demonstration purpose only.  The video was selected more consistency with our theme than any
        endorsement of it's content.
       
    f.  contact.html - includes standard form with built-in validity checks.  The send button is included for
        demonstration purposes and it is a stub.
        
    g.  login.html - this form is also a stub and probably will be expanded as part of the future milestone project.        
    
    
 
### 3. Design Approach and Code Sources
  
    As mentioned by instructor for the Bootstrap module, it's a good thing to reuse code, that you have rights to reuse.
    To faciliate the develoment of this site, I used the code from the Bootstrap Whiskey demonstration.  I appreciated
    both the style and subject matter.

    a. Design Phase
    
        I used Basalmiq to create a mock ups, which were presented to and approved by my mentor. 
        While in Balamiq, I tested out links and background images, to get comfortable with the look and feel and site flow. 
        My focus group consisted of my wife and Jack, my pup, though Jack provided lousy advice.
        Also, I created the content prior to programming, such that I was able to cut and paste text, 
        as I built out the webpage.

    b. Programming 

        As first step, I  create a template which included a menu bar and logo, footer and 
        in general a call to action header.
        
        My first task was to modify the top of page bootstrap Navbar to reflect my color preferences and menu content.  
        The basic structure of the menu is from the Whisky example and is consistent with the sample code of 
        Bootstrap 3.3.7 documentation.  Then using the Bootstrap Navbar example from Bootstrap documentation, I created a simpler  
        menu for the footer.
        
        The picture based header is essentially  the callout code from the Whiskey example, modified for 
        appropriate images and content.
        
        For  the index and pricing plan pages, I used the template and added bootstrap thumbnail elements, using example
        code from the Bootstrap documentation.   I also used the Flaticon site to acquire icons included in the thumbnails.
        Images were acquired using Google image search and care was taken, where possible to find images from sources that did
        not look copywrite protected.
        
        The sign up page, was built using a Bootstrap template.  To make the relevant. I had to delete some 
        form-groups and modify the text for others.   This page will likely change in future projects to 
        reflect a more realistic sign up workflow.
        
        The contact page, used code from the resume mini-project.  Care was taken to add the necessary
        CSS elements while not creating referencing conflicts.
        
        The login page was built off the contact page, while using CSS reference documentation
        to help build out additional fields.
        
        The about page, used the basic template with language used to a link to youtube
        borrowed from the resume project's download a pdf language.
        
        In the CSS a media query was used so that index page call to action loaded up correctly on the iphone
        
   ### 4.  Deployment
    
        The deployment of the project relies soley on the Cloud9 platform.  At this point, it is not
        deployed to any live webserver.  
        
        Note that project from time-to-time was backed up  locally using git.  In order to 
        faciliate an initial review, the project was added to github at 
        https://github.com/BruceRedefinedprop/harrystools-proofofconcent and will continue to
        be udpated on the site.
        
   ### 5.  Testing
    
        My current test enviroment consists of:
        
            Apple Macbook Pro loaded with OS High Sierra v 10.13.1, Safari v 11.0.1, Chrome v 62.0.3202.94 (64 bit),
            Firefox v 57.0 64-bit.
            
            Apple IPhone 6 IOS 11.1.2
            
            Leveno Desktop 8V8TRS4 loaded with Windows 10 Home v 1709, MS Edge 41.16299.15.0, 
            Chrome  62.0.  3202.94 (Official Build) (64-bit)  Mozilla Firefox 57.0 (64 bit)
            
            Apple Ipad Pro
        
        To test the site I used the following procedure:
        
            a.  I developed the site on both my Macbook and Desktop and bounced between Safari and Chrome.
                First, I examined the site in desktop mode, to view the look and feel and verify
                all links.  When necessary I used Chrome and Safari developer tools help fix bugs
                and test out changes.
            
            b.  I opened up each browers on each device to test links and view look and feel.
                I shrunk Safari and Chrome browers on both the Mac and Windows Desktop to test
                website response.  (I still have an issue when chaning vertical height, that 
                I working to fix). 
                
            c.  I tested the smaller screen on my Iphone and Ipad (though Ipad pro is similar to the
                laptop).  To diagnose issue on the small screen, I used Chrome developers tool.
            
            d.  I used browserstack to spot check different OS versions for window and phones.   This test was
                was a spot check, my testing was focused on the index page since it's callout was the most 
                challenging for the smaller screens.  Spot checked other pages.  Did not test form or links, 
                I assumed those work in similar manner as in the primary testing platform.
        
    
    
  
 ********************************************************
 
 # Major Change Log
 --------------------
 
## Rev 0.1  Nov 29 2017
 
 Fixed firebox scroolbar issue - horizontal scroll bar on uses cases and index
   
   
   
 ## Dec 3, 2017 Update

    udpated the README.md to include markdown language syntax
 
 # Test Log
 
     The test log is being added for the benefit of my Code Institute indstructors
     so that they can verify my testing methodology / process
 
 
   ## a. Initial Review
   
    Tested on Windows 10 computer Google Chrome
        for look and feel   Examined margins and flow
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed
            
          
 
    Tested on Windows 10 computer MS Edge
        for look and feel   Examined margins and flow
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed
   
       Tested on Windows 10 computer Firefox
            for look and feel   Examined margins and flow
            tested links:
                Logo link - each page.  Expected goes back to home page - passed
                Tested top menu link for each page - passed
                Tested footer menu lines for each page - passed
                Tested sign up button for each page - passed
                tested about page youtube link - passed
                Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed
   
       Tested on MacBook computer Safari
        for look and feel   Examined margins and flow
        
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            tested sign in button for each page - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed
   
   
    Tested on MacBook computer Chrome
        for look and feel   Examined margins and flow
        
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            tested sign in button for each page - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed
            
            
    Tested on MacBook computer Firefox
         for look and feel   Examined margins and flow
        
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            tested sign in button for each page - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

        Tested Responsiveness
            view look and feel.  see that bootstrap breakpoints work, and scrollbars appear.
        
            Index page      - horizontal  Passed   , Veritical  Passed
            Pricing page    - horizontal  Passed   , Veritical  Passed
            usercase page   - horizontal  Passed   , Veritical  Passed
            About page      - horizontal  Passed   , Veritical  Passed
            Sign up page    - horizontal  Passed   , Veritical  Passed
            Log in page     - horizontal  Passed   , Veritical  Passed
            Contact page    - horizontal  Passed   , Veritical  Passed            
            
            
    Tested on MacBook computer Firefox
        for look and feel   Examined margins and flow
        
            
            
        
        tested links:
            Logo link - each page.  Expected goes back to home page - passed
            Tested top menu link for each page - passed
            Tested footer menu lines for each page - passed
            Tested sign up button for each page - passed
            tested about page youtube link - passed
            tested sign in button for each page - passed
            Tested hamburger menu icon (three bars) - passed
        
        Forms:
            Sign up page tested validations
            Sign up page tested validations, choose files

