# News Site

## Install

```bash
$ npm install
```

You see security alert like below after installing. 
But do not worry about it because firebase team say [it does not directly affect firebase](https://github.com/firebase/firebase-tools/issues/769#issuecomment-400376070).    
```text
┌───────────────┬──────────────────────────────────────────────────────────────┐
│ Low           │ Prototype Pollution                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Package       │ lodash                                                       │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Patched in    │ >=4.17.5                                                     │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Dependency of │ firebase-tools [dev]                                         │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ Path          │ firebase-tools > @google-cloud/functions-emulator >          │
│               │ cli-table2 > lodash                                          │
├───────────────┼──────────────────────────────────────────────────────────────┤
│ More info     │ https://nodesecurity.io/advisories/577                       │
└───────────────┴──────────────────────────────────────────────────────────────┘
```
