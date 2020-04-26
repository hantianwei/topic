# 第一章

> 测试。。。

```java
    private static boolean action31(String value1, String value2) {
        if (value1.length() != value2.length()) {
            return false;
        }
        int num1 = 0, num2 = 0;
        for (int i = 0; i < value1.length(); i++) {
            num1 += value1.charAt(i);
            num2 += value2.charAt(i);
        }
        return num1 == num2;
    }
```

