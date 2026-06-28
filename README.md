# blockchain
```
app.run(host='127.0.0.1', port=5000)
```
در آخر با دستور فوق وب اپلیکیشن را اجرا می‌کنیم. در مرورگر خود آدرس زیر را وارد می‌‎کنیم:

```
Localhost:5000
```
سپس آدرس‌هایی را که در کدها ایجاد کردیم، به ترتیب و مرحله به مرحله در انتهای آدرس وارد می‌کنیم. نتیجۀ سیستم بلاکچین ما به این صورت خواهد بود:
```
{
"index":2,
"message":"A block is MINED",
"previous_hash":"2d83a826f87415edb31b7e12b35949b9dbf702aee7e383cbab119456847b957c",
"proof":533,
"timestamp":"2020-06-01 22:47:59.309000"
}
```
خروجی آدرس mine_block
```
{
"chain":[{"index":1,
"previous_hash":"0",
"proof":1,
"timestamp":"2020-06-01 22:47:05.915000"},{"index":2,
"previous_hash":"2d83a826f87415edb31b7e12b35949b9dbf702aee7e383cbab119456847b957c",
"proof":533,
"timestamp":"2020-06-01 22:47:59.309000"}],
"length":2
}
```
خروجی آدرس get_chain
```
{"message":"The Blockchain is valid."}
خروجی آدرس valid
```

salaaammmm
bayyyyyy