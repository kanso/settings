## Settings Package

Uploads the kanso.json file as a CommonJS module under the 'settings' directory. Useful for packages that need access to these values after deployment.

### Install

Add `settings` to your dependencies section in `kanso.json`.

```javascript
...
  "dependencies": {
    "settings": null,
    ...
  }
```

Run `kanso install` to fetch the package.


### Changes log

Jul 19, 2017

0.16 

  - ⚠ Security fix where private data could potentially be included in a ddoc (couchapp). [#3](https://github.com/kanso/settings/issues/3)

