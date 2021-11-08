## BackstopJS example

This example is using [picsum.photos](https://picsum.photos/) which is a cool site that generate a new random image every time.

---

### Setup
- Use the suggested node version
```
nvm use
```

- Install backstopjs globally
```
npm install -g backstopjs
```

- Install the dependencies
```
yarn
```

### Test

- Test the page for the first time (it will probably fails since there is no baseline to compare):
```
yarn bs-test
```

- You can approve your baseline:
```
yarn bs-approve
```

- Then you can run your text again and see the difference
```
yarn bs-test
```

### Clean-up your workspace

```
./scripts/clean-up.sh
```