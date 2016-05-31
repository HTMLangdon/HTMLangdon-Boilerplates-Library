// How projects should be set up:

/*

stylesheets/
|
|-- modules/              # Common modules
|   |-- _all.scss         # Include to get all modules
|   |-- _utility.scss     # Module name
|   |-- _colors.scss      # Etc...
|   ...
|-- partials/             # Partials
|   |-- _base.sass        # imports for all mixins + global project variables
|   |-- _buttons.scss     # buttons
|   |-- _figures.scss     # figures
|   |-- _grids.scss       # grids
|   |-- _typography.scss  # typography
|   |-- _reset.scss       # reset
|   ...
|-- vendor/               # CSS or Sass from other projects
|   |-- _colorpicker.scss
|   |-- _jquery.ui.core.scss
|   ...
|
`-- main.scss            # primary Sass file

*/

/* BEST example of what each media query is for in a stylesheet i've ever seen. from'prowebdesign.net/simple-responsive-template/tutorial/css.html' */
//          /*
//          BASE (MOBILE) SIZE
//          These are the mobile styles. It's what people see on their phones.
//          Remember, keep it light: Speed is Important.
//          */
//          
//          /*
//          LARGER MOBILE DEVICES
//          This is for mobile devices with a bit larger screens.
//          */
//          @media only screen and (min-width: 481px) 
//          { 
//          
//          }
//          
//          /*
//          TABLET & SMALLER LAPTOPS
//          The average viewing window and preferred media query for those is 768px.
//          But I think that some more breathing space is good:)
//          */
//          @media only screen and (min-width: 920px) 
            {
//          
//          }
//          
//          DESKTOP
//          This is the average viewing window. So Desktops, Laptops, and
//          in general anyone not viewing on a mobile device. Here's where
//          you can add resource intensive styles.
//          */
//          @media only screen and (min-width: 1030px) 
            {
//          
//          }
//          
//          LARGE VIEWING SIZE
//          This is for the larger monitors and possibly full screen viewers.
//          */
//          @media only screen and (min-width: 1240px) 
            {
//          
//          }
//          
//          RETINA (2x RESOLUTION DEVICES)
//          This applies to the retina iPhone (4s) and iPad (2,3) along with
//          other displays with a 2x resolution.
//          */
//          @media only screen and (-webkit-min-device-pixel-ratio: 1.5),
//          only screen and (min--moz-device-pixel-ratio: 1.5),
//          only screen and (min-device-pixel-ratio: 1.5) 
//          {
//          
//          }
//          
//          iPHONE 5 MEDIA QUERY
//          iPhone 5 or iPod Touch 5th generation styles (you can include your own file if you want)
//          */
//          @media (device-height: 568px) and (-webkit-min-device-pixel-ratio: 2) 
            { 
//          
//          }
//          
//          PRINT STYLESHEET
//          @media print 
//          {
//          }

//          ZX