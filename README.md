npm5 bundle dependencies bug
-------

1. Clone this repository
2. Run `npm install`
3. Note that the `package-lock.json` is created
4. Run `npm install` again
5. See that the `package-lock.json` has changed

Looks like there's some funny business caused by `bundleDependencies`.
