<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameZone | Onlayn o‘yinlar</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0b1020;
            color: white;
        }

        header {
            background: #141c32;
            padding: 22px;
            text-align: center;
            border-bottom: 2px solid #19d3da;
        }

        header h1 {
            font-size: 35px;
            color: #19d3da;
        }

        header p {
            margin-top: 8px;
            color: #bbbbdd;
        }

        nav {
            background: #192440;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 12px;
            font-weight: bold;
        }

        nav a:hover {
            color: #19d3da;
        }

        .hero {
            text-align: center;
            padding: 55px 20px;
            background: linear-gradient(135deg, #29205c, #101b38);
        }

        .hero h2 {
            font-size: 38px;
            margin-bottom: 15px;
        }

        .hero span {
            color: #19d3da;
        }

        .hero p {
            color: #ccccdd;
            line-height: 1.7;
        }

        .search {
            display: block;
            width: 90%;
            max-width: 500px;
            margin: 25px auto;
            padding: 14px;
            border-radius: 12px;
            border: 1px solid #19d3da;
            background: #141c32;
            color: white;
            font-size: 16px;
        }

        .games {
            padding: 25px 5%;
        }

        .games h2 {
            text-align: center;
            margin-bottom: 25px;
            font-size: 30px;
        }

        .game-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .game {
            background: #141c32;
            padding: 25px 18px;
            border-radius: 18px;
            text-align: center;
            border: 1px solid #293654;
            transition: 0.3s;
        }

        .game:hover {
            transform: translateY(-6px);
            border-color: #19d3da;
            box-shadow: 0 8px 25px #0005;
        }

        .emoji {
            font-size: 60px;
            margin-bottom: 15px;
        }

        .game h3 {
            margin-bottom: 12px;
        }

        .game p {
            color: #b8c1d9;
            line-height: 1.5;
            min-height: 45px;
        }

        button {
            background: #7c5cff;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 9px;
            cursor: pointer;
            font-size: 15px;
            font-weight: bold;
            margin-top: 15px;
        }

        button:hover {
            background: #19aeb8;
        }

        #gameArea {
            display: none;
            margin: 25px auto;
            padding: 25px;
            width: 90%;
            max-width: 500px;
            background: #192440;
            border-radius: 18px;
            text-align: center;
        }

        #gameArea h2 {
            margin-bottom: 15px;
        }

        #gameArea p {
            margin: 12px 0;
        }

        #xoBoard {
            display: grid;
            grid-template-columns: repeat(3, 75px);
            justify-content: center;
            gap: 6px;
            margin: 20px 0;
        }

        .cell {
            width: 75px;
            height: 75px;
            margin: 0;
            font-size: 30px;
            background: #293654;
        }

