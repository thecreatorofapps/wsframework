
# WSFramework
[![Maintainence](https://badges.ws/maintenance/yes/2026)](https://github.com/Archie-Aird/companyport/commits/main) [![MIT License](https://badges.ws/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/)

Get rid of all of the shenanigans of WebSockets. Just simply use this framework
## Authors

- [@Archie-Aird](https://www.github.com/Archie-Aird)

(Contact me via the form to register here)
## Support

For support and general questions, use [this form](https://tally.so/r/eqOylJ).
## Usage/Examples

```javascript
import Server from 'wsframework'

Server.commands.set('time', () => {
    return (new Date()).toISOString()
})

Server.begin()
```

