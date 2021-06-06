# [e107 Bootstrap Landing Zero 2](https://www.e107sk.com/)


## Version 1.5  


Version 1.5.1 Fixed

- REMOVED theme solution for SITEDISLAIMER, core is used now
- REMOVED signup template, core one is used
- FIXED mistypo for masthead template
- FIXED autoplay video for Chrome, see: https://stackoverflow.com/questions/34764876/html-5-video-autoplay-not-automatically-starting-in-chrome
- FIXED missing placeholders in contact menu

Version 1.5.0

- REMOVED support for Login page as standalone page (not supported by core)
- REMOVED support for FPW in modal (not supported by core)
- ADDED support for Signin plugin, {SIGNIN} shortcode
- REMOVED support for {{MEMBER_LOGIN}} and {USERBOX}
- ADDED support for {NAVBAR_BRANDING}
- ADDED support for JMLayouts plugin
- REMOVED support for JMTheme plugin
- FIXED theme.php for new standards (e107 2.3.1 after 10.3.2021 )
- FIXED theme.xml for new standards (e107 2.3.1 after 10.3.2021 )
- FIXED Removed plugins folder from theme, see #4390
- FIXED Default style if there are skins available
- FIXED Mistypo for WM tablestyle
- FIXED Used LAN shortcode for theme LAN string - PHP8 fix


## Version 1.4 

Version 1.4.3 Fixed 

- REMOVED theme solution for SITEDISLAIMER, core is used now
- FIXED mistypo for masthead template
- FIXED autoplay video for Chrome, see: https://stackoverflow.com/questions/34764876/html-5-video-autoplay-not-automatically-starting-in-chrome
- FIXED missing placeholders in contact menu

Version 1.4.2 Fixed 

- FIXED Removed plugins folder from theme, see #4390
- FIXED Default style if there are skins available
- FIXED Mistypo for WM tablestyle
- FIXED Used LAN shortcode for theme LAN string - PHP8 fix

Version 1.4.1  

- FIXED Hidding Welcome Message by default

Version 1.4.0

- ADDED Master Header functionality

Version 1.3.0

- ADDED extended Theme Options 
- ADDED extended Login page Configuraton


## Version 1.2 

Version 1.2.2 [not released, fixed only custom theme UG]

- FIXED theme.php for new standards (e107 2.3.1 after 10.3.2021 )

Version 1.2.1

- FIXED theme.php for new standards (e107 2.3.0 after 4.5.2020 )
- FIXED cleaned not used prefs 
- ADDED support for inline css code
- ADDED theme help page
- UPDATED custom theme import - available only in debug or developer mode
- UPDATED pager look on core user template

Version 1.2.0

- FIXED theme.php for new standards (e107 2.3.0 after 30.4.2020 )
- FIXED wrong original author in Readme
- UPDATED resized and compressed demo images

Version 1.1.1

- changed compability with e107 2.2.0 (e107 2.3.0 from 17.3.2020 )
Version 1.1.0

- FIXED header and footer custom shortcodes - there is no need parsing template separately, it's done in core with theme.html
- ADDED possibility to use boxed layout - see theme preferences 
- ADDED shortcode for using theme prefs value in HTML layouts directly
- REMOVED link to Calender plugin in demo data 
- TESTED with e107 2.3.0 from 17.3.2020 


Version 1.0.0

- UPDATED and tested with Boostrap 3.4.1
- REMOVED social links shortcode and ADDED social links template
- REMOVED one 2 columns footer navigation and ADDED 2 separate navigation (footer+alt5)
- REMOVED hardcoded About modal button and ADDED alt navigation for this functionality
- REMOVED BOOTSTRAP USERNAV shortcode and ADDED  {USERBOX} and {MEMBER_LOGIN}
- ADDED HTML layouts and REMOVED php layouts
- ADDED 3 columns layout
- ADDED 2 columns left sidebar layout
- ADDED support for DEFAULT_MENUAREA - works only with JM Theme plugin






