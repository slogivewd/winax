For Electron users, need rebuild with a different V8 version:

```
npm rebuild winax --runtime=electron --target=30.1.0 --dist-url=https://electronjs.org/headers --build-from-source
```

Change --target value to your electron version.
See also Electron Documentation: [Using Native Node Modules](https://electron.atom.io/docs/tutorial/using-native-node-modules/).
