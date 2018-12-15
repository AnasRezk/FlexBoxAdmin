** Subjects **

1. Custom Properties (CSS Variables)

   - Pros
     1. you donot need Pre-processoprs.
     2. Can be manipulated from javascript.
     3. you can edit them in dev tool.
     4. easy to use in `calc` function.
   - Usage
     1. They have to be defined in scope declation block.
     2. Define variables in shared place.
        `:root{ --color-primary: #ccc; }`
     3. Use **--** in order to distinguish between our custom propertise and built-in css propertise.

2. FlexBox

   - Usage

     1. to define width of element we use ** flex phases property **
        we should use it in the shortened flex property
        `flex: flex-grow flex-shrink flex-basis`

        `flex: 0 0 18%`
        0 --> we donot our element to grow if there is some space
        0 --> we donot our element to shrink if there is not enough space
        18% --> The perfect width for the sidebar, this mean its automatically shrink

     2. use `flex:1` to make element grow as mush as it can

3. Font Icons VS SVG Icons
   **its best practisen to use svg icons instead of font icons**
 