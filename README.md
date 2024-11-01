<!DOCTYPE html>
<html>
<head>
    <title>LuxShop</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>LuxShop</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">ホーム</a></li>
                <li><a href="#">商品</a></li>
                <li><a href="#">サポート</a></li>
                <li><a href="#">コンタクト</a></li>
                <li><a href="#">カート</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="検索...">
            <button>検索</button>
        </div>
    </header>
    <main>
        <section class="hero">
            <h2>最新の家電製品を手に入れよう</h2>
            <p>最新技術、最高のデザイン。</p>
            <button>今すぐ購入</button>
        </section>
        <section class="products">
            <h2>おすすめ商品</h2>
            <div class="product">
                <img src="images/microwave.jpg" alt="電子レンジ">
                <h3>電子レンジ</h3>
                <p>¥30000</p>
                <button>カートに追加</button>
            </div>
            <div class="product">
                <img src="images/washing_machine.jpg" alt="洗濯機">
                <h3>洗濯機</h3>
                <p>¥50000</p>
                <button>カートに追加</button>
            </div>
            <div class="product">
                <img src="images/refrigerator.jpg" alt="冷蔵庫">
                <h3>冷蔵庫</h3>
                <p>¥80000</p>
                <button>カートに追加</button>
            </div>
            <div class="product">
                <img src="images/tv.jpg" alt="テレビ">
                <h3>テレビ</h3>
                <p>¥60000</p>
                <button>カートに追加</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 LuxShop</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #fff;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #fff;
    color: #333;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    border-bottom: 2px solid #d4af37; /* 金色のライン */
}

.logo h1 {
    margin: 0;
    font-size: 24px;
}

nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    gap: 15px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #d4af37; /* 金色 */
    text-decoration: none;
    font-size: 16px;
}

.search-bar {
    display: flex;
    align-items: center;
}

.search-bar input {
    padding: 5px;
    font-size: 16px;
    border: 1px solid #ddd;
    border-radius: 5px 0 0 5px;
}

.search-bar button {
    padding: 5px 10px;
    font-size: 16px;
    border: 1px solid #d4af37; /* 金色 */
    background-color: #d4af37; /* 金色 */
    color: #fff;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
}

.hero {
    background-color: #fff;
    color: #333;
    text-align: center;
    padding: 50px 20px;
    border-bottom: 2px solid #d4af37; /* 金色のライン */
}

.hero h2 {
    margin: 0;
    font-size: 36px;
}

.hero p {
    font-size: 18px;
}

.hero button {
    background-color: #d4af37; /* 金色 */
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

.products {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px;
}

.product {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    text-align: center;
    width: 45%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 10px 0;
}

.product img {
    width: 100%;
    height: auto;
}

.product h3 {
    margin: 15px 0;
}

.product p {
    font-size: 18px;
    font-weight: bold;
    color: #d4af37; /* 金色 */
}

.product button {
    background-color: #d4af37; /* 金色 */
    color: #fff;
    border: none;
    padding: 10px;
    cursor: pointer;
}

footer {
    background-color: #fff;
    color: #333;
    text-align: center;
    padding: 10px;
    border-top: 2px solid #d4af37; /* 金色のライン */
}
