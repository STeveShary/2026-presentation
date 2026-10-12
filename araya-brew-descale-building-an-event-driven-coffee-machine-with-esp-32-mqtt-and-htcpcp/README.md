# BREW /descale: Building an Event-Driven Coffee Machine with ESP32, MQTT, and HTCPCP

Arturo Araya &mdash; *Arturo Araya, Lead Software Engineer, Fifth Third Bank*

- [LinkedIn](https://www.linkedin.com/in/arturoarayacincinnati/)
- [Website](https://substack.com/@cloudfreehome)

## Bio

Arturo has had dual, sometimes competing, sometimes collaborating, passions in both music and technology since he was 10. After pursuing, and receiving, a Bachelors, Masters, and  finally an Artist Diploma in Cello Performance from  Oberlin Conservatory and the University of Cincinnati's College-Conservatory of Music, and after then briefly performing as principal cellist of the Shenzhen Symphony Orchestra in Shenzhen, PRC, Arturo's career took him in a completely different direction. 

Currently, Arturo is tech lead for Fifth Third Bank in the areas of Software Security and Risk Mitigation, where he gets to cooperate with great people, solving interesting puzzles that  make the online banking experience safer for all of Fifth Third's customers. While he still pursues music, off the clock Arturo works on crafting his own smart home system, building components from scratch, and working out how to get them to talk to one another. He spends equal amounts of time tending to his home lab, a sort of "digital garden".

## Abstract

It started as a joke: a fictitious curl command using the Hyper Text Coffee Pot Control Protocol (HTCPCP - RFC 2324) to trigger a coffee machine cleaning cycle.

Then I built it.

And it works.

In this talk, we’ll walk through how I instrumented a Breville Barista Express with an ESP32 to safely emulate button inputs, expose a playful HTCPCP-inspired interface, and stream real-time telemetry over MQTT.

Along the way, we’ll explore how serious engineering concepts—event-driven architecture, state machines, observability, and protocol design—translate surprisingly well into the world of IoT (and espresso).

Topics include:

- Designing a safe hardware interface without defeating built-in protections
- Modeling a physical process (descaling) as an event-driven system
- Using MQTT for telemetry, control, and integration with systems like Home Assistant
- Building an HTTP façade that translates REST/HTCPCP-like calls into asynchronous device commands
- Securing your HTTP façade to prevent your neighbor from flooding your kitchen

Whether you're building distributed systems or just love coffee, this talk shows how “toy” projects can become real platforms—and why sometimes the best way to understand architecture is to brew it.

- **Level**: Advanced
- **Tags**: Architecture & System Design, Hardware & IoT, Security
