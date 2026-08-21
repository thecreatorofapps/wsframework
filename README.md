
# WSFramework
[![Maintainence](https://badges.ws/maintenance/yes/2026)](https://github.com/thecreatorofapps/wsframework/commits/main) [![Polyform Noncommercial](https://badges.ws/badge/License-Polyform%20Noncommercial-yellow.svg)](https://polyformproject.org/licenses/noncommercial)

Get rid of all of the shenanigans of WebSockets. Just simply use this framework
## Authors

- [@thecreatorofapps](https://www.github.com/thecreatorofapps)

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

