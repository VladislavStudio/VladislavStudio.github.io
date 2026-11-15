<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>имясайта</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz@14..32&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            padding: 2rem 1rem;
            background: #f8fafc;
        }
        .site-container {
            max-width: 1000px;
            width: 100%;
            margin: 0 auto;
            border-radius: 24px;
            padding: 2.5rem;
            box-shadow: 0 10px 40px rgba(0,0,0,0.06);
            transition: background 0.3s, color 0.3s;
        }
        .theme-light { background: #ffffff; color: #1e293b; }
        .theme-dark { background: #0f172a; color: #e2e8f0; }
        .theme-forest { background: #f0fdf4; color: #14532d; }
        .theme-sunset { background: #fff7ed; color: #7c2d12; }

        .site-block { margin-bottom: 1.5rem; position: relative; }
        .site-block:last-child { margin-bottom: 0; }
        .site-block h1, .site-block h2, .site-block h3 { margin-bottom: 0.5rem; }
        .site-block p { margin-bottom: 0.5rem; line-height: 1.6; }
        .site-block img { max-width: 100%; border-radius: 12px; display: block; }
        .site-block hr { border: none; margin: 1rem 0; }
        .site-block .card-block { border-radius: 16px; padding: 1.5rem; border: 1px solid rgba(0,0,0,0.08); }
        .theme-dark .site-block .card-block { background: #1e293b !important; border-color: #334155; }

        .video-wrapper { position: relative; width: 100%; background: #000; border-radius: 12px; overflow: hidden; }
        .video-wrapper iframe { width: 100%; height: 100%; border: 0; display: block; }
        .video-wrapper.ratio-16-9 { aspect-ratio: 16 / 9; }
        .video-wrapper.ratio-4-3 { aspect-ratio: 4 / 3; }
        .video-wrapper.ratio-1-1 { aspect-ratio: 1 / 1; }
        .video-link-placeholder {
            display: flex; flex-direction: column; align-items: center; justify-content: center;
            padding: 2rem; background: rgba(0,0,0,0.05); border-radius: 12px; text-align: center;
            color: inherit; text-decoration: none; border: 1px dashed currentColor;
        }
        .video-link-placeholder i { font-size: 2rem; margin-bottom: 0.5rem; opacity: 0.6; }

        @media (max-width: 640px) {
            body { padding: 1rem 0.5rem; }
            .site-container { padding: 1.5rem; border-radius: 16px; }
            .site-block h1 { font-size: 1.8rem !important; }
        }
    </style>
</head>
<body>
    <div class="site-container theme-light">
        <div class="site-block" data-type="hero"><h1 style="font-size:2.5rem;font-weight:700;margin-bottom:1rem;text-align:center;color:#0062ff;">Vladislav studio</h1></div>
<div class="site-block" data-type="text"><p style="font-size:1.1rem;line-height:1.6;text-align:center;">Добро пожаловать на сайт Vladislav studio!</p></div>
<div class="site-block" data-type="html-raw"><div style="text-align: center; margin-top: 15px;">
  <a href="https://m.youtube.com/@VladislavStudioRussia" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #e62117; color: #ffffff; text-decoration: none; border-radius: 6px; font-family: Arial, sans-serif; font-weight: bold; transition: background-color 0.3s;">Перейти на YouTube-канал</a>
</div></div>
    </div>
</body>
</html>
