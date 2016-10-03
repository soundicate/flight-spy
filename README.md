# FlightSpy
[![Flight Spy](http://business.skyscanner.net/Content/images/logo/ssf-white-color.png)](http://www.skyscanner.net)

[![Build Status](https://travis-ci.org/jeancsil/flight-spy.svg?branch=master)](https://travis-ci.org/jeancsil/flight-spy)
[![Latest Stable Version](https://img.shields.io/badge/packagist-flight--spy-blue.svg)](https://packagist.org/packages/jeancsil/flight-spy)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/jeancsil/flight-spy/master/LICENSE) [![Twitter](https://img.shields.io/twitter/url/https/github.com/jeancsil/flight-spy.svg?style=social)](https://twitter.com/intent/tweet?text=Watch the best fare for your next trip!&url=http://github.com%2Fjeancsil%2Fflight-spy)


Provides console commands to keep watching flight deals for you!


## Install with docker (recommended)
Rename the `src/Resources/parameters.yml.dist` to `parameters.yml` and update the content accordingly.

Change the `src/Resources/watch.json` file with all the flights, dates, budged etc.. you are looking for.

`$ git clone https://github.com/jeancsil/flight-spy.git`

`$ docker build -t jeancsil/flight-spy .`

`$ docker run -t -i jeancsil/flight-spy`

## Documentation

FlightSpy will look for the best deals for you from 5 to 5 minutes and will let you know by e-mail if there is a good fare for you next trip!

## Support

For general support and questions, find me on Twitter as [@jeancsil](http://twitter.com./jeancsil).

Bugs and suggestions: [open a ticket](https://github.com/jeancsil/flight-spy/issues).

## License

This package is available under the [MIT license](LICENSE).
