this is v4l2 loopback device which output is it's own input.

this is useful for feeding different v4l2 applications with video from non v4l2 sources, for example one can feed Skype with video enhanced by gstreamer effects; or use input device which does not have v4l2 compliant driver; or to share one v4l device with many programs, as many drovers are block device, when opened.

code is based on avld driver, but in fact it is a complete rewrite and final version unlikely will share common code.<br>

work is ongoing, next stage is to remove hard-coded image resolution and make it possible to open device for reading more than one time.<br>
<br>
this project is not actively maintained anymore, please look at the fork here<br>
<br>
<a href='https://github.com/umlaeute/v4l2loopback'>https://github.com/umlaeute/v4l2loopback</a>