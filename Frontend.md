Primary Functionality  
----------------------


- [ ] **1. Create page structure and essential UI**
  1. [ ] “Home” page
    1. [ ] Top nav. bar (2 icons) - settings icon on left and search icon on right (Settings icon linked to “settings”        page)
    2. [ ] Bottom tab bar (5 icons) - home, explore, create post, messages, profile. (Each icon on the tab bar are            linked to their respective pages)
  2. [ ] “Explore” page
    1. [ ] Top nav. bar (1 icon) - search icon on right (no link yet)
    2. [ ] Scope bar (3 tabs) - “subscribed,” “popular,” and “discover.”
    3. [ ] Bottom tab bar (5 icons) - Home, explore, create post, messages, profile.
  3. [ ] “Create post” page
    1. [ ] Top nav. Bar (2 icons) – back button on left and “next” button on right (back linked to “home” page/ “next”        button linked to “pick category page”)
    2. [ ] Text fields (2) – Title and description
    3. [ ] button for photo upload
  4. [ ] “Pick category” page (linked from “create post” page)
    1. [ ] Top nav. Bar (2 icons)- back button on left and post button on right 
    2. [ ] Back button returns user to “create post” page 
    3. [ ]	Post button returns user to “home page”
  5. [ ] “Messages” page
    1. [ ] Top nav. Bar (1 icon) – compose button on right (no link yet)
    2. [ ]	Bottom tab bar (5 icons) - Home, explore, create post, messages, profile.
  6. [ ] “Profile” page
    1. [ ]Bottom tab bar (5 icons) - Home, explore, create post, messages, profile.
  7. [ ] “Settings” page
    1. [ ] Top nav. Bar (1 icon) – back button on right (link to home page)

2. [ ] **2. Evaluate the best options to use as backend. Once set up, create fields for the following**
  1. [ ] User accounts- detailed in backend doc. 
  2. [ ] Posts- detailed in backend doc

3. [ ] **3. Allow users to post content to the “home” page**
  1. [ ] Enable users to input content into text fields on the “create post” page and upload/take* photo. 
  2. [ ] Add function to back button- pressing this will delete any content entered in the “create post” page
  3. [ ] Add functions to the “next” button. 
    1. [ ] Pressing the button will temporarily save the entered content and open the “pick category” page.
  4. [ ] Create blank category link. Pressing this will enable the user to continue and press the “post button.” Since     the categories have not been set up yet this will remain blank for now. This is to simulate the user choosing a        category
  5. [ ] Add function to “post button”
    1. [ ] Pressing the post button will add a new entity to the post field in the database and save the appropriate          metadata and the temporarily saved.
    2. [ ] Pressing the post button will display the post’s content onto the “home” page.  
    3. [ ] Pressing the post button will return the user to the “home page.”

4. [ ] **4. Structure post content (doesn’t have to be pretty for now)**
  1. [ ] The only content displayed on the “home” page for each post will be the 
    1. [ ] Username
    2. [ ] Title 
    3. [ ] Category- blank or comment out for now, details below
    4. [ ] Picture
    5. [ ] Time posted
    6. [ ] Location- comment out for now, details below
  2. [ ] Create link areas over each post displayed on the “home” page. Pressing a post will open up a new page             displaying that entire post’s content (which includes the description).

5. [ ] **5. Set up User Authentication**
  1. [ ] Allow users to create accounts with a username and password.  Account information stored and pulled from           backend.
  2. [ ] User is remembered when restarting application
  3. [ ] Create link under settings which allows user to log out

6. [ ] **6. Geolocation** 
  1. [ ] Enable application to track user location 
  2. [ ] Incorporate location into posts and post metadata
    1. [ ] When a user creates a post, the application will record that user’s current location and place it into that        post’s metadata.
    2. [ ] On the post view on the “home” page, this info will be displayed by the distance between the user and where        the post was created.
  3. [ ] Restrict view of posts on “home” page to a certain distance. Users will only be able to view posts within a        certain distance
  4. [ ] Create popup on launch that confirms that the application can track location
  5. [ ] *Under settings, create a slide bar which will allow the user to manipulate the radius. This could potentially      be placed under secondary.  Since the initial number of posts will be small it might be useless in the beginning        to provide this function.
  6. [ ] ot a priority but) add distance from user as one of the criteria displayed in a post

7. [ ] **7. Categories**
  1. [ ] Set up category data fields in database
  2. [ ] Add list of categories to the “choose category” page. This page will pull list from database
  3. [ ] Add category label to viewable criteria for each post on “home” page (preferable alongside username)
  4. [ ] Add category list to “explore” page. Opening this page will pull list from database.
    1. [ ] Each listed category on the “explore” page has a toggle button which enables/disables the category from the        user’s frontpage
    2. [ ] Posts only from the categories which have been toggled on can be viewed on the frontpage
    3. [ ] For now the scope bar will remain deactivated or we can remove it for now. The category list will remain           unfiltered for now. 
  5. [ ] Pressing an individual category on the “explore” page will allow user to view posts from only that category.

8. [ ] **8. Messaging**
  1. [ ] Create reply button on each post page which allows a user to instantly message the user
  2. [ ] This creates a thread under the messaging page available through the icon in the tool bar. 

9. [ ] **9.	Comments**
  1. [ ] Create comment thread for each post
  2. [ ] Display comment thread below description on the post page.

10. [ ]	**10. User profile**
  1. [ ] Saved posts
  2. [ ] Post history

Secondary functionality (in no specific order)
----------------------------------------------

11.	[ ] **11. Voting system for each post/comment**
12.	[ ] **12. Contacts**
13.	[ ] **13. Push notifications**
13. [ ]	**14. Create search function**
14.	[ ] **15. Fine tune category search, organization, creation.** 


