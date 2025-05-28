# Lab8-Starter

https://evgenii-ruzin.github.io/Lab8_Starter/

'graceful degradation' principle refers to the idea of designing app in such a way that it will still continue to work even after some of it dependancies become outdated or unavailable. Service Workers allow us to add graceful degradation to our program. For example, suppose our web app always gets some image from www.web.site/image.png. If web.site becomes unavailable, without service workers this image would become unavailable as well. With them, however, this image is cached, so even when web.site doesn't exist anymore, our web app will still load the image because it is cached.
So, graceful degradation and service workers are related in a sense that service workers are the tool to provide graceful degradation to our web app.