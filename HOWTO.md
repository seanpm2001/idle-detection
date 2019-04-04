# How to use the IdleDetector API

The IdleDetector API is currently available in chrome canaries under a flag:

1) Download chrome canary ([android](https://play.google.com/store/apps/details?id=com.chrome.canary), [desktop](https://www.google.com/chrome/canary/)).
2) Navigate to `chrome://flags` and enable `Experimental Web Platform features`.
3) Navigate to a test page, e.g. https://code.sgo.to/tmp/idle.html
4) Go idle (e.g. stop moving your mouse, typing on your keyboard or lock your screen)

You should see something along the lines of:

```
[4/4/2019, 2:59:54 PM] idle change: active, unlocked
[4/4/2019, 3:00:54 PM] idle change: idle, unlocked
[4/4/2019, 3:01:07 PM] idle change: active, unlocked
[4/4/2019, 3:02:25 PM] idle change: idle, unlocked
[4/4/2019, 3:02:41 PM] idle change: active, unlocked
[4/4/2019, 3:03:56 PM] idle change: idle, unlocked
[4/4/2019, 3:12:56 PM] idle change: idle, locked
[4/4/2019, 3:17:38 PM] idle change: active, unlocked
```