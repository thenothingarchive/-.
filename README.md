<html>

<head>
    <title>The Nothing Archive</title>

    <style>
        body {
            background: white;
            color: black;
            font-family: Georgia, "Times New Roman", serif;
            margin: 0;
        }

        .page {
            width: 650px;
            max-width: 85%;
            margin: 100px auto;
        }

        .navigation {
            text-align: center;
            margin-bottom: 40px;
            font-size: 16px;
        }

        .navigation a {
            color: blue;
            text-decoration: underline;
            margin: 0 10px;
        }

        .navigation .divider {
            color: black;
        }

        .writing {
            display: flex;
            align-items: stretch;
        }

        .line {
            width: 1px;
            background: black;
        }

        .writing-content {
            flex: 1;
            padding: 0 35px;
            text-align: left;
        }

        .entry {
            margin-bottom: 20px;
        }

        .entry a {
            color: blue;
            text-decoration: underline;
        }

        /* Choppy scrolling text */

        .marquee {
            width: 100%;
            overflow: hidden;
            white-space: nowrap;
            margin-top: 20px;
            margin-bottom: 40px;
            font-size: 20px;
        }

        .marquee span {
            display: inline-block;
            padding-left: 100%;
            animation: choppy-scroll 10s steps(35, end) infinite;
        }

        @keyframes choppy-scroll {
            from {
                transform: translateX(0);
            }

            to {
                transform: translateX(-100%);
            }
        }
    </style>
</head>

<body>

    <div class="marquee">
        <span>Nothing Important Here</span>
    </div>

    <div class="page">

        <div class="navigation">
            <a href="index.html">Home</a>
            <span class="divider">|</span>
            <a href="Cannibal.html">Cannibal</a>
        </div>

        <div class="writing">

            <div class="line"></div>

            <div class="writing-content">

                <div class="entry">
                    <a href="09192026.html">
                        09/19/2026 | the beginning, and hopefully the end soon
                    </a>
                </div>

            </div>

            <div class="line"></div>

        </div>

    </div>

</body>

</html>
