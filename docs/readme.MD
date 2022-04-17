# Welcome to expense tracker project

## Purpose of this project
**edit by Mark**

## Team meeting notes

| Date Time | Meeting notes| Written by |
| ------ | ------ | -----: |
|mm-dd-yyyy | this is a demo notes | Yue|

## Brain storming Miro link
https://miro.com/app/board/uXjVOASlymM=/

## Tech Stack
 - Authentication: Firebase Auth 
 - Backend server (Python, Flask) Serena's Group
 - Frontend (React.js, Next.js) Mark Fang
 - Designing: Figma
 - Collaboration: Miro, and Discord
 - Hosting: Vercel for Frontend, AWS or Heroku as Backend 


## Requirements to be implemented


| No | Requirement | Raised by  |
| ------ | ------ | -----: |
|1| Support web browser notification which has different color and things (Frontend & Backend) | Henry|
|2|Support all history of purchases (Backend) |Andy + Mark (Frontend)|
|3|Support good UI for both mobile and computer devices (Frontend) |Mark + Andy|
|4| Able to set budget for certain time frames (Backend) | Serena + Henry (Frontend)|
|5| chart of amount of money through time (Frontend Chart.js) |Dante + Bryan| 
|6| Manage reoccuring subscription to things |Serena|
|7| MAKING THE API |Serena + with her group|
|7| Support multiple  currencies (Backend) |Andy|
|8| Website Structure and Styling (Homepage) |Alexander + Mark + Dante + Bryan|
|9| Sign/up Page |Henry|
|10| About Page |Alexander|
|11| Dashboard (Linking with the API) |Mark + Alexander|


## Details of each requirements

### 1. Support web browser notification which has different color and thing
This allows us to show notifs, and we can change colour by using css
https://www.w3schools.com/howto/howto_js_popup.asp nice artical about it

##How we are going to implement

when a user chooses to get notified, we store a binary number in a data base, then we run scripts on the database for the things that have been requested. For example, see if the bills have been payed each month, on the 20th, we would check the database to see if the user has done it, and if not, we send a notif.

There is also browser notifs requests, which is also required for them to show up on the desktop

### 2. Support all history of purchase
**A seperate tab/page for a complete list of all purchases, sorted by date**

### 3. Support good UI for both mobile and computer devices
**All UI should look clean for all devices, no bugs/glitches/weird formatting**

### 4. Able to set buget for certain time frames
**A counter somewhere on the page that shows (current spent)/(budget). When budget reached or surpassed a notification pops up in the middle of the screen warning the user of going over budget**

#### 5. chart of amount of money through time
**edit by Steven**

### 6. Manage reoccuring subscription to things
- When adding expense, have option to set a schedule for it (every Sunday, every month)
- Automatically add it every month
- Add a name to it (Netflix, Hulu, internet bill)
- Notification when it is due soon
- Connect to database

### 7. Support multiple  currencies
- Set base currency
- When adding expense, have an option to set currency and convert to base
- Connect to API to convert the currencies
- Display in table of all transactions what currency is
- In database, store the value in the base currency but have option to see how much it costed in other currency (not sure if this is good)


## Design noted here




