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
|1 | Support web browser notification which has different color and things (Frontend & Backend) | Henry|
|2|Support all history of purchases (Backend) |Andy + Mark (Frontend)|
|3|Support good UI for both mobile and computer devices (Frontend) |Mark|
|4| Able to set budget for certain time frames (Backend) | Serena + Henry (Frontend)|
|5| chart of amount of money through time (Frontend Chart.js) |Dante| 
|6| Manage reoccuring subscription to things |Serena|
|7| Support multiple  currencies (Backend) |Andy|

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

#### 6. Manage reoccuring subscription to things
**edit by Serena**

### 7. Support multiple  currencies
**edit by Serena**


## Design noted here




