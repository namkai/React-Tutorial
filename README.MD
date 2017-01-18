React Weather Tutorial

This react weather tutorial will show students how to build their own weather app. The app will allow the user to type in a city name and see the current weather in that city.

Part 1 :

-Give a brief introduction about React and the benefits of using React.
-Start by having them download a boiler plate from my github for them to use.
-Will explain boiler a bit but won't go in depth in this Tutorial.
-I'll explain what Webpack and Babel are and why they are fundamental in using React.

Part 2:

-In this section we will build the skeleton of our project.
        Skeleton components:
            -Nav
            -App
            -Weather
                -WeatherForm
                -WeatherMessage

-I'll introduce the students to Components and teach them the difference between your main component and child components.
-I'll explain the particulars about how we render different components and the possible bugs that can occur when attempting this.
-I'll have students download the React developer tools which is a great tool to help with debugging.

Part 3:

-Teach students how to render all the neccessary components to the screen.
-Introduce students to the Open Weather API and the the package Axios which is how they are going to make their AJAX requests.
-Show students how they can parse through the JSON data
-Design the skeleton of the Weather Component which has 2 child components.
---WeatherForm which sends the AJAX requests.
---WeatherMessage which displays the weather to the page.

Part 4:
-Flesh out the WeatherComponent and its child components.
-Explain what state is and how we can pass state down to child components.
-Explain how to change state and why we must never do the following unless we are building the state in the constructor
    this.state = {'new state'}
    must always be
    this.setState({'new state'})

Part 5:
-Weather app should almost be complete
-Add some styling to the page.
-Have a review session explaining what each component does and how it functions within the whole applicaton.
