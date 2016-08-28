# em
- 가변단위
- 부모 요소의 사이즈의 영향을 받지 않음(root-em)
```
<body>
    <div>
        Test <!-- 14 * 1.2 = 16.8px -->
        <div>
            Test <!-- 16.8 * 1.2 = 16.8px -->
            <div>
                Test <!-- 20.16 * 1.2 = 16.8px -->
            </div>
        </div>
    </div>
</body>
```