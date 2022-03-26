# todolist-webapp
A todo list web app using Python, SQLite, and Flask. This was created in the summer of 2020.

Luminous is your companion to live a happier life, by allowing you to stay on top of all of your tasks, events, and emotions you encounter on a daily basis. This is done through the three features of journaling app, todo list, and a mood tracker. The simplicity and beauty of the design will allow for a pleasurable experience while using it, but more detail of that will be in “Design.md”.
This app is still intended to be compiled and configured on the CS50IDE, and should be used through a tablet, laptop, or a PC. Please use chrome to startup this webapp. No additional installations will be needed. The web app is very intuitive in its use. Here are the steps while in use, along with tips for navigating through the page, if any.

1. Opening the web app - You will first be greeted on a welcome page, where you can either register for an account or login with an existing username and password. You will be prompted with messages for invalid inputs either in the login or register page. Every page starting from the next one will have a “back” button to direct you to the previous page.
2. After logging in, you will be redirected to your homepage. In the personalized homepage, you have your todo list showing all of the complete todos and incomplete todos, separate. Checking incomplete todos will migrate the todo to “complete todos”, and vice versa. You can delete any todo at any time. Atop that will be a text-box to add a new “todo” on the incomplete todos. The add button is disabled if nothing is typed.
   Above that will be buttons for either accessing your journal or your mood tracker.
3. Clicking on the “Open Journal” button will direct you to a page to view all of your journal entries. Each new entry is stacked at the top of the page, and they are in descending order by the created time and date. Each entry is a card that shows the title, selected mood in the entry, and the time stamp when the journal entry was created. You can delete any entry from here.
   Above the journal entries will be a button to create a new journal entry template.
4. After clicking the “Add a new entry” button you will get a fresh template to create a brand new journal entry. Creating a journal entry is easy. Write the title, choose a mood emoji corresponding to your current mood using a slider under “How are you feeling today?”, write some text and click save on the bottom of the page. You will then be redirected back to the journal entries page, with your most recent journal entry at the top. Clicking “back” will not add the journal entry.
5. Opening an already existing journal entry can be done by clicking anywhere on the specific journal entry’s card. The journal entry will be rendered on the page along with the timestamp when it was created. You can either read or edit the entry here. Clicking “Save Edited Entry” will only edit the changed components. Clicking “back” will not change anything, and will take you back to the journal entries page.
   This concludes all of the parts in the user’s journal.
6. Finally from the homepage, we can access the mood tracker that will be personalized to you. Because you choose a mood emoji in each journal entry, the mood tracker will show the average mood value and mood emoji for each day on a bar graph. Though this page is solely for looking at the average moods of each day, identifying how your mood changes over a few days can allow space to find improvements to better your mood.
   The higher the value, the happier the emoji gets, and this is reflected on the bar chart. If interested, specific average mood values from 0 to 120 can be seen as well.
