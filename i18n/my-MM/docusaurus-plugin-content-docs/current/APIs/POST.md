---
sidebar_position: 2
---

# POST

## အသုံးပြုသူအသစ်ကို ဖန်တီးပါ။

### အဆုံးမှတ်

`POST /users`

### ဖော်ပြချက်

အသုံးပြုသူအသစ်ဖန်တီးပြီး အသုံးပြုသူအသေးစိတ်အချက်အလက်များကို ပြန်ပေးသည်။

### တောင်းခံလွှာ

အသုံးပြုသူအသစ်ကို ကိုယ်စားပြုသော JSON အရာဝတ္ထု။

```json
{
  "name": "John Doe",
  "email": "john.doe@example.com"
}
```

## ဥပမာ

```bash
curl -X POST -H "Content-Type: application/json" -d '{"name":"John Doe","email":"john.doe@example.com"}' http://localhost:3000/users
```
