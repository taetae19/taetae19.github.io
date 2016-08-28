# em
- 가변단위
- 부모 요소의 사이즈의 영향을 받음
```
body {
	font-size: 14px;
}

div {
	font-size: 1.2em;  // calculated at 14px * 1.2
}
```
```
<body>
    <div>
        Test <!-- 14 * 1.2 = 16.8px -->
        <div>
            Test <!-- 16.8 * 1.2 = 20.16px -->
            <div>
                Test <!-- 20.16 * 1.2 = 24.192px -->
            </div>
        </div>
    </div>
</body>
```