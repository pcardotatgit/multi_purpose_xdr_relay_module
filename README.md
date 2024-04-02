# Multi Purpose XDR Relay Module

This project is a generic and multi purpose Relay Module for Cisco XDR.

What is a Relay Module ?  this is a component that allows integration of any 3rd party solution into XDR. 

The XDR Architecture is very agile, and very open. This is a microservice architecture which include natively into the plateform the capability to connect XDR to anything that exist in the IT, to any 3rd Party solutions.

The Relay Module is the component which lives between XDR and the third party solution and which translate API calls sent by XDR into 3rd party solution requets in the format expected by this solutions.  And in the way back the Relay Module is responsible for translating replies from the 3rd Party solution into valid JSON anwsers for XDR.

At the first sight this component can be seen just as a connector that link XDR to 3rd Party Solutions, and which is responsilbe for translation.

But we quickly understand that it is much more than tha. This is a very powerfulcomponent is !   It can be much more than a simple connectors.

You can add into it demo data, You can add into it a web front end, you can add to it a chat bot, and you can connect it to an Artificial Intelligence. And then create a second Threat Hunting Engine which can be as powerfull as XDR it self and which provides you with the security features you miss.

The idea of this current project is to share a Relay Module Template which help anyone who want to create a new integration within XDR, to start in 5 minutes. 

This Relay Module Template provides with a lot of code samples for almost every activities we need when we create an integration. We have to built our new code and use the code examples as refences to build custom codes. 

But this Relay Module is functional. That mean that you can start it and it works. It gives a few demo tiles which will appear into you XDR tenant. Running the Relay Module template and displaying the demos tiles into the XDR tenant is the fist step for a new development. And 5 mins are needed for that.

![](/img/relay_module_architecture.png)