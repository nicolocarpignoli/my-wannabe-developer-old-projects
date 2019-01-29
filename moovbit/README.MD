
# MOOVBIT

## What is that?

MOOVBIT is the project for my master degree’s thesis. It is the result of a six months internship at an italian Software House. Is basically divided in two main studies:

MOOVBIT is the name of the project and of the IoT architecture that I designed. This architecture is general-purpose, composed by three layers and comes with studies about all aspects of an ICT System, such as scalability, performance, fault-tolerance and most of all security. So you basically can see how I design this architecture and why I suggest three layers, why suchs communication protocols and databases – every choice was done accordingly to the specific features of the case study – because “IoT systems” means a lot of very different cases and “IoT” is such a known buzzword that led to think, erroneously, that all IoT systems are similar.
MOOVBIT Suite is the prototype that was built following the architecture that I designed. It was composed by a input component with sensor (MOOVBIT Tag), a Gateway and a Server. This prototype was applied to the specific case study of monitoring of athletes in Squash sport, during training. So basically the thesis covered the theorical and more general aspects and then go in deep and in more technical aspects with this real implementation.

## Why?

Because IoT is fascinating, it’s a market that is real, it’s the present and the future, but it’s also so bad standardized. There are yet no standards in security, in communication protocols nor architectural styles. Building IoT systems required high skills but also efforts from telco companies and providers of internet/ICT services.

## Any technical detail?

Here’s a list of technologies/framework/tools that I used for the complete data flow (from MOOVBIT TAG sensor data to web dashboards):

* Arduino 101 Libraries (C++)
* 6-axis Gyro and Accelerometer sensor
* gatttool ([and jgattool library, which I wrote myself](https://github.com/nicolocarpignoli/jgatttool))
* Intel Nuc Gateway
* Java
* MQTT
* Redis
* Cassandra
* Spring
* Angular JS.

## Links

[Thesis Document](https://drive.google.com/file/d/1xB3jqQNRWYz75WBPiMZ5Z7yK_7ac4Uoz/view?usp=sharing)

[Thesis slides](https://drive.google.com/file/d/15HWhpK37x_EO8cy5ZlUFLIZfHuU-5zQH/view?usp=sharing)

[MOOVBIT TAG source code](https://github.com/nicolocarpignoli/moovbittag-arduino)
