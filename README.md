mithril-node-render
===================
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/StephanHoyer/mithril-node-render?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Use mithril views to render server side

Usage
-----

```javascript
var m = require('mithril');
var render = require('mithril-node-render');

render(m('span', 'huhu')) //<span>huhu</span>
```