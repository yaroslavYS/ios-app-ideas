
# _**1. Expense Tracker**_
**The required features of the app are:**

-   Display and compare total cost by day, month, year.
-   Show your invoices during the day.
-   Add a new invoice.
-   Show categories (including food, water bills, etc).
-   Show categories with used invoices (for collecting purpose).

**This expense management app works in the following way:**

First, in the ‘**Home**’ screen, you will see comparative charts which will help keep track and make comparisons of the current day’s expenses. Below the charts, a list will display all invoices you have paid that day.

Next, as you click the ‘**Add New**’ button, catalogs will appear. Clicking on each specific catalog will lead to the next screen where you can input the amount of money and give a description for that invoice.

When things are done, the app will automatically return to its home screen. By utilizing the  **Tabbar**  navigation, you can create 3 items:  **Home**,  **Activities**, and  **Setting**. Activities screen displays recorded bills in categories (for example, Food: 3 bills, Drink: 4 bills, etc). Clicking on a specific item to see the details.

‘**Setting**’ enables users to edit their information and images.

![enter image description here](https://www.iosapptemplates.com/wp-content/uploads/2019/08/Screen-Shot-2019-08-31-at-12.46.45-PM-600x523.png)

**So what can you apply?**  
**1. Chart View, Table View, Collection View**: With the infinite creativity of designers, you can apply knowledge of views to create impressive screens.  
**2. Tabbar Navigation and View Controller Navigation**.





# _**2. Recipes App**_

The idea of Recipes app is to help users have a collection of dishes and recipes they’d like to try. In addition, the app can also add the ingredients into their shopping cart. This is a very simple iOS app idea, extremely suitable for an iOS beginner.

**The required features of the app are:**

-   Show all dishes and recipes which the app has.
-   Show details of each dish, each recipe.
-   Add ingredients into the shopping cart enabling users to make quick payments.
-   Allow users to perform the payments.
-   Optional features: list of saved dishes, tracking your last payments, etc.

**The business logic:**

I guess after you read the 3 apps above, you can also imagine how this app works. You can use tabBar navigation controller or side-menu to help users navigate to the screen they wish. In general, we will have four sections:

In the ‘**Dashboard**’ screen (or  **Home**, whatever), this will show the top trending recipes. This is where you can unleash your creativity. You can use either a collection view or a table view or combine them as shown below. Of course, users can see the details of each recipe by tapping on that item.

The ‘**Detail**‘ page will show all the ingredients which users need to make their dishes. In this feature, this part can be updated by integrating to payment allowing them to be able to buy these ingredients. But this task needs a lot of things since you need to link/ co-operate with supermarkets or agents.

Tapping on the ‘**Add New**’ button will lead users to the screen where they can add a new favorite recipe. ‘**Setting**’ enables users to edit their information and avatars.
![enter image description here](https://www.iosapptemplates.com/wp-content/uploads/2019/08/Screen-Shot-2019-08-31-at-1.06.49-PM-600x575.png)

**What you can apply:**

1. Firebase/ GCD: In this section, you can create your own server. Use firebase might be a little bit different from the Restful API but the flow you communicate to the server is the same. You send requests and receive responses. The main thing is the way you handle them in the proper threads, avoid blocking UI or some weird behaviors.

2. Local Database: Nothing new but save data in your app.




# _**3. To-do list – Tracking task**_

**The must-have features:**

-   Keep track of tasks by days, weeks, months and years.
-   Calendars, for sure.
-   Local push notification.

**The business logic:**

From the key idea of this app, you can develop it into many versions to make differences. It could be tracking by process of the tasks, by group, by categories, by people.

After you have the percent, you can show, display these parameters in a various way. Let’s take a look at this following image, for instance. With the calendar, it will enable users to navigate to any dates to re-check or update tasks.
![enter image description here](https://www.iosapptemplates.com/wp-content/uploads/2019/09/Screen-Shot-2019-09-01-at-9.24.41-AM-600x586.png)

**Which knowledge we can apply here:**

-   Calendar: Instead of using an existing library, why don’t you create your own calendar? Try it and you will find out it’s not easy.
-   Retain cycle and life cycle of the view controller: Since this kind of app doesn’t need to use servers (actually it could), you can focus on the performance of the app. Whether it gets memory leaks, whether it has a bunch of view controllers having not been removed yet after every pushing.
-   Local push notification: it could be used for telling users updates.



# 4._**The Music/ Radio App**_

The last idea is streaming music collection and control music on iOS like Spotify. Yes, you can guess how it looks like. A table view with a bunch of songs and users can select any one of them and enjoy it! 

With  [these free APIs](https://blog.rapidapi.com/top-free-music-data-apis/), you can retrieve and save them in your database then show them in your UI. The way and the flow are the same as the ideas above. The only new thing is MediaPlayer library where you can play, next/ previous or stop songs.

Next, you can let users “like” or “share onto the social networks”. It is also a new thing you can learn. Let’s try it. You could be the next  [Spotify](https://apps.apple.com/us/app/spotify-discover-new-music/id324684580#?platform=iphone), like this

![enter image description here](https://www.iosapptemplates.com/wp-content/uploads/2019/09/Screen-Shot-2019-09-01-at-3.23.16-PM-768x391.png)
