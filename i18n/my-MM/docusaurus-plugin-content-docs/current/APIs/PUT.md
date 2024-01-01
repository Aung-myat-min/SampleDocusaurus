---
sidebar_position: 3
---

# PUT

## အသုံးပြုသူအား ID ဖြင့် အပ်ဒိတ်လုပ်ပါ။

### အဆုံးမှတ်

`PUT /users/:id`

### ဖော်ပြချက်

အသုံးပြုသူတစ်ဦး၏ ID ဖြင့် သီးခြားအသေးစိတ်အချက်အလက်များကို အပ်ဒိတ်လုပ်ပါ။

### Parameters

- `:id` (integer) - User ID

### တောင်းဆိုချက်

အပ်ဒိတ်လုပ်ထားသော အသုံးပြုသူအသေးစိတ်များကို ကိုယ်စားပြုသည့် JSON အရာဝတ္ထု။

```json
{
  "name": "Updated Name",
  "email": "updated.email@example.com"
}
```

## ဥပမာ

```bash
curl -X PUT -H "Content-Type: application/json" -d '{"name":"Updated Name","email":"updated.email@example.com"}' http://localhost:3000/users/1
```
