# Plan

## Use:
    - Bootstrap
    - Sass
    - Awesome Font
## Idea: 
    - http://impreza.us-themes.com/

## Step:
    - Header:
        + Nav (Bootstrap)
        + Header Text
    - Features:
        + 4 column link to 4 sections
    
    - Our lastest Work
        + 2 row with 3 columns 
        + hover effect
    
    - High quality:
        + 4 columns
    
    - Core featureS:
        + 3 rows 3 columns
    - Footer:
        + 3 columns

# Code
## Nav:
    - Idea:
        + fixed top (sticky when scroll): use Bootstrap fixed-top, data-spy and data-target
            --> https://www.w3schools.com/bootstrap4/bootstrap_ref_js_scrollspy.asp
        + Change color when scroll (require js): window.scrollY
        --> https://www.codehim.com/demo/bootstrap-responsive-navigation-menu/
        --> View source code of this website
        + Responsive: use Bootstrap
    
    - Code Exp:
        + don't set height for nav in bootstrap (can't no set background for dropdown)
        + to move ul to the right, use ml-auto class of boostrap

## Header:
    - idea:
        + div store btn and header then use the div to move 2 items into center
        + use ::after content of h1 to make a change
        + Use btn effect before and clip path.

## Section Feature:
    - Idea: 
        + Use clip paht for the section to make wave shape
        + Use grid of bootstrap to make 4 column 
        +link features with sections and use scroll-behave: smooth to make the transaction smooth
    
    - Code Exp:
        + bootsrap 3 has col-<size>-offest-<number> to space between col (didn't use in this project)
            --> <number> = number of col
            --> https://getbootstrap.com/docs/3.3/css/#grid-offsetting
    
## Last Work:
    - Idea:
        + 1 div content img and div(hover content)
        + 2 row 3 columns each
    
    - Code Exp:
        + in div content, even position absolute, we still can use display flex to position the children elements

## Quality:
    - Idea:
        + 1 header 
        + 1 row 4 column
    - Code Exp:
        + To make background darken
        --> background-image: rgba(0,0,0,<opacity>), url();
        
# Screenshots

![Screenshot from 2020-04-19 08-22-45](https://user-images.githubusercontent.com/44929757/79690339-33044d00-8217-11ea-8166-799d85b1738f.png)


![Screenshot from 2020-04-19 08-28-39](https://user-images.githubusercontent.com/44929757/79690483-dbb2ac80-8217-11ea-9643-cca4be6f9c32.png)


![Screenshot from 2020-04-19 08-30-31](https://user-images.githubusercontent.com/44929757/79690531-1f0d1b00-8218-11ea-832d-f54b56e0fb90.png)


![Screenshot from 2020-04-19 08-33-43](https://user-images.githubusercontent.com/44929757/79690617-83c87580-8218-11ea-90a9-c45d37c13dac.png)
        
