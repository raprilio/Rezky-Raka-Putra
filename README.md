<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IT Infrastructure Portfolio & Profile</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #e2e8f0;
            --text-muted: #94a3b8;
            --accent-blue: #38bdf8;
            --accent-green: #34d399;
            --accent-orange: #fb923c;
            --accent-purple: #c084fc;
            --border-color: #334155;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 40px 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            padding-bottom: 40px;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 2.5rem;
            color: #ffffff;
            margin-bottom: 10px;
        }

        header h2 {
            font-size: 1.3rem;
            color: var(--accent-blue);
            font-weight: 500;
            margin-bottom: 15px;
        }

        header p {
            color: var(--text-muted);
            font-size: 1rem;
            max-width: 700px;
            margin: 0 auto 20px auto;
        }

        .social-links a {
            display: inline-block;
            margin: 0 10px;
            color: var(--text-color);
            text-decoration: none;
            background-color: var(--card-bg);
            padding: 8px 16px;
            border-radius: 6px;
            font-size: 0.9rem;
            border: 1px solid var(--border-color);
            transition: all 0.3s ease;
        }

        .social-links a:hover {
            border-color: var(--accent-blue);
            color: var(--accent-blue);
        }

        section {
            margin-bottom: 40px;
        }

        section h3 {
            font-size: 1.5rem;
            color: #ffffff;
            margin-bottom: 20px;
            border-left: 4px solid var(--accent-blue);
            padding-left: 12px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }

        .card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 20px;
            transition: transform 0.2s ease, border-color 0.2s ease;
        }

        .card:hover {
            transform: translateY(-2px);
            border-color: var(--accent-blue);
        }

        .card h4 {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .card h4 a {
            color: #ffffff;
            text-decoration: none;
            transition: color 0.2s ease;
        }

        .card h4 a:hover {
            color: var(--accent-blue);
            text-decoration: underline;
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .badge-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 15px;
        }

        .badge {
            background-color: rgba(56, 189, 248, 0.1);
            color: var(--accent-blue);
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: 600;
        }

        .badge.network { background-color: rgba(248, 113, 113, 0.1); color: #f87171; }
        .badge.cloud { background-color: rgba(251, 146, 60, 0.1); color: #fb923c; }
        .badge.dev { background-color: rgba(52, 211, 153, 0.1); color: #34d399; }
        .badge.hardware { background-color: rgba(192, 132, 252, 0.1); color: var(--accent-purple); }

        .tech-box {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .tech-box h4 {
            color: var(--text-muted);
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 12px;
        }

        ul {
            padding-left: 20px;
            color: var(--text-muted);
        }

        li {
            margin-bottom: 8px;
        }

        li strong {
            color: var(--text-color);
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Rezky Raka Putra</h1>
            <h2>IT Infrastructure Engineer | Hardware Enthusiast | Full-Stack</h2>
            <p>Specialist in enterprise network design, cloud administration, storage/VM engineering, broadcast setups, and internal operational tool development.</p>
            <div class="social-links">
                <a href="https://linkedin.com/in/YOUR-PROFILE" target="_blank">💼 LinkedIn</a>
                <a href="https://github.com/YOUR-USERNAME" target="_blank">🐙 GitHub</a>
                <a href="mailto:your.email@example.com">📧 Contact Email</a>
            </div>
        </header>

        <section id="repositories">
            <h3>📂 Featured Repositories & Configurations</h3>
            <p style="color: var(--text-muted); margin-bottom: 20px; font-size: 0.95rem;">Click on the folder names to view the repository codes and configurations.</p>
            <div class="grid">
                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/network-configs" target="_blank">network-configs</a></h4>
                    <p>Network configuration blueprints, firewall rules, and workload routing optimization scripts.</p>
                    <div class="badge-list">
                        <span class="badge network">MikroTik</span>
                        <span class="badge network">FortiGate</span>
                        <span class="badge network">pfSense</span>
                    </div>
                </div>
                
                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/nas-vm-homelab" target="_blank">nas-vm-homelab</a></h4>
                    <p>Build configurations, provisioning scripts, and optimizations for NAS storage servers and Virtual Machines.</p>
                    <div class="badge-list">
                        <span class="badge hardware">NAS Storage</span>
                        <span class="badge hardware">Virtual Machines</span>
                        <span class="badge hardware">Proxmox</span>
                    </div>
                </div>

                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/broadcast-obs-studio" target="_blank">broadcast-obs-studio</a></h4>
                    <p>Advanced configurations for broadcast studio cameras, OBS Studio scene collections, and streaming optimization.</p>
                    <div class="badge-list">
                        <span class="badge hardware">OBS Studio</span>
                        <span class="badge hardware">Camera Configs</span>
                        <span class="badge hardware">Streaming</span>
                    </div>
                </div>

                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/3d-printing-projects" target="_blank">3d-printing-projects</a></h4>
                    <p>Firmware settings, calibration profiles, and code snippets for 3D printer builds and small hardware projects.</p>
                    <div class="badge-list">
                        <span class="badge hardware">3D Printing</span>
                        <span class="badge hardware">Hardware Config</span>
                    </div>
                </div>

                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/cloud-sysadmin" target="_blank">cloud-sysadmin</a></h4>
                    <p>Automation scripts for identity management, security policies, and resource deployment.</p>
                    <div class="badge-list">
                        <span class="badge cloud">AWS</span>
                        <span class="badge cloud">M365</span>
                        <span class="badge cloud">Workspace</span>
                    </div>
                </div>

                <div class="card">
                    <h4>📁 <a href="https://github.com/YOUR-USERNAME/infrastructure-dashboards" target="_blank">infrastructure-dashboards</a></h4>
                    <p>Source code for internal IT asset management apps, ERP systems, and monitoring panels.</p>
                    <div class="badge-list">
                        <span class="badge dev">Laravel</span>
                        <span class="badge dev">Filament</span>
                        <span class="badge dev">React.js</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="focus">
            <h3>Current Initiatives</h3>
            <ul>
                <li><strong>Global Scalability:</strong> Developing a standardized infrastructure portfolio to meet the needs of international scale partners.</li>
                <li><strong>Business Development:</strong> Building integrated technology operational foundations and a comprehensive procurement service catalog under PT Golden Brillant Essential.</li>
                <li><strong>Creative & Media Tech:</strong> Fine-tuning studio broadcasting environments and pushing the limits of 3D printing hardware integrations.</li>
                <li><strong>Market Analysis:</strong> Conducting technical analysis research on market movements and the blockchain ecosystem.</li>
            </ul>
        </section>
    </div>

</body>
</html>
