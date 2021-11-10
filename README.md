# CreatorMediaClub
This is a project that I plan on having 1.0 released and depolyed for public consumption by 4th Quarter 2022  

The idea is for Creators and Influencers to use this to interact with their communities in a different way than just through their normal routes of content, I plan on supporting the basic types of media out there albulms, movies, art and books (including comics/graphic novels and manga). At launch I dont plan on having any major monetization effort outside of user donation, though I have ideas for ways for this to be monetized if user and communities response is good enough.  

Inspiration came from [this video](https://www.youtube.com/watch?v=yh9Evgt6ZBg) from Jacksepticeye because in it he reviewed dune the  movie and compared it to the book and it struck me as a potential for fan engagement to create book clubs then my idea expanded to all forms of media.

## The packaged releases for deployment
Coming Soon

### documentation on how to install/deploy

#### The Back end
Arguably the most important part and there are two main ways to do it:
Way One:
* pull the code to a local machine that has a JVM and Maven or an ide that can run java programs
* build and run
* if you want the jar then it will be in the build folder

Way Two: 
* download the jar from releases and run via jvm
  * the command is ```java -jar $PathTOJar\CreatorMediaClub.jar```

__ If you are trying to test out before release then it is imperitive to to the function of the apps to have this running on a network local machine __

#### iOS
Sideloading on apple is not a recomended move at the moment so for iOS users you must wait for the app Store beta which might come around the same time the 1.0 for android. Though if you can't wait [here](https://searchmobilecomputing.techtarget.com/opinion/Did-you-know-how-easy-it-is-to-sideload-iOS-apps-to-your-iPhone)
is an article from that describes how to and why you may wat to just wait.

#### Android
Android instalation there are two ways:  
Way One:  
* pull source code build in your choice of ide, I use Android Studio
* build and run on external device the app will then be downloaded to the device
  
Way Two:  
* download release apk on to the device you wish to install the app
* fiddle with your security settings to allow third party apps, described [here](https://www.howtogeek.com/313433/how-to-sideload-apps-on-android/)
  * beware that it may be slightly different depending age and type of phone you have
* Install the app and it should work

### Web

Just wait until there is a hosted site

## Source Code for all the components
the iOS App is [here](https://github.com/CaKellum/CreatorMediaClubs_iOS) using swift with Cocoapods  
the Backend is [here](https://github.com/CaKellum/CreatorMediaClubs_BackEnd) using JavaSpring with Maven  
the Android is [here](https://github.com/CaKellum/CreatorMediaClubs_Android)  using kotlin & JetPack with Gradle  
the WebApp is [here](https://github.com/CaKellum/CreatorMediaClubs_Web) using Python/Django  

## How to Contribute

If you would like to contribute please fork and open a pullrequest  
Most of the code Guidelines will be taken care of by the linters,  
but make sure to:
* have easily understandable variable names
* that there are no runtime errors
* no unhandeled error, unlesss in testing
* all functions have properly formatted comments

and when you make a pull request please leave a Comment/Note on what the improvement you are making,   
be descriptive and verbose  
__I Will deny any PRs with no or subpar notation__

## If you like this and Want to see more
Considering dontating to these organizations that will support the next generation:
- [Code.org](https://donate.code.org/campaign/support-computer-science-education/c172233)
- [Black Girls Code](https://www.blackgirlscode.com/donate/)
- [SMASH](https://www.smash.org/?form=donate)
- [Girls Who Code homepage](https://girlswhocode.com/) and donte [here](https://www.classy.org/give/77372/#!/donation/checkout)
- [Scratch Foundation](https://secure.donationpay.org/scratchfoundation/)
- [First](https://www.firstinspires.org/donate?utm_source=first-inspires&utm_medium=donate-button&utm_campaign=donation)
- there are many more that are more in need of money than I so please before you give me money really consider giving money to any charity

or if you want to be my benefactor to see more of specifically my stuff [paypal me](https://paypal.me/cakethecook4353?country.x=US&locale.x=en_US) because money makes it easier to do things which you might like

