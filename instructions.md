Welcome to your challenge,

You are tasked with creating a dummy react native application that showcases your ability to do mobile programming
using react and typescript. You will be creating two screens inside your application that are common inside of finance and crypto currency
applications: A keypad login and an asset list.

In this assignment you are free to use any technology that makes it simpler for you to complete the task in a timely manner.
Although you must use one of the latest versions of React Native (only hooks, no class components) and Typescript in your final solution. The solution
must also work on both IOS and Android and solutions which work well on both will be scored higher. Projects that also make use of typescript in a scalable
and well throughout manner will be also be scored higher. Please provide comments where necessary for anything that isn't trivial or requires explanation.
You should attempt to create a solution which is production ready, we would much prefer to see a finished and working simple app than an app which is complex
but has lots of bugs or out of scope features.

Screen 1

You are required to create a keypad screen that has:
 
- A page title should display 'bitvavo' above the notches
- buttons from 0-9 distributed out in a typical fashion (see example screenshot 1, no abc required etc)
- 4 notches (small circles) which change color dependent on entered value.
- A delete button
- A fingerprint button

Once a user enters the numbers 1337 they should be navigated to the asset list screen (screen 2) at all other times
the user should be presented with a popup that displays 'The code which was entered was incorrect!' and the login form reset.

Optional:

- Add an animation to the notches when a number is entered such as a jump or fill-in in animation.
- Provide a component test that covers the buttons being used.

Screen 2

You are required to present the user with an asset view list which displays the following:

- The cryptocurrency name
- It's current price

For this part of the assignment we expect you to use https://docs.bitvavo.com/#tag/General/paths/~1markets/get and https://docs.bitvavo.com/#tag/Subscriptions/paths/~1subscribeTicker/post Both of these use websockets and can be used to display the latest price in realtime. We've attached example 2 here which should be used as inspiration, don't worry
we're not expecting to see something as well put together and styled as the example, but it gives you an idea. 

Optional:

- Asset icons (you can use the ones returned from the coinmarketcap api)
- Change
- Market Identifier

The assignment should take no longer than three hours to complete without optional steps, though feel free to take as much time as you need to finish it.

If at any point during this assignment something is unclear or you get stuck please feel free to reach out and we will try our best to help you figure it out, good luck!

----

Once your happy with the work that you've done please can you make a public repository available and mail a link too liam@bitvavo.com, and we will be score and your assignment.
