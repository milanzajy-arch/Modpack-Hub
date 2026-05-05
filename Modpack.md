<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modpack Hub</title>
    <style>
        body {
            background-color: white;
            color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Judul */
        .title {
            font-size: 32px;
            font-weight: bold;
            margin-top: 20px;
        }

        /* Kolom pencarian */
        .search-box {
            margin: 20px auto;
        }

        .search-box input {
            width: 250px;
            padding: 8px;
            font-size: 14px;
        }

        /* Container download */
        .download-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr); /* 2 kolom */
            gap: 10px;
            width: 300px;
            margin: auto;
        }

        /* Box download */
        .download-box {
            background-color: black;
            color: white;
            padding: 10px;
            font-size: 12px;
            border-radius: 6px;
        }

        .download-box a {
            color: #00aaff;
            text-decoration: none;
            font-size: 11px;
        }

        .download-box a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Judul -->
    <div class="title">Modpack Hub</div>

    <!-- Kolom Pencarian -->
    <div class="search-box">
        <input type="text" placeholder="Cari modpack...">
    </div>

    <!-- Kolom Download -->
    <div class="download-container">
        <div class="download-box">
            <div>Vulkan 1.21</div>
            <a href="https://www.mediafire.com/file/99zr94p26d1gvpe/Fabulously_Vulkanium_1.21.0.18.4_By_Milz.mrpack/file" target="_blank">
                Download
            </a>
        </div>

        <!-- Bisa ditambah lagi biar jadi 2 baris -->
        <div class="download-box">
            <div>Sodium 26.1</div>
            <a href="https://www.mediafire.com/file/9cahase2nu3ff7u/26.1+modpack+by+milz.mrpack/file" target="_blank"> Download
            </a>
        </div>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>By Milz</title>
    <style>
        .by-milz {
            position: absolute;
            top: 5px;
            right: 10px;
            font-size: 10px; /* super kecil */
            font-weight: normal;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>

<div class="by-milz">By Milz</div>

</body>
</html>
