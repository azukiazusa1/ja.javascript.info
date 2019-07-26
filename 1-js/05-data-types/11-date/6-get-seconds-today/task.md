importance: 5

---

# 今日何秒経過しましたか？

今日の開始から秒数を返す関数 `getSecondsToday()` を書いてください。

例えば、今 `10:00 am` で夏時間のシフトがない場合:

```js
getSecondsToday() == 36000 // (3600 * 10)
```

関数は任意の日で動作する必要があります。つまり、"今日" のハードコードを持つべきではありません。