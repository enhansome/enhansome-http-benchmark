## HTTP(S) benchmark tools, testing/debugging, & restAPI (RESTful)

*Located in alphabetical order (not prefer)*

# Awesome HTTP(S) Benchmark Tools with stars

* [**wrk**](https://github.com/wg/wrk) ⭐ 40,391 | 🐛 203 | 🌐 C | 📅 2023-12-30 – multithreaded, ~~but doesn't offer concurrent connections and a keepalive switch~~, written in `C`/`Lua`
* [**k6**](https://github.com/loadimpact/k6) ⭐ 31,308 | 🐛 796 | 🌐 Go | 📅 2026-08-25 - A modern load testing tool scriptable in ES6 JS with support for HTTP/1.1, HTTP/2.0 and WebSocket, written in Go (`golang`)
* [**vegeta**](https://github.com/tsenart/vegeta) ⭐ 25,164 | 🐛 122 | 🌐 Go | 📅 2026-02-16 – HTTP load testing tool and library, written in Go (`golang`)
* [**hey**](https://github.com/rakyll/hey) ⭐ 20,240 | 🐛 189 | 🌐 Go | 📅 2026-01-10 – HTTP(S) load generator, ApacheBench (`ab`) replacement, formerly known as [**rakyll/boom**](https://github.com/rakyll/boom) ⚠️ Archived, written in Go (`golang`)
* [**oha**](https://github.com/hatoo/oha) ⭐ 10,504 | 🐛 57 | 🌐 Rust | 📅 2026-08-23 – HTTP load generator, inspired by rakyll/hey with tui animation, written in `Rust`
* [**ddosify**](https://github.com/ddosify/ddosify) ⭐ 8,523 | 🐛 19 | 🌐 Go | 📅 2026-03-04 – High-performance load testing tool, written in Go (`golang`)
* [**autocannon**](https://github.com/mcollina/autocannon) ⭐ 8,502 | 🐛 58 | 🌐 JavaScript | 📅 2026-05-16 – fast HTTP/1.1 benchmarking tool written in Node.js
* [**bombardier**](https://github.com/codesenberg/bombardier) ⭐ 6,825 | 🐛 27 | 🌐 Go | 📅 2026-03-31 – Fast crossplatform HTTP benchmarking tool, written in Go (`golang`)
* [**wrk2**](https://github.com/giltene/wrk2) ⭐ 4,625 | 🐛 106 | 🌐 C | 📅 2024-03-03 – constant throughput, correct latency recording variant of wrk, written in `C`/`Lua`
  Concurrent connections are enabled with:
  -c, --connections <N>  Connections to keep open
  And keepalive (which is default) can be disabled using:
  -H "Connection: close"
* [**plow**](https://github.com/six-ddc/plow) ⭐ 4,517 | 🐛 20 | 🌐 Go | 📅 2026-04-28 – A high-performance HTTP benchmarking tool with real-time web UI and terminal displaying, written in Go (`golang`)
* [**ali**](https://github.com/nakabonne/ali) ⭐ 3,937 | 🐛 25 | 🌐 Go | 📅 2026-01-19 – Generate HTTP load and plot the results in real-time, written in Go (`golang`)
* [**fortio**](https://github.com/istio/fortio) ⭐ 3,723 | 🐛 87 | 🌐 Go | 📅 2026-08-24 – load testing library and command line tool and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats, written in Go (`golang`)
* [**yandex-tank**](https://github.com/yandex/yandex-tank) ⭐ 2,596 | 🐛 84 | 🌐 Python | 📅 2026-08-19 – Load and performance benchmark tool, written in `Python`/`C|C++|Asm` ([phantom](https://github.com/yandex-load/phantom) ⭐ 72 | 🐛 4 | 🌐 C | 📅 2020-02-04)
* [**drill**](https://github.com/fcsonline/drill) ⭐ 2,307 | 🐛 38 | 🌐 Rust | 📅 2026-07-29 – Drill is a HTTP load testing application inspired by Ansible syntax, written in `Rust`
* [**NBomber**](https://github.com/PragmaticFlow/NBomber) ⭐ 2,238 | 🐛 173 | 🌐 CSS | 📅 2026-08-17 – Modern and flexible load testing framework for Pull and Push scenarios, designed to test any system regardless a protocol (HTTP/WebSockets/AMQP etc) or a semantic model (Pull/Push), written in F# (`F Sharp`)
* [**goad**](https://github.com/gophergala2016/goad) ⚠️ Archived – Goad is an AWS Lambda powered, highly distributed, load testing tool, written in Go (`golang`)
* [**slowhttptest**](https://github.com/shekyan/slowhttptest) ⭐ 1,644 | 🐛 25 | 🌐 C++ | 📅 2025-06-26 – Application Layer DoS attack simulator, written in `C++`
* [**Netling**](https://github.com/hallatore/Netling) ⭐ 1,348 | 🐛 13 | 🌐 C# | 📅 2022-12-05 – Netling is a load tester client for easy web testing., written in C# (`C Sharp`)
* [**go-wrk**](https://github.com/tsliwowicz/go-wrk) ⭐ 1,062 | 🐛 10 | 🌐 Go | 📅 2026-07-04 – a HTTP benchmarking tool based in spirit on the excellent wrk tool ([`wg/wrk`](https://github.com/wg/wrk) ⭐ 40,391 | 🐛 203 | 🌐 C | 📅 2023-12-30), written in Go (`golang`)
* [**httperf**](https://github.com/httperf/httperf) ⭐ 1,017 | 🐛 54 | 🌐 C | 📅 2022-04-20 – difficult configuration, slow and single threaded, written in `C`
* [**goose**](https://github.com/tag1consulting/goose) ⭐ 991 | 🐛 43 | 🌐 Rust | 📅 2026-06-28 - A modern, high-performance and flexible distributed HTTP(S) load testing tool, written in `Rust`
* [**cassowary**](https://github.com/rogerwelin/cassowary) ⭐ 812 | 🐛 7 | 🌐 Go | 📅 2025-09-11 – is a modern HTTP(S), intuitive & cross-platform load testing tool, written in Go (`golang`)
* [**baloo**](https://github.com/h2non/baloo) ⭐ 779 | 🐛 9 | 🌐 Go | 📅 2022-08-10 – Expressive end-to-end HTTP API testing made easy, written in Go (`golang`)
* [**rewrk**](https://github.com/ChillFish8/rewrk) ⭐ 586 | 🐛 18 | 🌐 Rust | 📅 2024-03-25 – A more modern http framework benchmarker supporting HTTP/1 and HTTP/2 benchmarks, written in `Rust`.
* [**molotov**](https://github.com/tarekziade/molotov) ⭐ 480 | 🐛 19 | 🌐 Python | 📅 2024-03-18 - A simple `Python` 3.7+ tool to write load tests
* [**pewpew**](https://github.com/bengadbois/pewpew) ⭐ 456 | 🐛 1 | 🌐 Go | 📅 2026-03-28 - Flexible HTTP command line stress testing tool for websites and web services, written in Go (`golang`)
* [**gobench**](https://github.com/cmpxchg16/gobench) ⭐ 443 | 🐛 21 | 🌐 Go | 📅 2023-01-24 – HTTP/HTTPS load testing and benchmarking tool, written in Go (`golang`)
* [**goloris**](https://github.com/valyala/goloris) ⭐ 380 | 🐛 7 | 🌐 Go | 📅 2019-04-23 – Slowloris for NGINX DoS attack, written in Go (`golang`)
* [**sniper**](https://github.com/lubia/sniper) ⭐ 378 | 🐛 10 | 🌐 Go | 📅 2017-10-15 – powerful & high-performance http load tester, written in Go (`golang`)
* [**weighttp**](https://github.com/lighttpd/weighttp) ⭐ 365 | 🐛 1 | 🌐 C | 📅 2025-04-06 – multithreaded, but slower than htstress without keepalive, written in `C`
* [**slow\_cooker**](https://github.com/BuoyantIO/slow_cooker) ⭐ 346 | 🐛 9 | 🌐 Go | 📅 2023-12-05 – A load tester focused on lifecycle issues and long-running tests, service with a predictable load and concurrency level for a long period of time, written in Go (`golang`)
* [**slapper**](https://github.com/ikruglov/slapper) ⭐ 332 | 🐛 3 | 🌐 Go | 📅 2021-09-20 – Simple load testing tool with real-time updated histogram of request timings, written in Go (`golang`)
* [**apib**](https://github.com/apigee/apib) ⚠️ Archived – most of the features of ApacheBench (`ab`), also designed as a [more modern replacement](https://github.com/apigee/apib#design) ⚠️ Archived, written in `C`
* [**baton**](https://github.com/americanexpress/baton) ⚠️ Archived – HTTP load testing, written in Go (`golang`)
* [**fbender**](https://github.com/facebookincubator/fbender) ⚠️ Archived – A load-testing command line tool for generic network protocols (`HTTP`, `DNS`, `DHCP`, …), written in Go (`golang`)
* [**salvo**](https://github.com/tarekziade/salvo) ⭐ 239 | 🐛 3 | 🌐 Python | 📅 2020-12-02 - A simple HTTP(S) load testing tool like [boom](https://github.com/tarekziade/boom) ⚠️ Archived, but based on [molotov](https://github.com/loads/molotov) ⭐ 480 | 🐛 19 | 🌐 Python | 📅 2024-03-18. `Python`
* [**httpit**](https://github.com/gonetx/httpit) ⭐ 232 | 🐛 8 | 🌐 Go | 📅 2023-03-16 - A rapid http(s) benchmark tool, written in `golang`
* [**gohttpbench**](https://github.com/parkghost/gohttpbench) ⭐ 226 | 🐛 3 | 🌐 Go | 📅 2023-08-10 – `ab`-like benchmark tool run on multi-core cpu, written in Go (`golang`)
* [**cryload**](https://github.com/sdogruyol/cryload) ⭐ 215 | 🐛 0 | 🌐 Crystal | 📅 2026-08-11 – Cross-platform HTTP load testing CLI, `ab`/`wrk` alternative with JSON/CSV output for CI/CD, written in `Crystal`
* [**reqstress**](https://github.com/utkusen/reqstress) ⭐ 165 | 🐛 0 | 🌐 Go | 📅 2022-09-24 – a benchmarking\&stressing tool that can send raw HTTP requests, written in Go (`golang`).
* [**fasthttploader**](https://github.com/hagen1778/fasthttploader) ⭐ 121 | 🐛 5 | 🌐 Go | 📅 2019-02-21 – benchmark (kinda ab) with autoadjustment and charts based on fasthttp library, written in Go (`golang`)
* [**lor-axe**](https://github.com/ajmwagar/lor-axe) ⭐ 96 | 🐛 2 | 🌐 Rust | 📅 2019-05-01 – A multi-threaded, low-bandwidth HTTP Slowloris DoS tool that handles connections and sockets in parallel, written in `Rust`
* [**htstress**](https://github.com/arut/htstress) ⭐ 90 | 🐛 2 | 🌐 C | 📅 2017-10-14 – multithreading high-load bechmarking services (>5K rps), written in `C`/`Linux`
* [**welle**](https://github.com/rylev/welle) ⭐ 60 | 🐛 0 | 🌐 Rust | 📅 2018-10-14 – ab (Apache Benchmark) like tool, written in `Rust`
* [**httping**](https://github.com/folkertvanheusden/httping) ⭐ 54 | 🐛 10 | 🌐 C | 📅 2026-08-07 - Ping with HTTP requests, see <http://www.vanheusden.com/httping/>, written in `C`
* [**inundator**](https://github.com/opsengine/inundator) ⭐ 32 | 🐛 1 | 🌐 C | 📅 2013-05-27 – A simple and high-throughput HTTP flood program, written in `C`/`Linux`
* [**mgun**](https://github.com/byorty/mgun) ⭐ 31 | 🐛 2 | 🌐 Go | 📅 2021-06-21 – A modern tool for load testing HTTP servers, written in Go (`golang`)
* [**pounce**](https://github.com/fredrikwidlund/pounce) ⭐ 24 | 🐛 0 | 🌐 C | 📅 2023-04-25 – event-driven with a similar interface as `wrk` but with the ambition to potentially achieve lower latency and higher throughout, written in `C`
* [**zrk**](https://github.com/zoxy-io/zrk) ⭐ 9 | 🐛 1 | 🌐 Zig | 📅 2026-08-23 - A constant-throughput load generator in Zig ⚡
* [**thrash**](https://github.com/TylerBrock/thrash) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2019-12-31 – HTTP Micro Benchmarker, written in Go (`golang`)
* [**pywrkr**](https://github.com/kurok/pywrkr) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-19 – `ab`/`wrk`-inspired benchmarking CLI with latency percentiles, virtual-user simulation, rate limiting, traffic profiles, HAR import, and SLO/threshold checks for CI, written in `Python`
* [**ab**](http://en.wikipedia.org/wiki/ApacheBench) – slow in single-threaded can be made more efficient by [`taskset`](https://man7.org/linux/man-pages/man1/taskset.1.html), written in `C`
* [**Bencher**](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI
* [**curl-loader**](http://curl-loader.sourceforge.net/) – performance loading of various application services and traffic generation, written in `C`
* [**gatling**](http://gatling.io) – High performance load testing framework based on Scala, Akka and Netty, written in `Scala`
* [**h2load**](https://nghttp2.org/documentation/h2load-howto.html) - benchmarking tool for HTTP/2 and HTTP/1.1. It supports SSL/TLS and clear text for all supported protocols, written in `C`/`C++`
* [**jmeter**](http://jmeter.apache.org/) – Apache  JMeter™, pure application designed to load test performance both on static and dynamic resources, written in `Java`
* [**locust**](https://locust.io/) – easy-to-use, distributed load testing tool with real-time web UI. Simulates a swarm of concurrent users, the behavior of each of them is defined by your python code. Written in `Python`
* [**RapidAPI (Paw)**](https://paw.cloud/) - for Mac is a full-featured HTTP client that lets you test and describe the APIs you build or consume.
* [**siege**](http://www.joedog.org/siege-home/) – multithreaded concurrent connections and slow single-user, written in `C`
* [**tquic\_client**](https://crates.io/crates/tquic_tools) – A high-performance HTTP/3 benchmarking tool, written in `Rust`
* [**tsung**](http://tsung.erlang-projects.org/) – Simulate stress users in order to test the scalability and performance of IP based client/server applications `HTTP`, `WebDAV`, `SOAP`, `PostgreSQL`, `MySQL`, `LDAP` and `Jabber`/`XMPP` servers, written in `Erlang`
* `seq 0 10000 | xargs -P 100 -I {} curl http://localhost:8080/` - Benchmarking in restricted environments, using GNU toolchain

# Toolkit for testing/debugging HTTP(S) and restAPI (RESTful)

* [**hoppscotch**](https://github.com/hoppscotch/hoppscotch) ⭐ 80,091 | 🐛 802 | 🌐 TypeScript | 📅 2026-08-24 - API request builder
* [**curl**](https://github.com/curl/curl) ⭐ 42,676 | 🐛 36 | 🌐 C | 📅 2026-08-24 – Powerful features command-line tool for transferring data specified with URL syntax, written in `C`
  * [Online curl command line builde](https://curlbuilder.com/)
* [**httpie**](https://github.com/jkbrzt/httpie) ⭐ 38,448 | 🐛 332 | 🌐 Python | 📅 2024-12-17 – client, user-friendly curl replacement with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, written in `Python`
* [**jq**](https://github.com/stedolan/jq) ⭐ 35,478 | 🐛 467 | 🌐 C | 📅 2026-08-23 – is a lightweight and flexible command-line JSON processor, written in `C`
* [**hurl**](https://github.com/Orange-OpenSource/hurl) ⭐ 19,157 | 🐛 206 | 🌐 Rust | 📅 2026-08-24 - Hurl is a command line tool that runs HTTP requests defined in a simple plain text format
* [**Keploy**](https://github.com/keploy/keploy) ⭐ 18,414 | 🐛 704 | 🌐 Go | 📅 2026-08-24 - Open source ai testing platform that records user traffic as test cases and mocks (infrastructure virtualisation along withDBs) and uses AI to expand the API, schema and code coverage of the backend regression test suite. It also auto-generates tests with assertions and is used for contract testing, functional and performance testing using AI.
* [**curlconverter**](https://github.com/NickCarneiro/curlconverter) ⭐ 8,169 | 🐛 43 | 🌐 TypeScript | 📅 2026-03-10 – convert curl commands to python, javascript, php
* [**xh**](https://github.com/ducaale/xh) ⭐ 8,039 | 🐛 38 | 🌐 Rust | 📅 2026-08-23 – Yet another [HTTPie](https://httpie.org) clone, written in `Rust`
* [**httpstat**](https://github.com/reorx/httpstat) ⭐ 6,215 | 🐛 9 | 🌐 Python | 📅 2026-04-08 - It's like curl -v, with colours
* <https://github.com/marmelab/awesome-rest> ⭐ 3,907 | 🐛 15 | 📅 2026-05-13
* [**bat**](https://github.com/astaxie/bat) ⭐ 2,564 | 🐛 29 | 🌐 Go | 📅 2022-10-29 – Go implement CLI, cURL-like tool for humans, written in Go (`golang`)
* <https://github.com/stepci/awesome-api-clients> ⭐ 1,106 | 🐛 3 | 📅 2026-05-11
* [**agent-qa**](https://github.com/vostride/agent-qa) ⭐ 961 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 – Self-improving QA agent for natural-language web and mobile regression tests, written in `TypeScript`
* [**DeepfakeHTTP**](https://github.com/xnbox/DeepfakeHTTP) ⭐ 526 | 🐛 8 | 🌐 Java | 📅 2022-08-05 – is a web server that uses HTTP dumps as a source for responses, written in `Java`
* [**jaggr**](https://github.com/rs/jaggr) ⭐ 484 | 🐛 2 | 🌐 Go | 📅 2024-08-29 – JSON Aggregation CLI, Jaggr can be used to integrate [vegeta](https://github.com/tsenart/vegeta) ⭐ 25,164 | 🐛 122 | 🌐 Go | 📅 2026-02-16 with [jplot](https://github.com/rs/jplot) ⭐ 1,178 | 🐛 10 | 🌐 Go | 📅 2025-10-20, written in Go (`golang`)
* <https://github.com/mrmykey/awesome-http-clients> ⭐ 165 | 🐛 1 | 📅 2026-08-09
* [**Bruno**](https://www.usebruno.com/) – is a Fast and Git-Friendly Opensource API client
* [**HTTPie Desktop**](https://httpie.io/desktop) – HTTPie Desktop is a cross-platform API testing client for humans. Use it to test REST, GraphQL, and HTTP APIs painlessly.
* [**HttpMaster**](https://www.httpmaster.net) - Professional desktop tool for HTTP testing and debugging.
* [**curlie**](https://curlie.io) – If you like the interface of [HTTPie](https://httpie.org) but miss the features of [curl](https://curl.haxx.se), curlie is what you are searching for. Curlie is a drop-in replacement for `httpie` that use `curl` to perform operations, written in Go (`golang`)
* [**insomnia**](https://insomnia.rest/) - simple, beautiful, and free Desktop REST API client (`Mac`, `Windows`, and `Linux`)
* [**Proxyman**](https://proxyman.io/) - Capture HTTP(s) in a few clicks. Best-in-class native macOS app to capture, decrypt, and mock your HTTP(s) requests/ responses with powerful debugging tools.
* [**Webhook Debugger, Logger & API Mocking Suite**](https://apify.com/ar27111994/webhook-debugger-logger) – Enterprise-grade tool for testing, debugging, and logging incoming webhooks in real-time, written in Node.js.
* [**Yaak**](https://yaak.app/) – API client for modern developers, Call REST, GraphQL, SSE, and gRPC APIs from a simple and intuitive app.

# SaaS/PaaS

* [**BlazeMeter**](https://blazemeter.com/) – offers a cross-enterprise test automation framework for the entire technical team (developers, devops, ops and QA) throughout the product development lifecycle. Run continuous or 'on demand' testing for APIs, mobile apps and websites. Run from the cloud, on-premise or as a hybrid solution. Use with JMeter & Selenium WebDriver & integrate with your existing CI, CD & APM tools.
* [**NewRelic**](http://newrelic.com/) – software analytics tool suite used by developers, ops, and software companies to understand how your applications are performing in development and production
* [**GetPageSpeed Amplify**](https://amplify.getpagespeed.com/) – Visually identify performance bottlenecks, overloaded servers, or potential DDoS attacks. Improve and optimize NGINX performance with intelligent advice and recommendations. Get alerts when something is wrong with the delivery of your application. Plan capacity and performance for web applications. Keep track of systems running NGINX. *(NGINX Amplify was [retired on January 31, 2026](https://blog.nginx.org/blog/nginx-amplify-endoflife). GetPageSpeed Amplify is a compatible replacement.)*
* [**k6.io**](https://k6.io/) - Open source load testing tool and SaaS for engineering teams. Powerful scripting and lots of CI/CD integration.
* [**RedLine13**](https://redline13.com/) - Cloud Based Load Testing to run JMeter, Gatling, or custom code load test plans at scale using low cost instance pricing.
* [**tracetest**](https://tracetest.io) – Use OpenTelemetry for testing and synthetic monitoring. Write your tests using `YAML`

# Additional tools and inspiration collection

* <https://github.com/aliesbelik/load-testing-toolkit> ⭐ 252 | 🐛 1 | 📅 2026-07-01

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
