<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Silk & Petal Journal</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;1,500&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        :root {
            --petal-pink: #F7C8D0;
            --deep-blush: #E06C9F;
            --off-white: #FFF9FA;
            --soft-charcoal: #4A4A4A;
        }

        body {
            background-color: var(--petal-pink);
            background-image: radial-gradient(circle, #ffffff 1px, transparent 1px);
            background-size: 25px 25px; /* Subtle polka dot texture */
            font-family: 'Montserrat', sans-serif;
            color: var(--soft-charcoal);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }

        .blog-container {
            background: var(--off-white);
            width: 90%;
            max-width: 450px;
            padding: 40px 20px;
            border-radius: 30px;
            box-shadow: 0 15px 35px rgba(224, 108, 159, 0.2);
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.8);
        }

        .profile-area img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid var(--petal-pink);
            padding: 5px;
            margin-bottom: 20px;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-weight: 500;
            font-size: 2rem;
            margin: 0 0 10px 0;
            color: var(--deep-blush);
        }

        p.description {
            font-size: 0.9rem;
            line-height: 1.6;
            margin-bottom: 30px;
            padding: 0 15px;
            color: #777;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-card {
            background: #fff;
            padding: 15px;
            border-radius: 15px;
            text-decoration: none;
            color: var(--soft-charcoal);
            font-weight: 400;
            border: 1px solid var(--petal-pink);
            transition: all 0.3s ease;
        }

        .link-card:hover {
            background: var(--petal-pink);
            color: white;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(247, 200, 208, 0.6);
        }

        .footer-sparkle {
            margin-top: 30px;
            font-size: 1.2rem;
            color: var(--petal-pink);
        }
    </style>
</head>
<body>

    <div class="blog

