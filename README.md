<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>价值元素金字塔</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <h1>价值元素金字塔</h1>
    <div id="pyramid-container">
        <!-- 金字塔结构将由JavaScript动态生成 -->
    </div>
    <div class="bottom-container">
        <div id="element-description">
            <!-- 元素描述将在这里显示 -->
        </div>
        <div id="industry-selector">
            <label for="industry">选择行业：</label>
            <select id="industry">
                <option value="">请选择</option>
                <option value="apparel">服装零售</option>
                <option value="discount">折扣零售</option>
                <option value="food">食品饮料</option>
                <option value="grocery">杂货店</option>
                <option value="tv">电视服务</option>
                <option value="smartphones">智能手机</option>
                <option value="brokerage">经纪服务</option>
                <option value="banking">消费者银行</option>
                <option value="insurance">汽车保险</option>
                <option value="creditcards">信用卡</option>
            </select>
        </div>
        <div id="industry-summary">
            <!-- 行业总结将在这里显示 -->
        </div>
    </div>
    <script src="js/script.js"></script>
</body>
</html>
