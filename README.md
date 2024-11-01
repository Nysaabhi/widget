# widget
<html>
<head>
    <style>
        .ticker-container {
            width: 75%;
            height: 140px;
            background-color: transparent;
            border-radius: 8px;
            padding: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 20px;
            overflow: hidden;
            position: relative;
        }
        
        /* Hide Plasbit branding */
        .ticker-container iframe {
            transform: scale(1.1); /* Slight zoom to cover branding */
            clip-path: inset(0px 0px 50px 0px); /* Hide the bottom area with branding */
        }
    </style>
</head>
<body>
    <div class="ticker-container">
        <div id="crypto_ticker"
             data-coins="BTC,ETH,USDT,SOL,USDC,XRP,DOGE,ADA,SHIB,AVAX,LINK"
             data-cards=""
             data-rss=""
             data-theme="transparent"
             data-text="#1a1c1b"
             data-button="#0581de"
             data-vertical="false"
             data-coin="BTC"
             data-price="USD"
             data-crypto-amount="1"
             data-switch-mode="false"
             data-currency-amount="1"
             data-language="en">
        </div>
    </div>
    <script src="https://img.plasbit.com/widget/js/crypto-price-ticker.js"></script>
</body>
