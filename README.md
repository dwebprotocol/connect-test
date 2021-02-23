# @dswarm/connect-test

Create connections with peers in the 'connect-test' topic (Demo).

```
npx @dswarm/connect-test
```

You should see output like:

```
★   ★   ★   ★   ★   ★
  ★   ★   ★   ★   ★
dSwarm Connect-Test
  ★   ★   ★   ★   ★
★   ★   ★   ★   ★   ★

▶ Testing hole-punchability...
✔ Your network is hole-punchable

▶ Joining dSwarm under the sha256('connect-test') topic
ℹ Waiting for connections...

› New connection!
› New connection!
› New connection!
```

That's all it does! It joins the dSwarm under the 'connect-test' topic (hashed by sha256) and then arranges connections. The connections aren't used at all.