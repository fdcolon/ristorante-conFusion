# Ristorante Con Fusion

**Ristorante Con Fusion** is a project requested by **Coursera** in order to get the certification as **Front-End Web Development with React** ([View Certificate](https://www.coursera.org/account/accomplishments/verify/JXUERW9DMAYR)). It is focused in develop a responsive website that contains a `Home` page, an `About Us` section, the `Restaurante Menu` and a `Contact Us` section.

## Objective
It is requested to update the web application to get data from the server to render the information corresponding to the leadership team of the company. In addition, handle the submission of the feedback form by posting the feedback to the server.

## Assignment Requirements

**Task 1**  
Update the `Redux` actions and the `Home` and `About` components to use the data from the server for rendering the leader information.

**Task 2**  
Enable the saving of the feedback data submitted using the feedback form in the `Contact` component. You will save the feedback form data submitted by the user to the server.

**Task 3**  
Use simple animation using `react-animation-components` to enable a staggered rendering of the list of leaders in `About` component.

## Review Criteria

**Task 1**
  * Appropriate action types and action creators have been added.
  * The `Home` component is correctly using the leader data, and handling any errors that might arise.
  * The `About` component is correctly using the leader data, and handling any errors that might arise.

**Task 2**
  * A new `postFeedback()` action creator is correctly implemented to post the feedback data to the server.
  * The `Contact` component has been correctly updated to use `postFeedback()` to post the form data to the server.

**Task 3**
  * Appropriate animation has been added to stagger the rendering of the leaders in the `About` component.

## Installation

Clone the GitHub repository and use `yarn` to install the dependencies.

```
> git clone https://github.com/fdcolon/ristorante-conFusion.git
> cd ristorante-conFusion
> yarn install 
```

> :warning: If you don't have `yarn` installed in your computer, please type the following in your terminal:

```
> npm install --global yarn
```

## Usage

To run the **Ristorante Con Fusion** website you will need use two terminals:

  1. For the server.
  2. For the UI environment.

### Running the Server (Terminal 1).
```
> yarn run server
```

### Running the UI environment (Terminal 2).
```
> yarn start
```

### Home

Once the app is running, the first view it the **Home** page where you will find a logo, a navigation bar, and a `Login` button.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/home-web-01.png)  
**Figure 1** - Home Page (web view)

This website is responsive, so if you try it in a mobile device or if you use the `Chrome Developer Tools` to emulate a mobile device, you will see how it looks.

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/home-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/home-mobile-02.png" height="400">

**Figure 2** - Home Page (mobile view)

> :warning: In the mobile version, you need to tap on the hamburguer icon (**☰**) to display/hide the navigation menu.

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/home-mobile-03.png" height="400">

**Figure 3** - Home Page - Navigation menu (mobile view)

### About Us

This section contains a bief history of the restaurante, some facts and the Corporate Leadership (all this info is fake data).

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/about-us-web-01.png)  
**Figure 4** - About Us (web view)

For the mobile version, the view will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/about-us-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/about-us-mobile-02.png" height="400">

**Figure 5** - About Us (mobile view)

### Menu

This section contains the restaurante menu (4 dishes). To see the dish details and comments, you can click/tap on any of the four displayed dishes.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/menu-web-01.png)  
**Figure 6** - Menu (web view)

For the mobile version, the view will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/menu-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/menu-mobile-02.png" height="400">

**Figure 7** - Menu (mobile view)

### Dish Details

When you click/tap on a dish, it will display the dish details and comments given to that particular dish.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/menu-details-web-01.png)  
**Figure 8** - Dish Details (web view)

For the mobile version, the view will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/menu-details-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/menu-details-mobile-02.png" height="400">

**Figure 9** - Dish Details (mobile view)

### Submitting Comments to a Dish

If you would like to add a comment to a dish, you click/tap on the `Submit Comment` button to open the corresponding form. First, rate the dish.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/submit-comments-web-01.png)  
**Figure 10** - Submit Comments - Selecting rate (web view)

Next, fill the form and click on the `Submit` button.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/submit-comments-web-01.png)  
**Figure 11** - Submit Comments - Filling form (web view)

Finally, look for the added comment at the end of the **Comments** list.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/submit-comments-web-01.png)  
**Figure 12** - Submit Comments - Comment added (web view)

For the mobile version, the views will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/submit-comments-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/submit-comments-mobile-02.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/submit-comments-mobile-03.png" height="400">

**Figure 13** - Submit Comments (mobile view)

> :warning: To go back to the `Menu` section, just click/tap on the `Menu` link located into the `breadcrumbs` section.

### Contact Us

This section contains some fake info for contacting the restaurant and a feedback form.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/contact-us-web-01.png)  
**Figure 14** - Contact Us (web view)

For the mobile version, the views will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/contact-us-mobile-01.png" height="400">
<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/contact-us-mobile-02.png" height="400">

**Figure 15** - Contact Us (mobile view)

If you would like to submit a feedback, just fill the `Feedback` form and click on the `Send Feedback` button.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/contact-us-web-02.png)  
**Figure 16** - Contact Us - Filling Feedback Form (web view)

For the mobile version, the view will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/contact-us-mobile-03.png" height="400">

**Figure 17** - Contact Us - Filling Feedback Form (mobile view)

Once you click/tap on the `Send Feedback` button, it will be displayed an `Alert Box` with the information you provided.

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/contact-us-web-03.png" width="300">

**Figure 18** - Contact Us - Alert Box

### Login

This section was developed only testing how to handle the data, but it is not used to login into the website.

![](https://github.com/fdcolon/ristorante-conFusion/blob/main/public/login-web-01.png)  
**Figure 19** - Login (web view)

For the mobile version, the view will look as following:

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/login-mobile-01.png" height="400">

**Figure 20** - Login (mobile view)

If you provide an email and a password and click/tap on the `Login` button, it will be displayed an `Alert Box` with the information you provided.

<img src="https://github.com/fdcolon/ristorante-conFusion/blob/main/public/screenshots/login-web-02.png" width="300">

**Figure 21** - Login - Alert Box


## Notes

- To check the feedback you submit, you can open the `db.json` file located at the `ristorante-conFusion/json-server/public` folder. Look for the `feedback` property and look for the last items. Your feedback should be there.

## License

This App is Copyright © 2021 Fernando Daniel Colon Gonzalez and thoughtbot. It is free software, and may be redistributed under the terms specified in the [LICENSE](https://github.com/fdcolon/ristorante-conFusion/blob/main/LICENSE) file.