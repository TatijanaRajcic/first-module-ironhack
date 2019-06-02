Things I still don't understand:

- I set the color of Body to rgba(255,255,255,0.8) and the color of buttons to white (that what intentional). But I don't understand why the Body color don't apply to my Links (that's why I added the Rgba color again here)

- I didn't use float right for the header because the image is filling the full container (and was not certain how to use float to be honest). I decided to use background-image. I still don't get how to fix it in order not to move when it's not full screen

- For section "Collaboration" I tried to offset the <ul> compared to the heading, and it's kind of working but it looks ugly. My heading "npm orgs is powerful..."  is offset because of the image floating, but when I tried to offset the <ul> compared to the heading (thanks to position: relative, position:absolute) it took into account the "normal" positionning of the heading, and not the actual one. So I gave up this method

Remarks:

- I didn't use an <ul> tag for the sign-in sign-up and bear logo because for me there is no semantic links between them

- Still not sure about the use of floats and clearfix

- Site looks terrible when not full screen