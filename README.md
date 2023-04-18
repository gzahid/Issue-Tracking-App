# Issue-Tracking-App
## Description:
This app tracks issues using local browser storage.

### Features: 
- SCSS is available. 
- Run ````sh yarn install ``` to setup SCSS 
- Run yarn ```sh sass:dev ``` to execute and recreate CSS


## Issues: 
<ul>
    <li>The app only works in chrome and safari. The import functionality of ES6 is not working in the firsfox and other browsers. 
    <br> <b>Fix:</b>
        <ul> 
            <li> replace import with fetch </li>   
        </ul>
    </li>
    <li>The app will not clear storage automatically. You need to clear cache to see new features. You will also lose your tasks.
        <br> localStorage.clear
        <p> Single directive
            Clear-Site-Data: "cache"

             Multiple directives (comma separated)
            Clear-Site-Data: "cache", "cookies"

             Wild card
            Clear-Site-Data: "*"
        </p>
    </li>
</ul>