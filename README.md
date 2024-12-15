## Hi there 👋

I don't have a particular favorite programming language; I appreciate what can be achieved with each of them. I'm a touche-à-tout who enjoys discovering new things.
I like open-source and libre projects ❤️

## 🔧 Technologies & Tools
Ruby, Python, Go, C, C++, JavaScript, AWS, Docker, ...

## 🚀 Personnal Projects 

[homeassistant-comwatt](https://github.com/MateoGreil/homeassistant-comwatt)
- An integration for Home Assistant that allows you to monitor and control your Comwatt devices.
- Fetches real-time data from Comwatt API and provides sensors for power consumption, production, and more.
- Enables you to create automations and track your energy usage directly from Home Assistant.
- Technologies used: Python, Home Assistant, Comwatt API

[xapi-go](https://github.com/mateoGreil/xapi-go)
- A Go library that implements the XAPI protocol
- Not really finished: does not implement all the API features.

[python-dvr](https://github.com/MateoGreil/python-dvr)
- Reverse-engineered the [application](https://apps.apple.com/fr/app/maginon-afs-1/id1438744569?l=en) of a pet feeder distributor bought at 15e at Action (Maginon is just a re-seller of chinese products), to gain control without using their xmeye API .
- Discovered that the pet feeder had weak default credentials ("admin:admin") and could not be changed through the manufacturer's application.
- Found that anyone with the serial number of the pet feeder could access the camera via the "By Device" section of the [xmeye.net](https://www.xmeye.net/index) website.
- After uncovering these vulnerabilities, I searched for and found an existing codebase to [add OPFeederFunctions](https://github.com/MateoGreil/python-dvr/pull/1).
- The original forked repository was reset in favor of the [OpenIPC/python-dvr](https://github.com/OpenIPC/python-dvr) repository, resulting in the loss of my commits.
- This project highlights the importance of secure default configurations and the potential risks associated with weak authentication mechanisms in IoT devices.
- Technologies used: Python, Wireshark.

## 💼 Professional Experience

### [Electra](https://github.com/Go-Electra/) (Current: 2 years +)
- Technologies: Ruby On Rails (Sidekiq, ...), Golang, PostgreSQL, Docker, AWS (Terraform, ...), Bugsnag, Datadog, ...
- Experienced with various protocols in the EV (Electric Vehicle) industry, including OCPP, OPCP, OICP, OCPI (all these protocols with O, C and P are not a joke, and are not the same), MQTT, ...

### [Wecasa](https://github.com/wecasa/) (1 year 3 months)
- Technologies: Ruby On Rails (Capistrano, Sidekiq, ...), MySQL, Docker, Airbrake, NewRelic, CircleCI, ...

### [Ekylibre](https://github.com/ekylibre/) (9 months)
- Technologies: Ruby On Rails (Capistrano, Sidekiq, ...), PostgreSQL, PostGIS, Docker, Kibana, ...
- Contributed to the development of an open-source farm management software. Not all the code I provided to Ekylibre ended up being open-sourced.

### [42 Network](https://github.com/topics/42network) (5 months)
- Technologies: Ruby On Rails (Capistrano, Sidekiq, ...), PostgreSQL, Django, Flask, JS, Docker, Sentry, NewRelic, ... On self-hosted servers.

Made with ❤️ with 🤖
