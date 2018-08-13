1. Have `yarn` installed (npm might work as well, didn't check)
1. `yarn install`
1. `yarn bootstrap`
1. `yarn watch`

You can see that of 3 identical packages only the 1st one fails with `Cannot find module '@watch-fail/lib'`.

If you `cd packages/pkg1` and `yarn build` or `yarn watch` there you'll that things work as expected.