# Online/Offline Budget Trackers

Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

- - -

### See Live Application
[Click Here](https://pwatrackmybudget.herokuapp.com//) to see the application.


### Installation


<!-- GETTING STARTED -->

This is some useful steps, you must meet to run this Express Application correctly 

### Prerequisites
You can use any code editor of user choise, i use Vs Code because it is open source and it understand git and do syntax highlighting very nicely.

* Go to
  [Click Here](https://code.visualstudio.com/download) to download Vs Code to your computer.
  

1. Clone the repo
   ```sh
   git clone https://github.com/lemanou7/pwaBudgetTracker
   ```
2. Get a linux shell emulator like Git bash or Powershell then:
    ```sh
    cd to where your repository folder is located in your computer
    ```
3. Install nodeJs on your machine


4. Install all the dependencies by entering this command in your Terminal and please add your database credentials(username, password and db name)
   ```sh
   npm install then npm start
   ```

4. Go in your web browser to see the App at specified port



### See Application Screenshots

1. Full App Main Page with 5 online entries 

![Home Page](./public/assets/images/pwa1.PNG)

2. Added 1 offline entry

![Home Page](./public/assets/images/pwa2.PNG)

3. The offline entry successfully sync to db when App went online

![Home Page](./public/assets/images/pwa3.PNG)


<!-- CONTACT -->
## Contact

Drissa Bagate (<span style="color:#5ddcf0">**Django, Javascript Full Stack Developer**</span>) [GitHub](https://github.com/lemanou7) - lemanou7@yahoo.fr

Other Project link: [My Blog Post Python-Django Implemation](http://grandbuzz.herokuapp.com/)

