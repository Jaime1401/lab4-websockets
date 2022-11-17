# Web Engineering 2022-2023 / Lab4 WebSockets

Please, go to the [GUIDE](docs/GUIDE.md) in order to get the instructions for this assignment.

Some ideas for obtaining a :gift: if you are the first that:

- **STOMP!**: Support STOMP in the server side and create a small client that uses it.
- **Sock from WebSocket**: Support SockJS in the server side and show that polling can be used as transport instead of WebSocket when needed ([additional info](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#websocket-fallback-sockjs-client)).
- **Turn sides**: Turn the DOCTOR into a client of the server, so, the server acts only as message broker.
- **Relay**: Use the server as a relay server to connect to an external message broker (e.g. RabbitMQ, [additional info](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#websocket-stomp-handle-broker-relay))

Note: unless the goal specifies o disallows a specific framework you are free to replace the framework used in the original implementation with a different framework.

Manifest your intention first by a PR updating this `README.md` with your goal.
If you desist of your goal, release it by a PR so other fellow can try it.

| User name    | NIA    | GitHub Action                                                                     | Score |
|--------------|--------|-----------------------------------------------------------------------------------|-------|
| [GueorguiKachan](https://github.com/GueorguiKachan/lab4-websockets/tree/work) | 794799 | [![Build Status](https://github.com/GueorguiKachan/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/GueorguiKachan/lab4-websockets/actions/workflows/ci.yml)
| [Ibon2](https://github.com/Ibon2/lab4-websockets/tree/work) | 776561 | [![Build Status](https://github.com/Ibon2/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/Ibon2/lab4-websockets/actions/workflows/ci.yml) |
| [jbuil](https://github.com/jbuil/lab4-websockets/tree/work) | 797285 | [![Build Status](https://github.com/jbuil/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/jbuil/lab4-websockets/actions/workflows/ci.yml) |
| [Ernesting](https://github.com/Ernesting/lab4-websockets/tree/work) | 798799 | [![Build Status](https://github.com/Ernesting/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/Ernesting/lab4-websockets/actions/workflows/ci.yml) 
| [HectorRute98](https://github.com/HectorRute98/lab4-websockets/tree/work) | 736259 | [![Build Status](https://github.com/HectorRute98/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/HectorRute98/lab4-websockets/actions/workflows/ci.yml) |
| [pikanachi](https://github.com/pikanachi/lab4-websockets/tree/work) | 610720 | [![Build Status](https://github.com/pikanachi/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/pikanachi/lab4-websockets/actions/workflows/ci.yml)
| [ZenithGD](https://github.com/ZenithGD/lab4-websockets/tree/work) | 795306 | ![Build Status](https://github.com/ZenithGD/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push) | Plan to implement **Relay** |
| [rubenDTD](https://github.com/rubenDTD/lab4-websockets/tree/work) | 736650 | [![Build Status](https://github.com/rubenDTD/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/rubenDTD/lab4-websockets/actions/workflows/ci.yml) |       |
| [798523](https://github.com/798523/lab4-websockets/tree/work) | 795306 | ![Build Status](https://github.com/798523/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)|       |
| [Daniel-dgp](https://github.com/Daniel-dgp/lab4-websockets/tree/work) | 756128 | ![Build Status](https://github.com/Daniel-dgp/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push) |       |
| [celiia01](https://github.com/celiia01/lab4-websockets/tree/work) | 796685 | [![Build Status](https://github.com/celiia01/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/celiia01/lab4-websockets/actions/workflows/ci.yml) |       |
| [Davidzf21](https://github.com/Davidzf21/lab4-websockets/tree/work) | 780500 | ![Build Status](https://github.com/Davidzf21/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push) |       |
| [HugoLazaro](https://github.com/HugoLazaro/lab4-websockets/tree/work)           | 801758 | [![Build Status](https://github.com/HugoLazaro/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/HugoLazaro/lab4-websockets/actions/workflows/ci.yml) |       |
| [PilarEster](https://github.com/PilarEster/lab4-websockets/tree/work)         | 800033 | ![Build Status](https://github.com/PilarEster/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)                                                                                   |       |
| [Berty980](https://github.com/Berty980/lab4-websockets/tree/work) | 735976 | [![Build Status](https://github.com/Berty980/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/Berty980/lab4-websockets/actions/workflows/ci.yml) |       |
| [797021](https://github.com/797021/lab4-websockets/tree/work) | 797021 | ![Build Status](https://github.com/797021/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push) |       |
| [p3n4x0](https://github.com/p3n4x0/lab4-websockets/tree/work)   | 774572 | ![Build Status](https://github.com/p3n4x0/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push) |       |
| [newfeels](https://github.com/newfeels/lab4-websockets/tree/work) | 779898 | ![Build Status](https://github.com/newfeels/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)|       |
| [GonchiMonchi](https://github.com/GonchiMonchi/lab4-websockets/tree/work) | 759561 | [![Build Status](https://github.com/GonchiMonchi/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/GonchiMonchi/lab4-websockets/actions/workflows/ci.yml)   |       |
| [797610](https://github.com/motinsa/lab4-websockets/tree/work) | 797610 | [![Build Status](https://github.com/motinsa/lab4-websockets/actions/workflows/ci.yml/badge.svg?branch=work&event=push)](https://github.com/motinsa/lab4-websockets/actions/workflows/ci.yml)
