# Novel-19

## Summary

Novel-19 is designed to assist users in being aware of their surroundings and flattening the curve of the novel coronavirus strain.  Users can log notes with geocoordinates concerning locations they have visited, where they have seen hard-to-find-food items, and anything else that may be useful to the general public.  When a user tests positive, they can update their status on the app and the map will show the placs they have visited within the past two weeks in red.  Then other users can cross-check these red pins with lcoations they have visited within the past two weeks to determine whether or not they feel it necessary to also take a two-week quarantine.

## Deployed App

This app can be accessed [here](https://novel-19.herokuapp.com/).  Simply navigate to the link.  You can then create a user login and begin making your local communtiy a safer place.

## Technologies Used

- Express

- Handlebars

- D3

- Leaflet

- Passport

- Sequelize

## Screenshot

![app screenshot](/public/assets/images/Screenshot.png)

## Future Updates

Here are a few features we hope to implement soon:

1.  We want to notify users who have saved notes at the same location as another user who has tested positive.  This will increase the ease of use for all users.

2.  We want to add categories for the notes so that the map will be color-coordinated by type of note.  Then, map filtering options will allow users to choose between what they wish too see.

3. As the app scales, we will need to load only portions of the map pins, so as to not slow down server response time.

4. The stats page will need to be scaled down so as to be mobile-friendly.