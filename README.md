<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Profile</title>
    <style>
        .terminal {
            font-family: 'Courier New', monospace;
            background-color: #2d2d2d;
            padding: 20px;
            color: #00ff00;
            border-radius: 5px;
            max-width: 600px;
            margin: auto;
        }
        .typing {
            font-weight: bold;
            color: #00ffff;
        }
        body {
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>
    <div class="terminal">
        <h1>Hello, I'm <span class="typing">YouAnChi</span> 👋</h1>
        <p>A passionate <strong>Developer</strong> and <strong>Explorer</strong> of the digital realm.</p>
        <p>I love building things that solve real-world problems and push the boundaries of technology.</p>
        <p>When I'm not coding, you can find me <strong>hiking</strong>, <strong>reading</strong>, or <strong>playing guitar</strong>.</p>
    </div>
    <br>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YouAnChi&size_weight=0.5&count_weight=0.5&langs_count=8" alt="Top Langs">
    <br><br>
    <picture>
        <source media="(prefers-color-scheme: dark)" 
                srcset="https://raw.githubusercontent.com/YouAnChi/YouAnChi/output/github-contribution-grid-snake-dark.svg">
        <source media="(prefers-color-scheme: light)" 
                srcset="https://raw.githubusercontent.com/YouAnChi/YouAnChi/output/github-contribution-grid-snake.svg">
        <img alt="github contribution grid snake animation" 
             src="https://raw.githubusercontent.com/YouAnChi/YouAnChi/output/github-contribution-grid-snake.svg">
    </picture>
    <script>
        const typingText = document.querySelector('.typing');
        let text = 'YouAnChi';
        let i = 0;
        const speed = 100;

        function typeWriter() {
            if (i < text.length) {
                typingText.textContent += text.charAt(i);
                i++;
                setTimeout(typeWriter, speed);
            }
        }

        typeWriter();
    </script>
</body>
</html>
