# Galaxy11-Preorder
Landing page for Samsung Galaxy S20 Pre Booking

## Description
This is the code respository for the Samsung Galaxy S20 Pre Booking Landing Page. It is being designed with static HTML resources, CSS and JS. Project is using CodeKit application to build and compile the code based on the Foundation Responsive Design Framework.

Please run `npm install` to download and install the necessary build node package dependencies. CodeKit is setup to push the completed static web files into the `/build/` folder.

## Deployment
To deploy to server, please copy across the contents of only the `/build/` folder. Can exclude the `scss` and `yarn.lock` folder from deployment assets as well. Please exclude the contents of the `checkout` folder inside the `build` folder as well - they are just for testing purpopes.

### Bundling the JS files
Originally, external 3rd party JS libraries were being directly referenced from `node_modules` directory. Workflow has no change on external libs that are not being customized. However, has a big effect on Foundation framework JS. We've made sure to only include the JS that is necessary to the project and we have minified it and put it inside the `build/js` folder.

### Checkout process
Currently the "Call to Action" buttons are linked to a demo checkout process, based on a previous campaign for iPhone 11. These pages are for mockup purposes only. They will need to be created on the server location booking.truecorp.co.th with updated content from TRUE/Samsung. Please disregard the contents of this folder for live deployment - THEY ARE FOR DEMO ONLY!

### Google Tag Manager
The GTM container code is currently commented out in the HTML. When deploying to server, ensure that GTM scripts are activated so that we can track user interactions.