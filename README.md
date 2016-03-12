# angular-polyfill
Just put it before angular.js, then everything works fine. Jquery is unnecessary.

```html
<!--[if lt IE 9]>
  <script type="text/javascript" src="/js/custom/angular-polyfill.min.js"></script>
<![endif]-->
<script type="text/javascript" src="/js/angularjs/angular.min.js"></script>
```
Do not put it after es5-shim.js or other polyfill, otherwise you will lost the magic.

###suport version
- angular v1.4.*
- angular-sanitize v1.5.*

###Bug
- not support ng-repeat in <select> tag
