# Which hosting methods are best suited for my project components?
In this document I am going to to see what it takes to both host parts of my application online as safe as possible.
The image below shows what the current network looks like.<br/>
![local network diagram](./Media/Demotica_Dashboard-local_network.png)<br/>
As is shown in the diagram, there are about 4 services that are comunicating with eachother to make this app work: the IOT device, the MQTT broker, the Springboot REST service and the React frontend app. I believe I could host everyting (except for the IOT devices for obvious reasons) online. but this raises the following questions: how, where and why?

## What are spring boot application hosting solutions
### 3rd party hosting service
>spring boot application deployment. (z.d.). docs.spring.io. https://docs.spring.io/spring-boot/docs/current/reference/html/deployment.html <br/>
>Stallman, R. (z.d.). Who Does That Server Really Serve? GNU.Com. Geraadpleegd op 13 december 2021, van https://www.gnu.org/philosophy/who-does-that-server-really-serve.html
>
Spring boot applications can be hosted using a variety 3rd party hosting services. the Spring docs mention Heroku Cloud Foundry, Amazon Web Services (AWS), Azure Google cloud and many more. The way this works is through hosting on VM's on a cloud. A vm could be as simple as a linux commandline OS or even a full graphical version of Windows10, even though the latter one would obviously be a less desired choice. The reason for that is that the OS should be as light as possible, This way the vm wont have to spend much proccesing power on just running the operating system.<br/>
3rd party hosting does bring some security risks however. Hosting software on a 3rd party means having to use SAAS(Software as a Service). not only will i likely have to pay a monthly fee for using the hosting service, I am also at the merce of any monitoring that the provider might do. this all ofcourse largly depends on the provider, it is however a very note worthy subject.<br/>
While we are on the subject of security, I should also mention that the application itself could prove to be a security risk. By not configuring some API calls or acces configurations correctly, I would allow certain blind spots to be out in the open. This is a problem that could be applied to both 3rd party hosting services as self hosting(next subject).
### Self hosting

### In conclusion
<br/>

## What are MQTT broker hosting solutions
### 3rd party hosting service
### Self hosting
### In conclusion
<br/>

## What are React hosting solutions
### 3rd party hosting service
### Self hosting
### In conclusion
<br/>

## What is a safe way to port forward
