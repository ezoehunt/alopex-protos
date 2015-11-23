# TabZero Navigation Model

TabZero is a hub-and-spoke navigation model in which the Homescreen is the hub. [See this visualization][1].


## What this prototype is (and is not)
* This prototype explains and illustrates one implementation of the new browser-based hub-and-spoke model. We're looking to learn where this model succeeds and where it may need to be modified.
* Motion and visual design are simplified so you can focus on the overall flow.
* Interface details are simplified - not all elements are visible in this prototype - so you can focus on the overall flow.
* For demonstration purposes, Tabs are color-coded so you can make a connection between the opened Tabs and their presence in the Tab Manager.
* The prototype includes a Status Bar, so you'll see 2 of them stacked on each other.
* The protoype doesn't include the minimizing search bar - you'll have to imagine this.


## How you can help
* Provide thoughts or feedback in the [Open Issue][2].
* Focus on the overall userflow - don't get bogged down in motion or visual design - those will be addressed later.
* The [Open Issue][2] contains some specific questions from the UX team. Thank you in advance for any thoughts you may have about these. 


## How to run this prototype
Because this flow is complex, the prototype was made with Axure. Unfortunately Axure prototypes don't work well with Android or FxOS. If you don't have an iPhone, you can still run it on your desktop!

**If you have an iPhone:**
  * Send this URL to your phone - [http://ezoehunt.github.io/alopex-protos/tabzero/start_1.html][3]
  * Open the URL in your browser (tested with Safari).
  * Add the URL to your homescreen.
  * Launch the prototype from your home screen.
  * Follow the <a href="#directions">directions</a> to navigate your way through the prototype.

**If you do not have an iPhone:** 
  * Open the URL on your desktop.
  * Resize the window to fit the prototype screen (320x570).
  * Click to tap; click-and-drag to swipe.
  * Follow the <a href="#directions">directions</a> to navigate your way through the prototype. 


## <a name="directions"></a>Navigating through the prototype

#### Getting started
1. Launch (or open or reload) the prototype.
2. Unlock your phone by swiping up on the Firefox logo.


#### Your first Tab - the Homescreen
1. Check out your Homescreen. This is your *first browser Tab.* Scroll up and down to see your content.
2. Swipe down from the Status Bar to see your *notificiations.* (notifications only works on the Homescreen in the prototype.)
3. Close your notifications - tap the Home icon or swipe up from the bottom of Notifications (directly above the darker Navigation Bar at the bottom of the screen).
4. Swipe up from the dark Navigation Bar at the bottom of the screen to see the *Tab Manager.* Since you haven't opened anything else yet, your Homescreen is the only thing in the Tab Manager right now. The Homescreen is always present in the Tab Manager at the the top. 
5. Close the Tab Manager by tapping the Home icon.
6. The Home icon works throughout this prototype to take you back to the Homescreen.


#### Creating new Tabs from the Homescreen
Everything launched from the Homescreen opens in a new tab. Next you'll open a news site and the Email app/webapp.
1. Vox Technology
  * On your Homescreen, tap the Vox Tech icon **to launch a new Tab for Vox Tech.**
  * Tap the 1st article about Google's self-driving car. Notice that "<" arrow is enabled so you can return to the main Vox Technology page. You can go back and forth between these 2 pages with the arrows.
2. Email
  * On your Homescreen, tap the Email icon **to launch a new Tab for Email.**
  * Tap the first message about West Elm. The "<" arrow is now enabled so you can navigate between the Inbox and the West Elm message.
3. Now open the Tab Manager (swipe up from the Navigation Bar). 
  * The most recently viewed tab (should be Email) is displayed beneath the always present Homescreen Tab.
  * The Tabs update their titles and images depending on which page of the Tab you last viewed. So if you last viewed the West Elm email message, the title of that Tab says "Email West Elm" and the image is of the West Elm message. Try it out by navigating back and forth and then checking the Tab Manager.
  * In the Tab Manager, you tap a Tab to bring that Tab into focus. Try it out!
  * In the Tab Manager, you swipe right to delete a tab. Try it out! Note that the Homescreen Tab cannot be deleted. 


#### Creating new Tabs from the Tab Manager
1. You're just remembered that you need to reply to a friend's email. Inside the Tab Manager, tap the Home icon in the Navigation Bar.
2. Now tap the Email icon to **launch a new Tab for Email.** To reply to your friend's email, you'd use the tools and navigation built into Email.
3. You want to do some more surfing, but want to do that in a new Tab so you don't lose the history in your existing Tabs (Vox Technology and Email). So open the Tab Manager and tap the "+" icon in the Navigation Bar.
This is the new Tab screen. The content here may change, but the goal is to provide some inspiration as well as search functionality. If you choose one of the icons or if you perform a search, that page will load in this Tab.
4. If you open the Tab Manager again, you'll see that there's a new item called "New Tab." As soon as you choose an item or perform a search on the New Tab screen, the title+image of the New Tab will change to match your selection.




[1]: visualization
[2]: open issues
[3]: http://ezoehunt.github.io/alopex-protos/tabzero/start_1.html
[4]: directions

