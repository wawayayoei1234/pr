# Conditional Statements

### If-Then-Else

---

## Agenda

@ol
* Basic `if` statement syntaxs
* Ternary Operator
* Demo
@olend

---

@title[Example]

## Example

```

if( เงื่อนไข )
{
  // ทำใน block นี้ถ้าเงื่อนไขเป็นจริง
}


if( เงื่อนไข )
{
  // ทำใน block นี้ถ้าเงื่อนไขเป็นจริง
}
else
{
  // ทำใน block นี้ถ้าเงื่อนไขเป็นเท็จ
}

Exception cases
6.ผู้ใช้ถอนเงินสำเร็จแต่ระบบไม่สามารถตัดเงินออกจากบัญชีได้ ระบบทำการแจ้งเตือน
```
@[1-4](Normal cases: กรณีที่เจอได้บ่อยๆ 80~90%)
@[6-8](Alternative cases: กรณีที่นานๆจะเกิดขึ้นที หรือเคสขอบ)
@[10-11](Exception cases: กรณีข้อผิดพลาดที่ยอมรับไม่ได้)

---
