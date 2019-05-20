# CSharp

## 字符串转换成时间格式

```csharp
    DateTime dt;
    DateTimeFormatInfo dtFormat = new DateTimeFormatInfo();
    dtFormat.ShortDatePattern = "yyyy-MM-dd";
    dtFormat.ShortTimePattern = "HH:mm:ss";
    dt = Convert.ToDateTime("2018-04-04 23:00:00", dtFormat);
```

## 字符串比大小

```csharp
    if (string.Compare("A","B") > 0)
    {
        //说明"A" 比 "B" 大
    }

    if (string.Compare("A","B") = 0)
    {
        //说明"A" 和 "B" 一样大
    }

    if (string.Compare("A","B") < 0)
    {
        //说明"A" 比 "B" 小
    }
```