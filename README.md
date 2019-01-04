# BOG.RaspberryPi.IFTTT

![alt text](https://github.com/rambotech/BOG.RaspberryPi.IFTTT/blob/master/assets/IFTTT_PI.png "Events to Raspberry Pi, actions from Raspberry Pi")

Status: ...Currently under construction...

A template for an ASP.NET Core Restful Web API which interfaces with IFTTT (If This, Then That)

- To send a webhook (event trigger) to IFTTT, to trigger an action (email, sms, slack, etc, etc...)
- To receive a webhook from IFTTT, from an event such as voice command, geofence entry/exit, etc.

This template includes the following:
- A basic web site (no authentication) with a simple home page promoting the template.
- A Swagger UI for testing the endpoints.
- Support for the GPIO pin output management (on, off, toggle)
- Support for monitoring GPIO for inputer pin state changes.
- Generic, pre-defined enpoints to cover most cases.

