# Sunshineandsprouts
Sunshine and Sprouts Web App

Goal: Create a web app from idea to final product to create
a better Client experience, automate tasks, and increase revenue. 



 

Company Background: 
2 Locations – Cascades, Broadlands

Cascades Location has 12 children, 1 Owner, 1 Full-Time Assistant

Broadlands Location has 2 children, 1 Owner.
Both address information is on the www.sunshineandsproutsdaycare.com
website.

Features 



Dashboard, Main PageAdmin Page (Daycare owner/assistant screen)On My Way ButtonUser ProfileSocial Media LoginSecure User LoginTimelineCalendarMessengerClick to Call Phone ButtonClick to Email ButtonChild Reports













 

On My Way Button
– This button is the main reason why this
app was initially created. When parents arrive to drop off or pick up their
children, sometimes they have to wait outside and I’ve heard them knocking up
to 10 minutes waiting for the door. This can be at 7am or 4:30pm. 

Use Users GPS coordinates and an opensource Maps Library
(Javascript for ex), and use the coordinates of the Daycare location and send
the Daycare Owner/Assistant, an up to the minute ETA of the child’s
parent.  And even a special alert when
they are less than 5 mins away or less than a mile away. 

 

 

User Profile –
User profile’s will show information about the each Child. Both Parents can
download separate apps but have them both synced to the same Child Profile. And
in the even of comments or updated changes made, our App will recognize which
parent made the change under their Child’s profile and that information can be
displayed, if those settings are wanted. But as far as programming goes, the
code should be able to distinguish between both Parent’s separate phones. 

There will also be information about the child. BirthdayAllergiesMedication InfoCurrent Weight/Height (We will provide our own data analytics graph reports at
the end of each month)ADD!! More FeaturesNote: We will create a database that holds *ALL* of the information of the Child, whether it is displayed in the Web App, is up to us and the Parents. But we may use that information for other Applications in the future. Some of these informations may be, if the child has younger siblings that could come under the care of the daycare, future prospects angle. And etc, we will keep adding to this last before creating the database.Timeline = This screen will work similar to Facebook and Instagram by showing the Parent's a live feed of what is happening with their child. The content that would appear would be if the child ate, peed, pooped, danced, images, any other important information deemed important by the Parent or the Daycare owner. Because we need the "live-feed" feature, I believe Node.js would be our best bet to accomplish that. Definitely opened to further research. Calendar - Basic Calendar Feature. The internet probably has 'pre-code' Calendar apps in whatever framework or library we use. Django had a 'out-of-the-box' Calendar page, minor tweaks was needed beside installation of it. The Calendar Feature will be meant for Parent's to update information for the Owner/Assistants to know. If they won't be attending a specific day or if the child's family is going on vacation for a week. Also the parent's can put in the Calendar when a child has a Dr's appointment. We will create Basic Options for the Calendar to have, out of the box. Like a parent will have the automatic option of choosing, Dr Appts, Vacation, Sick, etc. We'll create more features as we find out which are the most prominent to use. Also, the Owner/Assistants can be able to input events in the calendars about special events, ex: Halloween, Christmas Parties, specific children's birthdays (It'd be nice if this was automatically inputted by use the database info of each child, this is why we want to collect as much info on the child and then we'll find out the best ways to deliver it when that information is needed) 
Messenger - This feature is meant to solve a communication problem between the Parents of the child and Owner & Assistant. Sometimes the child wakes up early or was too fussy to fall asleep the previous night which effects the normal mood of the child. This kind of information is important for both the Owner & Assistant to know at 'real-time'. Again, I believe Node.js will work well for this. Because this Messenger feature is such a popular feature, we may find it 'out-of-the-box' under some Node library. And we just tweak it to our needs and take full control of the Graphic Designing.   Social Media Login - This allow Parent's to login with their Facebook, Twitter, Google+, etc. This makes it easier for Parents to login and not have to remember another password.    Secure Login - In Django, this was made sure by the 'out-of-the-box' Login I used, it was written with security in mind. Let's do research on any out of the box frameworks or libraries we use, and make sure that these methods have security implemented in already, which it should.   Dashboard - This is the main screen, after a Parent logs in. This is will display the main buttons. The next step is to begin brainstorming what buttons will make it to this screen, the goal is *simplicity*. When you get a custom suit, its never bigger or more than it should be, its exact fit. That same mentality is what we are carrying here. Not a button more, and not a button less then what we need. Admin Page - This is gonna be a fun part. We need to focus on creating an *awesome*, *amazing* admin page. This is a heavy part that we can sell to other Owners. This is a very "business" type of programming. There are awesome admin GUI templates that look amazing, I've been looking forward to creating my own Admin page. Other business's will definitely appreciate how well we execute this part because it directly connects to their User Experience of the app. In I want the store owner to feel like he got an xbox 360 when he was 16 but for his business. In the Admin page, the Owner side will be able to add New Child Client, it will be a GUI representation of their Database, well graphically designed. They will be able to make updates, see growth graphs of the children because we will be measuring their height and weight. I will add a new section that will have Admin page Templates. They kick ass.Child Report Section - This is the daily report of the child in an easy to read fashion. It will be say when the child went to the bathroom, ate, slept, and activities. These are important information for the parent to have each day. I want the Owner/Asst/Admin side of the app to easy input these child "events" and just press a button and it automatically takes the time unless they manually change it and the button icon images will coincide  with the event, such as a bottle icon for infant feeding time. Also, Parents should be able to download this Child Report in a pdf form and sent to their email or download directly to their phone. Our database should hold up to 2-4 weeks of child reports. These are small text files, they should not occupy a lot of memory space. I will add the current paper version that the Daycare Owner or Assistant manually fill out each day. This will automate that process. This section is just a basic Form, reading information from a database and displaying it in the same format in HTML/CSS.  One Click Phone Call Button - One line of code in the HTML file, very simple. One Click E-mail Button - One line of code in the HTML file, very simple.   
