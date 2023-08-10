:warning:  Warning
> I don't have any experience in Quality assurance field in Software Engineering. I have limited experience in writing unit and integration tests for some kind of TDD :smiley:. So, it will be heavily dev's pov.

:exclamation: Important Note
> Work in Progress. In any case if I miss something please feel free to create an issue. I would love to explore that side as well.


# Web Application testing
It is a guide which tries to cover few facets of web application testing. 

> Motto : "If you haven't tested it, it won't work the way you intended it." 

As W. Edwards quoted "In God we trust. All others must bring data.” 

## Modules
- HTTP API Contract
- Performance
- UI


### HTTP API Contract tests
There were many good candidates :
- [Karate](https://github.com/karatelabs/karate)
- [RestAssured](https://github.com/rest-assured/rest-assured)
- [Newman](https://www.npmjs.com/package/newman)

I decided that I would go with Karate for its simplicity and wide range of native support. Every decision brings its pros and cons.

### Performance testing

HTTP API load testing
- Old School : [Apache Benchmark](https://httpd.apache.org/docs/2.4/programs/ab.html)
- People like me who are still wondering : [K6](https://github.com/grafana/k6) :expressionless:
- New School : [Oha](https://github.com/hatoo/oha) - It is written in Rust. :joy:

### UI 

- [Playwright](https://playwright.dev/) - Automation testing for web based application
- [Appium](http://appium.io/docs/en/2.0/) - iOS and Android