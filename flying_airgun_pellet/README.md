# flying_airgun_pellet

When capturing videos, framerate unit is fps (frames per second).

Characterising multiple exposure frames, the unit is eps (exposures per second).
 
[airsoft pistol multiple exposure frame](https://github.com/Hermann-SW/Raspberry_v1_camera_global_external_shutter#user-content-bottom_led)  
2MP, 8.33&micro;s duration flashes at 3KHz frequency, 36.3m/s pellet speed, 3000eps:
![pellet3](../res/6mm.frame3946.jpg)

[airgun multiple exposure frame](https://github.com/Hermann-SW/Raspberry_v1_camera_global_external_shutter#user-content-bottom_plus_top_led)  
2MP, 8.33&micro;s duration flashes at 3KHz frequency, 109.2m/s pellet speed, 3000eps:
![pellet3](../res/airgun.1a.jpg)

[airgun multiple exposure frame](https://github.com/Hermann-SW/Raspberry_v1_camera_global_external_shutter#user-content-9000eps)  
0.3MP, 9KHz frequency 8.33&micro;s duration flashes, 96.9m/s pellet speed, 1.07cm between pellet exposures, 9000eps:
![pellet3](../res/pointed.pellet.frame0360.jpg)

Previous frame lens distortion correted with OpenCV:  
![pellet4](../res/pointed.pellet.frame0360_undistorted.jpg.png)

[airsoft pistol multiple exposure frame](https://www.raspberrypi.org/forums/viewtopic.php?f=43&t=241418&p=1531537#p1531537)  
Flying pellet spins fast, 93.75rps or 5625rpm (see blue dot on pellet).  
2MP, 9&micro;s duration flashes at 6KHz frequency, 36.3m/s pellet speed, 6000eps:  
![pellet3](../res/pellet.rotation.png)

[airsoft pistol 3pellets multiple exposure frame](https://www.raspberrypi.org/forums/viewtopic.php?f=43&t=253300&p=1547107#p1547107)  
The frame shows 3 pellets shot together by airsoft pistol. 300Hz frequency with 9µs long flashes was used. The left 3 pellets belong to one exposure, and the right three pellets to the next exposure:  
![3pellets](../res/good.0485.png)

Animation created from [full and empty frame](https://github.com/Hermann-SW/Raspberry_v1_camera_global_external_shutter#full-and-empty-frame), 5000fps framerate, played at 5fps, 1000× slower than real:  
![pellet5](../res/frame.640.5.anim.gif)

[camera software panning](https://github.com/Hermann-SW/Raspberry_v1_camera_global_external_shutter#camera-software-panning) allows to simulate really fast real camera panning in post processing.  
From 2500eps frame, full rotation in 5 frames, that is 500rps or 30,000rpm spinning of pellet:  
![pellet6](../res/frame.180.5.anim.gif)
