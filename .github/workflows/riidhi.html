<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Ridhi Bangaram 🌸</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Quicksand:wght@300;500&display=swap');

        :root {
            --soft-pink: #ffe5ec;
            --deep-pink: #ff85a2;
            --rose-red: #ff4d6d;
            --leaf-green: #95d5b2;
            --glass: rgba(255, 255, 255, 0.6);
        }

        * { box-sizing: border-box; scroll-behavior: smooth; }

        body {
            background: linear-gradient(135deg, #fff0f3 0%, #ffc1cf 100%);
            color: #594145;
            margin: 0;
            font-family: 'Quicksand', sans-serif;
            overflow-x: hidden;
            scroll-snap-type: y mandatory;
        }

        /* --- MAGIC FLOATING HEARTS --- */
        #bg-canvas {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
            z-index: 2;
            scroll-snap-align: start;
            padding: 20px;
        }

        /* --- SECTION 1: CUTE WELCOME --- */
        .heart-loader {
            font-size: 3rem;
            animation: beat 1.2s infinite;
            margin-bottom: 20px;
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            color: var(--rose-red);
            margin: 0;
        }

        /* --- SECTION 2: THE MAGIC BLOOM --- */
        .bouquet-stage {
            position: relative;
            width: 320px;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: flex-end;
            perspective: 1000px;
        }

        .flower-wrap {
            position: absolute;
            bottom: 20px;
            width: 160px;
            height: 250px;
            background: var(--glass);
            backdrop-filter: blur(10px);
            border-radius: 0 0 80px 80px;
            clip-path: polygon(0 0, 100% 0, 85% 100%, 15% 100%);
            border: 2px solid white;
            z-index: 5;
            box-shadow: 0 10px 30px rgba(255, 133, 162, 0.3);
        }

        /* The Animated Rose */
        .rose {
            position: absolute;
            bottom: 80px;
            transform-style: preserve-3d;
            transition: transform 1.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            z-index: 3;
        }

        .stem {
            width: 6px;
            height: 0;
            background: linear-gradient(to top, #40916c, var(--leaf-green));
            border-radius: 10px;
            transition: height 2s ease-in-out;
        }

        .petal {
            position: absolute;
            bottom: 0;
            left: 50%;
            background: radial-gradient(circle at center, #ffb3c1, var(--rose-red));
            border-radius: 50% 50% 10% 10%;
            transform-origin: bottom center;
            opacity: 0;
            box-shadow: inset 0 0 8px rgba(0,0,0,0.1);
        }

        /* --- SECTION 3: THE PROPOSAL --- */
        .proposal-card {
            background: white;
            padding: 40px;
            border-radius: 40px;
            box-shadow: 0 20px 60px rgba(255, 77, 109, 0.15);
            width: 100%;
            max-width: 380px;
            text-align: center;
            border: 5px solid var(--soft-pink);
        }

        .btn-cute {
            padding: 15px 35px;
            border-radius: 50px;
            border: none;
            cursor: pointer;
            font-weight: bold;
            font-size: 1rem;
            margin: 10px;
            transition: 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        #yes-btn { background-color: var(--rose-red); color: white; }
        #no-btn { background-color: #f0f0f0; color: #999; }
        
        #yes-btn:hover { transform: scale(1.1) rotate(-2deg); background-color: #ff0a54; }

        /* --- ANIMATIONS --- */
        @keyframes beat { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.2); } }
        @keyframes bloom { to { transform: translateX(-50%) rotateY(var(--ry)) rotateX(var(--rx)) scale(1); opacity: 1; } }
        
        .scroll-hint {
            position: absolute;
            bottom: 20px;
            font-weight: 500;
            color: var(--deep-pink);
            animation: bounce 2s infinite;
        }
        @keyframes bounce { 0%, 20%, 50%, 80%, 100% {transform: translateY(0);} 40% {transform: translateY(-10px);} }
    </style>
</head>
<body>

    <canvas id="bg-canvas"></canvas>

    <section>
        <div class="heart-loader">💝</div>
        <h1>Hello, Ridhi Bangaram</h1>
        <p style="font-weight: 300; letter-spacing: 2px;">I HAVE A SURPRISE FOR YOU...</p>
        <div class="scroll-hint">scroll down ↡</div>
    </section>

    <section>
        <div class="bouquet-stage" id="stage">
            <div class="flower-wrap"></div>
        </div>
        <button class="btn-cute" id="bloom-trigger" style="background: var(--deep-pink); color: white;" onclick="magicBloom()">Click for Magic ✨</button>
        <div class="scroll-hint" id="hint-2" style="display:none;">keep going ↡</div>
    </section>

    <section>
        <div class="proposal-card">
            <h2 style="font-family: 'Dancing Script', cursive; font-size: 2.5rem; color: var(--rose-red); margin-top:0;">Ammupie...</h2>
            <p>Will you be my Valentine and make my heart complete?</p>
            <div style="margin-top: 30px;">
                <button id="yes-btn" class="btn-cute" onclick="final(true)">YES! ❤️</button>
                <button id="no-btn" class="btn-cute" onclick="final(false)">No 🥺</button>
            </div>
            <div id="response" style="margin-top: 25px; font-weight: 500; color: var(--rose-red);"></div>
        </div>
    </section>

    <script>
        // Floating Background Hearts
        const canvas = document.getElementById('bg-canvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        function resize() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
        window.addEventListener('resize', resize); resize();

        class Heart {
            constructor() { this.reset(); }
            reset() {
                this.x = Math.random() * canvas.width;
                this.y = canvas.height + 20;
                this.size = Math.random() * 15 + 5;
                this.speed = Math.random() * 1.5 + 0.5;
                this.opacity = Math.random() * 0.4 + 0.1;
            }
            draw() {
                ctx.fillStyle = `rgba(255, 133, 162, ${this.opacity})`;
                ctx.beginPath();
                ctx.moveTo(this.x, this.y);
                ctx.bezierCurveTo(this.x - this.size/2, this.y - this.size/2, this.x - this.size, this.y + this.size/3, this.x, this.y + this.size);
                ctx.bezierCurveTo(this.x + this.size, this.y + this.size/3, this.x + this.size/2, this.y - this.size/2, this.x, this.y);
                ctx.fill();
            }
            update() { this.y -= this.speed; if (this.y < -20) this.reset(); }
        }

        for(let i=0; i<30; i++) particles.push(new Heart());
        function anim() { ctx.clearRect(0,0,canvas.width, canvas.height); particles.forEach(p=>{p.update(); p.draw();}); requestAnimationFrame(anim); }
        anim();

        // Magic Bloom Logic
        function createRose(z, y, delay) {
            const stage = document.getElementById('stage');
            const rose = document.createElement('div');
            rose.className = 'rose';
            rose.style.left = '50%';
            rose.style.transform = 'translateX(-50%) scale(0)';
            
            const stem = document.createElement('div'); stem.className = 'stem';
            const head = document.createElement('div'); head.style.position = 'absolute'; head.style.top = '0'; head.style.transformStyle = 'preserve-3d';
            
            rose.appendChild(head); rose.appendChild(stem); stage.appendChild(rose);

            setTimeout(() => { 
                stem.style.height = '200px'; 
                rose.style.transform = `translateX(-50%) rotateZ(${z}deg) rotateY(${y}deg) scale(1)`;
            }, delay);

            setTimeout(() => {
                for (let i = 0; i < 20; i++) {
                    const p = document.createElement('div'); p.className = 'petal';
                    p.style.setProperty('--ry', (i * 137.5) + 'deg');
                    p.style.setProperty('--rx', (20 + (i / 20) * 80) + 'deg');
                    p.style.width = (15 + (i * 1.5)) + 'px'; p.style.height = (20 + (i * 2)) + 'px';
                    p.style.animation = `bloom 1.5s ease-out ${i * 0.05}s forwards`;
                    head.appendChild(p);
                }
            }, delay + 1000);
        }

        function magicBloom() {
            document.getElementById('bloom-trigger').style.display = 'none';
            const bouquet = [[0,0,100], [-15,30,400], [15,-30,700], [-30,45,1000], [30,-45,1300]];
            bouquet.forEach(r => createRose(r[0], r[1], r[2]));
            setTimeout(() => { document.getElementById('hint-2').style.display = 'block'; }, 4000);
        }

        function final(isYes) {
            const res = document.getElementById('response');
            if(isYes) {
                res.innerHTML = "<h3>YAY! ❤️✨</h3>You've made me the happiest person in the world! I love you, Ammupie!";
            } else {
                res.innerHTML = "<h3>Nice try! 😉</h3>Despite you choosing no, you're <b>still my valentine</b> because I love you way too much!";
            }
        }
    </script>
</body>
</html>
