# HTML_QuickForm

This forks updates the `require_once` paths to relative links so we are using other composer dependencies
and not PEAR dependencies, if they are not installed.

This means you should require the following Composer dependencies;

```json
"pear/pear": "^1.10",
"pear/html_common": "dev-master",
"pear/html_quickform": "^3.2.20"
```

You should add the following to your composer.json repositories;

```json
"repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/pear/HTML_Common"
    },
    {
      "type": "vcs",
      "url": "https://github.com/Ricardo-EE/HTML_QuickForm"
    }
  ]
```
