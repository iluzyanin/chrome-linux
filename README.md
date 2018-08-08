# Chrome for Codeceptjs Puppeteer tests in Linux

This dockerfile is based on official Node image and installs Google Chrome + required dependencies to run Codeceptjs puppeteer tests.

To run the container, call

```
docker run --shm-size=1gb --rm -v ${PWD}:/tests iluzyanin/chrome-linux
```

By default it executes `npm test` command within the container.