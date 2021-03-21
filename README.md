[![Netlify Status](https://api.netlify.com/api/v1/badges/0224ad41-a8d3-40f6-8ec0-3c389d343f5b/deploy-status)](https://app.netlify.com/sites/jolly-clarke-cbd114/deploys)

# Frontend Mentor - Pod request access landing page solution

![Image of website on mobile, tablet, and laptop.](./assets/001-all-devices.png)

Hello! This is my first in a series of project challenges created by Frontend Mentor. This one is a simple landing page with a single email input. Pretty straightforward.

The original challenege can be found here: [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG).

## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "Oops! Please add your email"
  - The email is not formatted correctly should show "Oops! Please check your email"

## Links

- See it live on [Netlify](https://jolly-clarke-cbd114.netlify.app/)
- Play with the code on [CodeSandbox](https://codesandbox.io/s/001-fm-pod-landing-page-qy1k1)

## My process

I started by laying out the HTML structure, CSS classes, and basic styles for the mobile mockup. From there, I was able to add styles for the tablet and desktop mockups, refining my base mobile styles as I went. I really like this approach as a quick way to get going.

Instead of using JS for input validation, I opted for built-in validation provided by native HTML inputs using `required` and `type="email"`. I styled the error message according to the input state by using the `:invalid` pseudo-class. Using `visibility: hidden` instead of `display: none` for the error message prevented layout shift on state change. The element with `visibility: hidden` still exists in the DOM, unlike an element with the property `display: none`.

## Resources

- I used [Media Modifier](https://mediamodifier.com/) to create an image of my screenshots in different devices.
