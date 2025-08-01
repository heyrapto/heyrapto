<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caleb Kalejaiye - README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292f;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
        }
        
        h1 {
            font-size: 2.5em;
            font-weight: 600;
            margin-bottom: 0.3em;
            border-bottom: 1px solid #d1d9e0;
            padding-bottom: 0.3em;
        }
        
        .subtitle {
            font-size: 1.1em;
            color: #656d76;
            margin-bottom: 2em;
            font-weight: 400;
        }
        
        h2 {
            font-size: 1.5em;
            font-weight: 600;
            margin-top: 2em;
            margin-bottom: 1em;
            color: #1f2328;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5em;
            margin-bottom: 2em;
        }
        
        .skill-category {
            background: #f6f8fa;
            border: 1px solid #d1d9e0;
            border-radius: 6px;
            padding: 1.5em;
        }
        
        .skill-category h3 {
            font-size: 1.1em;
            font-weight: 600;
            margin-bottom: 0.8em;
            color: #1f2328;
            border-bottom: 2px solid #0969da;
            padding-bottom: 0.3em;
        }
        
        .skill-category ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        .skill-category li {
            padding: 0.3em 0;
            color: #656d76;
            font-size: 0.9em;
        }
        
        .skill-category li:before {
            content: "▸";
            color: #0969da;
            font-weight: bold;
            margin-right: 0.5em;
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1em;
            margin: 2em 0;
        }
        
        .stat-card {
            text-align: center;
            padding: 1em;
        }
        
        .stat-card img {
            border-radius: 6px;
            max-width: 100%;
            height: auto;
        }
        
        .footer {
            text-align: center;
            margin-top: 3em;
            padding: 1.5em;
            background: #f6f8fa;
            border-radius: 6px;
            border-left: 4px solid #0969da;
        }
        
        .footer p {
            margin: 0;
            font-style: italic;
            color: #656d76;
        }
        
        hr {
            border: none;
            height: 1px;
            background: #d1d9e0;
            margin: 2em 0;
        }
        
        @media (max-width: 600px) {
            .skills-grid {
                grid-template-columns: 1fr;
            }
            
            body {
                padding: 10px;
            }
            
            h1 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>
    <h1>Caleb Kalejaiye</h1>
    <p class="subtitle">Software Developer specializing in blockchain technology, AI systems, and full-stack web development.</p>
    
    <h2>Technical Expertise</h2>
    
    <div class="skills-grid">
        <div class="skill-category">
            <h3>Blockchain Development</h3>
            <ul>
                <li>Smart contract development with Solidity</li>
                <li>Development frameworks: Hardhat, Foundry</li>
                <li>EVM-compatible chains and architecture</li>
                <li>Smart contract security and auditing</li>
            </ul>
        </div>
        
        <div class="skill-category">
            <h3>AI & Intelligent Systems</h3>
            <ul>
                <li>Conversational agents using Gemini and OpenAI APIs</li>
                <li>AI-powered developer tooling and automation</li>
                <li>Prompt engineering and API orchestration</li>
                <li>Context management and intelligent task scheduling</li>
            </ul>
        </div>
        
        <div class="skill-category">
            <h3>Frontend Development</h3>
            <ul>
                <li>React.js, Next.js, TypeScript</li>
                <li>Modern styling with TailwindCSS</li>
                <li>State management with Zustand</li>
                <li>Authentication with Clerk</li>
            </ul>
        </div>
        
        <div class="skill-category">
            <h3>Backend & Infrastructure</h3>
            <ul>
                <li>Node.js and Express.js APIs</li>
                <li>Web3 integration with Web3.js and ethers.js</li>
                <li>Database management with Prisma and MongoDB</li>
                <li>Cloud services and Firebase integration</li>
            </ul>
        </div>
        
        <div class="skill-category">
            <h3>Developer Tools & Experience</h3>
            <ul>
                <li>Custom development tools and IDE extensions</li>
                <li>Technical documentation and tutorial creation</li>
                <li>Comprehensive testing with Jest and Playwright</li>
                <li>Developer onboarding and workflow optimization</li>
            </ul>
        </div>
    </div>
    
    <h2>GitHub Statistics</h2>
    
    <div class="stats-container">
        <div class="stat-card">
            <img src="https://github-readme-stats.vercel.app/api?username=heyrapto&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats">
        </div>
        
        <div class="stat-card">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heyrapto&layout=compact&theme=default&hide_border=true" alt="Top Languages">
        </div>
        
        <div class="stat-card">
            <img src="https://github-readme-streak-stats.herokuapp.com?user=heyrapto&theme=default&hide_border=true" alt="GitHub Streak">
        </div>
    </div>
    
    <hr>
    
    <div class="footer">
        <p>Building purposeful software solutions. Open to collaboration and challenging problem-solving opportunities.</p>
    </div>
</body>
</html>
