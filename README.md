# AnimatedCountDown
Explained You in Siimple Way

Step1: transform: translate(-50%,-50%) always give you the center element based on the container you applied, Always remember that.

Step2: transfrom-origin give you the ability to control the tranformation, from where you want to move and end the transfrom like from center bottom. 

come at center and go to the bottom.

step3: animation in this project i used from 120deg to 0deg. 

what it means that the element come at 120deg means center of the container and then go back to 0% meams bottom of the container.
based on the transfrom-origin property as I told you earlier.

step4: In this project, we use four animation goIn, goOut, hide and show.

step5: so basically the flow is like that 

    > first all the animation is performed and the first condition we check (refer code)
    
    > second after all the animation get performed we use the second animation called goOut it basically
    
    used to hide the animation from 0 to -120%. why, bcz 120% is the starting point of our animation so we have to stop that by hiding it
    
    > third after both the animaton get completed, else block gonna run. 
    
    > Then we use two function to replay it again and resetTheValues.
    
    > on the resetFunction I used one forloop don't get confused it basically means we are removing the class name using classList.value.

    And querySelectorAll give us nodeList and it is array like object not as original array, but we can use foreach loop in modern browser.
    so we use num[0] and add the classlist again so it show the element again from 120deg.














