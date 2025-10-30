<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timber Taskforce - Elite Tree Extraction Ops</title>
    <style>
        body { 
            font-family: 'Impact', Arial, sans-serif; 
            margin: 0; 
            padding: 0; 
            background-color: #0D0D0D; 
            color: #E0E0E0; 
            text-transform: uppercase; 
        }
        header { 
            background: url('https://via.placeholder.com/1920x600?text=Operator+In+The+Field') no-repeat center/cover; 
            height: 80vh; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            text-align: center; 
            color: #FFFFFF; 
            text-shadow: 4px 4px 8px rgba(0,0,0,0.9); 
            border-bottom: 5px solid #228B22; /* Military green */
            position: relative;
        }
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.6); /* Dark overlay for tactical feel */
            z-index: 1;
        }
        header h1 { 
            font-size: 4em; 
            z-index: 2; 
            animation: pulse 2s infinite; 
            letter-spacing: 0.1em;
        }
        @keyframes pulse { 
            0% { transform: scale(1); } 
            50% { transform: scale(1.05); } 
            100% { transform: scale(1); } 
        }
        section { 
            padding: 60px 20px; 
            max-width: 1200px; 
            margin: auto; 
            background: linear-gradient(to bottom, #1A1A1A, #0D0D0D); 
            border: 2px solid #333; 
        }
        .services { 
            display: flex; 
            flex-wrap: wrap; 
            gap: 30px; 
            justify-content: center; 
        }
        .service-card { 
            background: #222; 
            border: 3px solid #228B22; 
            border-radius: 0; /* Sharp edges for military */
            box-shadow: 0 8px 16px rgba(0,0,0,0.5); 
            padding: 30px; 
            width: 350px; 
            transition: all 0.3s; 
            text-align: center;
        }
        .service-card:hover { 
            transform: translateY(-10px); 
            border-color: #FFD700; /* Gold for heroic */
        }
        .service-card h3 { 
            color: #228B22; 
            font-size: 2em; 
            margin-bottom: 15px; 
        }
        .service-card p {
            font-size: 1.2em;
            line-height: 1.5;
        }
        .cta-button {
            display: inline-block;
            background: #228B22;
            color: #FFF;
            padding: 15px 30px;
            margin-top: 20px;
            text-decoration: none;
            font-size: 1.5em;
            border: 2px solid #FFF;
            transition: background 0.3s;
        }
        .cta-button:hover {
            background: #FFD700;
            color: #000;
        }
        footer { 
            background: #000; 
            color: #888; 
            text-align: center; 
            padding: 20px; 
            font-size: 1em;
            border-top: 5px solid #228B22;
        }
    </style>
</head>
<body>
    <header>
        <h1>Timber Taskforce: Elite Operators Dropping Targets</h1>
    </header>
    <section>
        <h2>Mission Briefing</h2>
        <p>Veteran-led SOF unit in Central Florida. We infiltrate, extract, and neutralize tree threats with precision strikes. No mercy for hazards—trim, remove, grind. Storm ops? We're the first in, last out. Locked, loaded, and eco-tactical.</p>
        <a href="#contact" class="cta-button">Deploy Now</a>
    </section>
    <section class="services">
        <div class="service-card">
            <h3>Tree Extraction</h3>
            <p>We drop hostiles like it's a black op. $1,000–$5,000. Crane reinforcements for high-value targets. No trace left behind.</p>
        </div>
        <div class="service-card">
            <h3>Stump Annihilation</h3>
            <p>Obliterate remnants, reclaim the AO. $200–$800. Grind 'em into dust—operator style.</p>
        </div>
        <div class="service-card">
            <h3>Storm Assault</h3>
            <p>Rapid insertion post-hurricane. Clear debris, secure perimeters. $2,000–$10,000. We own the chaos.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Timber Taskforce. Radio in: info@timbertaskforce.com | Veteran-Owned, Operator-Approved</p>
    </footer>
</body>
</html>
