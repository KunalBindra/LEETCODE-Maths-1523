# LEETCODE-Maths-1523
```
low = 3
high = 7
```

Code:

```java
return (high + 1) / 2 - low / 2;
```

---

## 🔍 Step 1: Compute (high + 1) / 2

```
high = 7
high + 1 = 8
8 / 2 = 4        // integer division
```

So,

```
odds from 1 to 7 = 4
```

(Actual odds: 1,3,5,7 → 4 numbers)

---

## 🔍 Step 2: Compute low / 2

```
low = 3
3 / 2 = 1        // integer division, 1.5 → 1
```

This value (1) represents **odds from 1 to (low-1) = 2**
(Actual odds: 1 → just 1 number)

---

## 🔍 Step 3: Final subtraction

```
4 - 1 = 3
```

---

## ✔ Final Answer = 3

### Check manually:

Range [3 to 7] me odd numbers:

```
3, 5, 7 → total 3
```

Matches perfectly! ✔
