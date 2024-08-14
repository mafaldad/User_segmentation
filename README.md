# User_segmentation
Mobile applications: Users segmentation based on behavior.

This project, with the potential to significantly impact our user experience and engagement, aims to analyze users' actions in the application to define groups that differ in product metrics (retention rate, time spent in the application, frequency of event occurrence, conversion on the target event, contacts_show `).

Throughout the project, we will:

- Carry out exploratory data analysis
- Segments users based on the events they complete
- Test statistical hypotheses
-Formulate and test a hypothesis about the difference in conversion in contact information views between those who downloaded the app from `Bing` and those who downloaded it from `Google`.
- Formulate a statistical hypothesis about the dataset data and test it.

**Data Description**

The datasets contain data about events in the Trash to Treasure mobile app, where users post ads to sell things they no longer need.

The data corresponds to those who took their first actions in the application after October 7, 2019.

`mobile_dataset_us.csv` contains the following columns:

- `event.time`: when the event took place
- `event.name`
- `user.id`

`mobile_sources_us.csv` contains the following columns:

- `userId`: user ID
- `source`: the source from which the user downloaded the application

Event details:

- `advert_open`: open an advertising post
- `photos_show`: see photos in the ad
- `tips_show`:  the user was shown recommended ads
- `tips_click`: the user clicked on a recommended ad
- `contacts_show` and `show_contacts`: the user clicked the "show phone number" button in the ad
- `contacts_call`: the user dialed the announcement number
- `map`: the user opened the map of the published ads
- `search_1` - `search_7`: various events related to website search
- `favorites_add`: the user added the ad to favorites
