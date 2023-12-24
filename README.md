# orbitdb test

ターミナルを4つ起動

1

```bash
node orbitdb1.js 
```

2

```bash
node orbitdb2.js /orbitdb/{address}
```

3

```bash
node orbitdb3.js /orbitdb/{address}
```

4 登録

```bash
curl -X POST http://localhost:3000 -H "Accept: application/json" -H "Content-type: application/json" -d '{ "key" : "key1", "value" : "valu1" }'
```

検索

```bash
curl http://localhost:3002/key1
```
