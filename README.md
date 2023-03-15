# Step to Reproduce

```
git clone git@github.com:HomyeeKing/reproduce-mdx-type-check.git

npm ci


```

then go to `src/test.mdx`, you will find it import from `./index`, but w/o type checking :/

that is expect `title` to be string, but got number and no error reported.

but the intellisense is fine :)
