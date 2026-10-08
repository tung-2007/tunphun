
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danh sách tệp khoanh đỏ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .file-box {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px 30px;
            width: 350px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
        }

        .file-box h2 {
            font-size: 18px;
            margin-top: 0;
            margin-bottom: 15px;
            color: #58a6ff;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }

        .file-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .file-item {
            display: flex;
            align-items: center;
            padding: 8px 10px;
            margin-bottom: 6px;
            border-radius: 6px;
            background-color: #21262d;
            transition: background-color 0.2s;
        }

        .file-item:hover {
            background-color: #30363d;
        }

        .file-icon {
            margin-right: 10px;
            font-size: 16px;
        }

        .file-name {
            font-family: monospace;
            font-size: 14px;
            color: #f0f6fc;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="file-box">
        <h2>Danh sách các tệp</h2>
        <ul class="file-list">
            <li class="file-item">
                <span class="file-icon">📄</span>
                <a href="t_i_x_u_game.html" class="file-name">t_i_x_u_game.html</a>
            </li>
            <li class="file-item">
                <span class="file-icon">📄</span>
                <a href="tai_xiu_game_v2 (1).html" class="file-name">tai_xiu_game_v2 (1).html</a>
            </li>
            <li class="file-item">
                <span class="file-icon">📄</span>
                <a href="totinh.html" class="file-name">totinh.html</a>
            </li>
            <li class="file-item">
                <span class="file-icon">📄</span>
                <a href="trang_web_gi_i_thi_u_h_n_i.html" class="file-name">trang_web_gi_i_thi_u_h_n_i.html</a>
            </li>
        </ul>
    </div>

</body>
</html>
