# dts-google-apps-script-analytics

d.ts files generator for [Google Apps Script](https://developers.google.com/apps-script/) [Analytics Service](https://developers.google.com/apps-script/advanced/analytics).

## How to generate `d.ts` files and update the `GoogleAppsScriptAnalytics` Type Definition

Download a copy of the latest copy of the Analytics Script Script Editor autocomplete json document [1]

The API definitions and documents are from Google Apps Script Script Editor autocomplete json document [1].

```sh
cat Analytics_v3.json | node generator.js # Pipe the autocomplete json document from Script Editor into the generator. New d.ts files are written to google-apps-script-analytics/
```

Create a PR to [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) with these updated files.

## DefinitelyTyped

You may want to use [definitions on DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/google-apps-script) unless you want to generate d.ts files manually.


[1] https://script.google.com/a/[user]/macros/autocomplete/dep/apiary/analytics/v3 (login required)