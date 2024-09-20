# Building

For Electron users, need rebuild with a different V8 version:

```bash
npm rebuild winax --runtime=electron --target=30.1.0 --dist-url=https://electronjs.org/headers --build-from-source
```

Change "--target" value to your electron version.
See also Electron Documentation: [Using Native Node Modules](https://electron.atom.io/docs/tutorial/using-native-node-modules/).

# Versions

| Electron |   Nodejs | Winax |    v8 | Compatible |
| -------: | -------: | ----: | ----: | :--------: |
|  v30.1.0 | v20.11.1 |  v5.2 | v12.6 |     ✅     |
|  v31.6.0 | v20.17.0 |  v5.3 | v12.6 |     ✅     |
|  v32.0.0 | v20.17.0 |  v5.3 | v12.8 |     ❌     |
