
<!--#echo json="package.json" key="name" underline="=" -->
data-loss-preview-pmb
=====================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
You could renew your backups now, or next week. If that disk died tomorrow.
would it really matter? Which other disks would you need to restore your data?
<!--/#echo -->


Usage
-----
see [doc/demo/usage.js](doc/demo/usage.js)
:TODO:

<!--!#include file="test/usage.js" start="  //#u" stop="  //#r"
  outdent="  " code="javascript" -->
```javascript
var data-loss-preview-pmb = require('data-loss-preview-pmb');
D.result  = data-loss-preview-pmb(null);
D.expect('===',           null);
```
<!--/include-->

```bash
$ data-loss-preview-pmb foo
bar
```


<!--#toc stop="scan" -->


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
