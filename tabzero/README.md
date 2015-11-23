# TabZero Navigation Model

TabZero is a hub-and-spoke navigation model in which the Homescreen is the hub.


## What this prototype is (and is not)
* This prototype explains and illustrates one implementation of the new browser-based hub-and-spoke model. We're looking to learn where this model succeeds and where it may need to be modified.
* Motion and visual design are simplified so you can focus on the overall flow.
* Interface details are simplified - not all elements are visible in this prototype - so you can focus on the overall flow.
* For demonstration purposes, Tabs are color-coded so you can make a connection between the opened Tabs and their presence in the Tab Manager.
* The prototype includes a Status Bar. Depending on how you're viewing the prototype, you may see 2 of them stacked on each other.
* The protoype doesn't include the minimizing search bar - you'll have to imagine this.


## How you can help
* Provide thoughts, questions, or feedback in the [Open Issue][2].
* Focus on the overall userflow - don't get bogged down in motion or visual design - those will be addressed later.
* The [Open Issue][2] contains some specific questions from the UX team. Thank you in advance for any thoughts you may have about these. 


## How to run this prototype
Because this flow is complex, the prototype was made with Axure. Unfortunately Axure prototypes don't work well with Android or FxOS. If you don't have an iPhone, you can still run it on your desktop!

**If you have an iPhone:**
  * Send this URL to your phone - [http://ezoehunt.github.io/alopex-protos/tabzero/tabzero.html][3]
  * Open the URL in your browser (tested with Safari).
  * Add the URL to your homescreen.
  * Launch the prototype from your home screen.
  * Follow the <a href="#directions">directions</a> to navigate your way through the prototype.

**If you do not have an iPhone:** 
  * Open the URL on your desktop.
  * Resize the window to fit the prototype screen (320x570).
  * Click to tap; click-and-drag to swipe; long-click to long-press.
  * Follow the <a href="#directions">directions</a> to navigate your way through the prototype. 


## <a name="directions"></a>Navigating through the prototype

#### Getting started
1. Launch (or open or reload) the prototype.
2. Unlock your phone by swiping up on the Firefox logo.


#### Your first Browser Tab - the Homescreen
1. Check out your Homescreen. This is your **first Browser Tab.** Scroll up and down to see your content.
2. Swipe down from the Status Bar to see your **notifications.** (notifications only works on the Homescreen in the prototype.)
3. Close your notifications - tap the Home icon or swipe up from the bottom of Notifications (directly above the darker Navigation Bar at the bottom of the screen).
4. Swipe up from the dark Navigation Bar at the bottom of the screen to see the **Tab Manager.** Since you haven't opened anything else yet, your Homescreen is the only thing in the Tab Manager right now. The Homescreen is always present in the Tab Manager at the top. 
5. Close the Tab Manager by tapping the Home icon.
6. *The Home icon works throughout this prototype to take you back to the Homescreen.*


#### Opening content from the Homescreen

Any content launched from the Homescreen opens in a new Browser Tab. Here you'll open a news site and the Email app/webapp.

1. Vox Technology

  * On your Homescreen, tap the Vox Tech icon **to launch a new Browser Tab for Vox Tech.**
  * Tap the 1st article about Google's self-driving car. 
  * Notice that "<" arrow is enabled now. Within a Browser Tab, you can navigate forward and backwards in that Tab's history. Try it out!

2. Email

  * Navigate to your Homescreen, and tap the Email icon **to launch a new Browser Tab for Email.**
  * Tap the first message about West Elm. The "<" arrow is now enabled so you can navigate between the Inbox and the West Elm message within this Browser Tab.

3. Now open the Tab Manager (swipe up from the Navigation Bar). 

  * The most recently viewed Browser Tab is displayed beneath the always present Homescreen Tab.
  * The Browser Tabs update their titles and images depending on which page of the Browser Tab you last viewed. So if you last viewed the West Elm email message, the title of that Browser Tab says "Email West Elm" and the image is of the West Elm message. Try it out by navigating back and forth and then checking the Tab Manager.

4. Things you can do in the Tab Manager:
  
  * Tap a Browser Tab to bring that Browser Tab into focus. Try it out!
  * Swipe right to delete a Browser Tab. Note that the Homescreen Tab cannot be deleted. Try it out!
  * Before going to the next section, delete the Vox and Email Tabs from your Tab Manager.


#### Creating new Browser Tabs

New Browser Tabs are created from multiple touchpoints. Here you'll open new Browser Tabs from the Tab Manager, from the Homescreen grid, and from inside an app/webapp/site.

1. from Tab Manager

  * Open the Tab Manager. 
  * Tap the "+" icon **to launch a New Tab.** Since this is a new Browser Tab, the back/forward navigation is disabled until you navigate forward from this page.
  * The New Tab will contain suggestions for users - content TBD.
  * Open the Tab Manager again, and you'll see the New Tab there.

2. from the Homescreen grid

  * On your Homescreen, long-press on the CNN Entertain icon **to launch a new Browser Tab for CNN Entertainment.**
  * Tap the first article about Pixar. You'll see the active "<" arrow so you can navigate between the main CNN Entertainment page and the Pixar article within this Browser Tab.
  * Open the Tab Manager again to see the newly added CNN Entertainment Tab.

3. from inside an app/webapp/site

  * If you're not already on it, navigate to the main CNN Entertainment page.
  * Scroll past the Pixar article and long-press on the "Adele impersonates herself" article **to launch a new Browser Tab for this article.** Since this is a new Browser Tab, the back/forward navigation is disabled until you navigate forward from this page.
  * Try it out with the Email app/webapp! Navigate to the Email Inbox screen. Then long-press the "compose email" icon in the upper right corner **to launch a new Browser Tab for Compose Email.** 


#### Searching

You can search from multiple touchpoints. Here you'll search from the Homescreen, from inside an app/webapp/site, and from the New Tab.

1. from the Homescreen

  * On your Homescreen, tap the search field at the top of the screen (where it says "Homescreen").
  * Close the search screen by tapping the "close" link in the upper right corner.
  *  Now open it again, and tap the search field at the top of the keyboard screen. 
  * Select the first result ("new york news") **to launch a new Browser Tab for this search result.**
  * Tap the first article about NYC schools to go to that article. Again you'll see the "<" arrow is enabled to allow you to go back to the search results and choose a different link. 
  * On the Yahoo search results page, you could also long-press any link to open it in a new Browser Tab (not hooked up in this prototype).

2. from inside an app/webapp/site

  * Open your Tab Manager, and tap the Email Compose Tab.
  * If Email Compose is not in your Tab Manager, tap the Email icon on your Homescreen. Then long-press the "compose email" icon in the upper right corner.
  * Tap the search field at the top of the screen (where it says "Email Compose").
  * Now tap the search field at the top of the keyboard.
  * Select the first result (juicy turkey allrecipes) **to launch a new Browser Tab for this result.**
  * Note: Because you arrived at Allrecipes from the Email Compose screen, the "<" arrow is enabled so you can go back and forth between these 2 pages.

3. from the New Tab

  * Open the Tab Manager, and tap the "+" icon **to launch a New Tab.**
  * Tap the search field at the top of the screen (where it says "New Tab").
  * Now tap the search field at the top of the keyboard screen.
  * Select the first result (san francisco weather) **to launch a new Browser Tab for this result.**
  * Note: Because you arrived at Yahoo Search Results from the New Tab screen, the "<" arrow is enabled so you can go back and forth within this Browser Tab.



[2]: linkgoeshere
[3]: http://ezoehunt.github.io/alopex-protos/tabzero/tabzero.html
