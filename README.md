<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Link Bio | Premium Experience</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>

    <style>
        :root {
            --bg: #0d1117; /* GitHub Dark Theme */
            --accent-git: #2f81f7;
            --accent-bibit: #00e676;
            --glass: rgba(255, 255, 255, 0.03);
            --glass-border: rgba(255, 255, 255, 0.1);
            --text-main: #c9d1d9;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background: var(--bg);
            color: var(--text-main);
            overflow-x: hidden;
        }

        /* GitHub Corner Animation */
        .github-corner:hover .octo-arm { animation: octocat-wave 560ms ease-in-out; }
        @keyframes octocat-wave { 0%, 100% { transform: rotate(0); } 20%, 60% { transform: rotate(-25deg); } 40%, 80% { transform: rotate(10deg); } }

        /* Animated Background Particles */
        .bg-glow {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at 50% 50%, rgba(47, 129, 247, 0.05), transparent);
            z-index: -1;
        }

        .container { max-width: 450px; margin: 0 auto; padding: 80px 20px 40px; }

        /* PROFILE */
        .profile { text-align: center; margin-bottom: 35px; }
        .avatar {
            width: 100px; height: 100px; border-radius: 50%;
            border: 2px solid var(--accent-git); padding: 5px;
            margin-bottom: 15px; transition: transform 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .avatar:hover { transform: scale(1.1) rotate(5deg); }

        /* CONTENT GRID (2X2) */
        .stats-grid {
            display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 25px;
        }
        .stat-card {
            background: var(--glass); border: 1px solid var(--glass-border);
            padding: 20px; border-radius: 20px; text-align: center;
            backdrop-filter: blur(10px); transition: 0.3s;
        }
        .stat-card:hover { border-color: var(--accent-git); background: rgba(47, 129, 247, 0.05); }
        .stat-card i { font-size: 1.5rem; display: block; margin-bottom: 8px; }
        .stat-card h4 { font-size: 0.8rem; color: #8b949e; }
        .stat-card p { font-size: 1.1rem; font-weight: 800; color: #fff; }

        /* BUTTONS */
        .links { display: flex; flex-direction: column; gap: 12px; margin-bottom: 30px; }
        .btn {
            background: var(--glass); border: 1px solid var(--glass-border);
            padding: 16px; border-radius: 15px; color: #fff; text-decoration: none;
            font-weight: 600; text-align: center; transition: 0.3s;
        }
        .btn:hover { background: var(--accent-git); border-color: var(--accent-git); color: #fff; }

        /* BIBIT CARD */
        .bibit-card {
            background: rgba(0, 230, 118, 0.02); border: 1px solid rgba(0, 230, 118, 0.15);
            padding: 25px; border-radius: 25px;
        }
        .bibit-header { display: flex; align-items: center; gap: 12px; margin-bottom: 15px; }
        .bibit-icon { width: 40px; height: 40px; background: var(--accent-bibit); border-radius: 10px; display: flex; align-items: center; justify-content: center; }
        .bibit-icon svg { width: 22px; fill: #000; }
        
        .copy-box {
            background: rgba(0, 230, 118, 0.05); border: 1px dashed var(--accent-bibit);
            padding: 15px; border-radius: 12px; text-align: center; cursor: pointer; margin-top: 15px;
        }
        .code { font-size: 1.2rem; font-weight: 800; color: var(--accent-bibit); display: block; }

        footer { text-align: center; padding: 40px; font-size: 0.7rem; color: #484f58; letter-spacing: 2px; }
        .reveal { opacity: 0; transform: translateY(20px); }
    </style>
</head>
<body>

    <div class="bg-glow"></div>

    <a href="https://github.com/username" class="github-corner" aria-label="View source on GitHub">
        <svg width="80" height="80" viewBox="0 0 250 250" style="fill:var(--accent-git); color:#0d1117; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.5 120.5,78.5 C111.9,76.1 118.7,80.8 118.7,80.8 C124.7,83.0 125.7,83.0 125.7,83.0 C128.2,76.4 134.3,72.3 139.5,73.7 C147.0,77.9 149.0,82.1 148.7,81.0 C146.9,77.7 140.4,75.6 140.2,75.6 C138.9,74.1 141.2,75.3 141.2,75.3 C143.4,77.9 146.1,80.9 151.0,81.2 C155.2,81.1 158.5,77.2 158.5,77.2 C160.4,74.1 158.1,70.1 158.1,70.1 C156.9,69.5 152.4,70.1 152.4,70.1 C148.2,70.5 145.8,71.5 144.1,72.7 C139.5,76.5 136.9,78.1 134.1,77.8 C131.5,77.5 129.5,76.0 127.3,74.0 C125.2,72.0 123.0,71.1 120.3,71.1 C117.7,71.1 115.3,72.3 112.5,74.4 L105.5,81.2 C101.4,85.1 100.2,88.9 100.8,92.5 C101.3,96.1 103.7,99.2 107.2,101.3 L112.7,104.5 C118.5,108.0 123.3,108.9 128.3,109.0 Z" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C145.5,98.8 148.0,100.3 150.8,103.3 L159.0,110.3 C162.1,113.3 166.5,114.3 171.2,112.7 C177.0,110.8 181.5,105.7 181.5,100.0 C181.5,94.3 177.0,89.2 171.2,87.3 C166.5,85.7 162.1,86.7 159.0,89.7 L150.8,96.7 C148.0,99.7 145.5,101.2 142.2,101.4 C139.9,101.6 136.9,100.8 133.7,98.4 L119.8,84.6 C118.7,83.5 114.9,84.9 115.0,85.0 L115.0,115.0 Z" fill="currentColor" class="octo-body"></path></svg></a>

    <div class="container">
        
        <div class="profile reveal">
            <img src="https://github.com/identicons/user.png" alt="Avatar" class="avatar">
            <h2 style="color:#fff; font-weight: 800;">Dev Portfolio</h2>
            <p style="color:#8b949e; font-size: 0.9rem;">Fullstack Developer • Open Source</p>
        </div>

        <div class="stats-grid">
            <div class="stat-card reveal">
                <h4>Repositories</h4>
                <p>42</p>
            </div>
            <div class="stat-card reveal">
                <h4>Followers</h4>
                <p>1.2k</p>
            </div>
            <div class="stat-card reveal">
                <h4>Stars</h4>
                <p>850</p>
            </div>
            <div class="stat-card reveal">
                <h4>Contributions</h4>
                <p>300+</p>
            </div>
        </div>

        <div class="links">
            <a href="#" class="btn reveal">VIEW PROJECTS</a>
            <a href="#" class="btn reveal">DOWNLOAD CV</a>
        </div>

        <div class="bibit-card reveal">
            <div class="bibit-header">
                <div class="bibit-icon">
                    <svg viewBox="0 0 24 24"><path d="M12,2L4.5,20.29L5.21,21L12,18L18.79,21L19.5,20.29L12,2Z"/></svg>
                </div>
                <div>
                    <h3 style="color:var(--accent-bibit); font-size: 1rem;">Developer Invest</h3>
                    <p style="font-size: 0.7rem; color: #8b949e;">Pasif Income untuk Developer</p>
                </div>
            </div>
            <div class="copy-box" onclick="copyRef()">
                <span style="font-size: 0.6rem; color: var(--accent-bibit); font-weight: 700;">REFERRAL KODE</span>
                <span class="code" id="refCode">GITCUAN2026</span>
            </div>
        </div>

        <footer>
            <p>© 2026 BUILT WITH GSAP • GITHUB PAGES</p>
        </footer>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", () => {
            gsap.to(".reveal", {
                opacity: 1,
                y: 0,
                duration: 0.8,
                stagger: 0.1,
                ease: "power2.out"
            });
        });

        function copyRef() {
            const code = document.getElementById('refCode').innerText;
            navigator.clipboard.writeText(code);
            alert("Kode Referral " + code + " berhasil disalin!");
        }
    </script>
</body>
</html>
