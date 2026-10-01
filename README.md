# usastats

A website with USA statistics.

## Current handoff

This is the historical `japet/usastats` fork, not the separately owned
`USAStats/usastats` repository. Treat it as reference pending an explicit revival
decision. The original setup below is historical documentation, not a verified
supported toolchain: Node 7, Gulp 3, React 15 and TypeScript 2 era declarations
have not been validated on a current runtime.

There is no root lockfile. TypeScript appears both as `^2.0.10` and `latest` in
the manifest, and `npm test` deliberately fails with a placeholder message.
Do not interpret a package install or server launch as a successful test.

Before revival, choose one supported TypeScript/runtime baseline, reconcile the
duplicate declaration, create and review a lockfile, and replace the test
placeholder with isolated build/server tests. Work in a fresh clone of
`https://github.com/japet/usastats.git`; changes to the upstream collaboration
need separate coordination. No dependency modernization or deployment is
included in this handoff.

## Information



### Historical build and install (unverified)

From repo:
```bash
git clone https://github.com/USAStats/usastats.git
npm install
npm start
```

Then, navigate to [http://localhost:3000/](http://localhost:3000/).

### Testing

### Historical compatibility (unverified)

Node v7.0.0+.

# License

Copyright (c) 2016 James Peters and Aaron Roney

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
