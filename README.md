# ARVR Business Card
###### developed by [Garrison Shoemake](https://github.com/Garrison-Shoemake) -[LinkedIn](https://www.linkedin.com/in/garrison-shoemake/) -[Twitter](Coming Soon!)

## Development
For this project, we were led towards WebXR, an API developed for web browsers. Coupled with hosting on GitHub Pages, this project's goal was to host an application similar to a previous project where we used Unity and Vuforia to show personal links when an image is recognized.

Unlike that project, this one does not revolve around recognition, but can be accessed by anyone scanning this QR Code:
<p align="center">
  <img src="https://raw.githubusercontent.com/Garrison-Shoemake/business-card/master/QR%20Code.png" width="250">
</p>

When scanned, the application loads looking at a floating GitHub Icon with the toggling of AR or VR in the bottom right. Switching to AR brings up the user's camera and uses it as their position in virtual space. Aiming at an icon with the orange reticle will turn it white to show an interacatable. Tapping anywhere on the screen with the reticle white will take you to the respective links. 

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/276959475737296896/953066135434170438/Screenshot_20220314-180406_Chrome.jpg" width="250">
</p>

Similarly, it can be viewed [here](https://garrison-shoemake.github.io/business-card/) on a browser. The reticle works the same, through click and drag mouse controls. Once the reitcle is aimed over an icon, click anywhere on the screen to interact with that object. Currently, there is only a solid white background. Another issue I ran in to was that I could not have a skybox when the application was in AR. The skybox would cover the device's tracked camera, so this is something I will look in to implementing.

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/276959475737296896/953075686631952414/Screenshot_20220314-180537_Chrome.jpg" width="250">
</p>

For this project, using WebXR meant using HTML, a language I'm not too familiar with. Thankfully, I learned about [A-Frame](https://aframe.io/), an easy to use entity-based framework that made developing in HTML feel as close to Unity as it could. Getting used to using HTML was the hardest acclimation for this project, but A-Frame gave me a platform that I look forward to expanding on. Goals for the future include more links and image recognition for mobile use.


## To-do List:
- [x] Add GitHub Icon
- [x] Add LinkedIn Icon 
- [x] Implement AR Recognition on User Device
- [ ] Add Twitter Icon
- [ ] Implement Image Recognition
- [ ] Test for Quest Headset
- [ ] Optimize non-mobile device use
- [ ] Implement background for non-AR use (no white screen)
