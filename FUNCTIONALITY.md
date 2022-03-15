# Table of Contents

[Header](#header)

[Footer](#footer)

[Home page](#home-page-hero-section-button)

[About page](#about-page-how-we-started-and-what-else-we-do-section)

[Items page](#items-page-menu-buttons-contact-box)

[Contact page](#contact-page-contact-form)

[Success and 404 page](#success-page-and-404-page)

[404 page](#404-page)

<br>

## Header

| Device | Input             | Expected result        | Actual result          | Test result |
| :----: | :----------------: | :---------------------: | :---------------------: | :---------: |
| Mobile | Click ≡      | Open the menu          | Open the menu          |    Pass     |
| Mobile | Click ⨉      | Close the menu         | Close the menu         |    Pass     |
|  All   | Click the logo        | Go to the Home page    | Go to the Home page    |    Pass     |
|  All   | Click __Home__    | Go to the Home page    | Go to the Home page    |    Pass     |
|  All   | Click __About__  | Go to the About page   | Go to the About page   |    Pass     |
|  All   | Click __Items__   | Go to the Items page   | Go to the Items page   |    Pass     |
|  All   | Click __Contact__ | Go to the Contact page | Go to the Contact page |    Pass     |

[Back To **Table of Contents**](#table-of-contents)

<br>

## Footer

| Device | Input                  | Expected result               | Actual result                   | Test result |
| :----: | :---------------------: | :----------------------------: | :------------------------------: | :---------: |
|  All   | Click the _Discord_ icon   | Open _Discord_ in a new tab   | Open _Discord_ in a new tab  |    Pass     |
|  All   | Click the _Facebook_ icon  | Open _Facebook_ in a new tab  | Open _Facebook_ in a new tab\*  |    Pass     |
|  All   | Click the _Instagram_ icon | Open _Instagram_ in a new tab | Open _Instagram_ in a new tab\* |    Pass     |
|  All   | Click the _Twitter_ icon   | Open _Twitter_ in a new tab   | Open _Twitter_ in a new tab\*   |    Pass     |

\*On iOS, the application opens instead of opening the respective web page in a new tab.

[Back To **Table of Contents**](#table-of-contents)

<br>

## Home page: Hero section button

| Device | Input                | Expected result      | Actual result        | Test result |
| :----: | :-------------------: | :-------------------: | :-------------------: | :---------: |
|  All   | Click the __VIEW ITEMS__ button | Go to the Items page | Go to the Items page |    Pass     |

[Back To **Table of Contents**](#table-of-contents)

<br>

## About page: How we started and What else we do section

| Device | Input                | Expected result        | Actual result          | Test result |
| :----: | :-------------------: | :---------------------: | :---------------------: | :---------: |
|  All   | Click the __VIEW ITEMS__ button | Go to the Items page   | Go to the Items page   |    Pass     |
|  All   | Click the __CONTACT US__ button | Go to the Contact page | Go to the Contact page |    Pass     |

[Back To **Table of Contents**](#table-of-contents)

<br>

## Items page: Menu buttons, Contact box

| Device | Input                     | Expected result             | Actual result               | Test result |
| :----: | :------------------------: | :--------------------------: | :--------------------------: | :---------: |
|  All   | Click the __Sell__ button     | Go to the Sell section          | Go to the Sell section          |    Pass     |
|  All   | Click the __Buy__ button      | Go to the Buy section           | Go to the Buy section           |    Pass     |
|  All   | Click the __Giveaway__ button | Go to the Giveaway section      | Go to the Giveaway section      |    Pass     |
|  All   | Click the _Discord_ icon      | Open _Discord_ in a new tab | Open _Discord_ in a new tab |    Pass     |

[Back To **Table of Contents**](#table-of-contents)

<br>

## Contact page: Contact form

Click the __SEND MESSAGE__ button with/without inputting anything in the required fields(Message and Checkbox for the privacy policy)

  | Device | Input                                         | Expected result        | Actual result                                             | Test result |
  | :----: | :--------------------------------------------: | :---------------------: | :--------------------------------------------------------: | :---------: |
  |  All   | Without a message and the checkbox unchecked  | Show an error message  | Show an error message below the message field\*           |    Pass     |
  |  All   | with a message and the checkbox unchecked | Show an error message  | Show an error message below/beside the checkbox input\*\* |    Pass     |
  |  All   | with a message and the checkbox checked       | Go to the Success page | Go to the Success page                                    |    Pass     |

\*Error messages on Safari iOS and macOS: "Fill out this field" / on Chrome: "Please fill in this field."

\*\*Error messages on Safari iOS: "Select this tick..." / Safari macOS: "Select this tickbox" / Chrome Android: "Please tick this box if you want to proceed." / Chrome Windows: “Please check this box if you want to proceed."

[Back To **Table of Contents**](#table-of-contents)

<br>

## Success page and 404 page

| Device | Input                         | Expected result     | Actual result       | Test result |
| :----: | :----------------------------: | :------------------: | :------------------: | :---------: |
|  All   | Click the __GO TO THE HOME PAGE__ button | Go to the Home page | Go to the Home page |    Pass     |

[Back To **Table of Contents**](#table-of-contents)

<br>

## 404 page

| Device | Input                         | Expected result    | Actual result      | Test result |
| :----: | :----------------------------: | :-----------------: | :-----------------: | :---------: |
|  All   | User input invalid URL at https://sejungkwak.github.io/trading-paradise/ | Go to the 404 page | Go to the 404 page |    Pass     |

[Back To **Table of Contents**](#table-of-contents)
