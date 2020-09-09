# K2 US TS Repo

A common place for all K2 tips, tricks and components. We currently have 6 categories defined in which assets are categorized. There is also some getting started documentation to cover areas of interest and how-to documentation. 

Each app or component  has its own repo in order for us to version them individually. Whenever a reference is made directly to a component hosted here, the best practice is to link directly to the version you are building against. This approach will prevent us from running into issues if later versions of the component introduce breaking changes.

# Categories
Here's how the assets are broken down:

## [Apps](#apps)
All the completed apps, immersified or standard, will be categorized as such.


## [Common Components](#common-components)
Used for all those reusable views, forms and scripts that we can simply drag and drop onto the canvas, set a view values and have it do its thing. 

## [CSS Files](https://k2-us-ts.github.io/Documentation/categories/css)
Here we store any custom CSS we created. There are some generic ones in the root, but we can also create specific themes and group them together in sub-categories.

## [Images](https://k2-us-ts.github.io/Documentation/categories/images)
List of images we can reuse. They can be linked directly from GitHub or saved to your repository of choice. There will only be a single repo for all images, with folders to separate these by theme, icon set, etc.

## [JavaScript Files](https://k2-us-ts.github.io/Documentation/categories/js)
Reusable scripts for common actions like animation, control behavior and so on. The idea here is to have a bunch in the root, with more specific scripts in sub folders. These files will also be versioned as a single unit. The key differentiator between having a script here vs common components is that if the script renders something new, it's probably a component. If it alters behavior of existing controls or actions, it belongs here.

JavaScript files cannot be linked directly from the GitHub repo, it has cross site scripting prevention headers, we need to proxy it through something in order to have them served correctly in SmartForms. There is a nice little site that does that for us, details are in the *JavaScript Files* form.

## [JavaScript Service Provider (JSSP) Components](https://k2-us-ts.github.io/Documentation/categories/jssp)
For all the custom components we create for the JSSP. Each will have its own repo and version. Each component will also need to be documented thoroughly to ensure ease of use.


# Apps
NOTE: The apps have not been ported over yet. The links below do not work. Ping the team if you have an app request.

## [Parts Ordering](https://www.google.com)


# Common Components

## [Address Lookup - Google](https://github.com/K2-US-TS/Address-Lookup---Google)
This component allows one to lookup addresses using the Google Maps APIs. Because it uses autocomplete to best guess addresses as you type, it doesn't make sense to have this as a service instance. This implementation is using JavaScript on a reusable view, with only some simple setup needed from the developer's side to get this going


# CSS
These are generally stand-alone. Some key files are:
- TBD1
- TBD2

