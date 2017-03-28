# DNN App Tutorial Angular 4: Hello DNN

This is a trivial hello-world in DNN using Angular 4.

## Using / Testing this App
To give it a test-ride, you'll need 

1. DNN (the web platform thingy)
2. 2sxc (the app-engine & CMS)
3. This app from the releases section

Once you've installed DNN, follow [these instructions on how to install an app](http://2sxc.org/en/install-2sxc-app-package) in case you've never done it before. 

## How to edit it for experimenting
There's some stuff you should know, but in case you only want to mess around a bit, here's what you should do:

1. Get the [latest node.js / npm](https://nodejs.org/en/)
2. Install the Angular CLI by running `npm install -g @angular/cli` _or_ following these [instructions](https://angular.io/docs/ts/latest/cli-quickstart.html)
3. Make a change to the app, like changing the "Hello DNN!" text in the `/src/app/app.component.ts`
4. Rebuild it for production using `ng build --prod --aot --output-hashing=none`

This last build will compile everything using AOT and place it with clear file names in the `/dist` folder.

Enjoy!!!
