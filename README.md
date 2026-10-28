<style>
    * {
        box-sizing: border-box;
    }

    .langIcons {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 0.75rem;
        margin-top: 0.75rem;
    }

    .lang {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 0.35rem;
        width: 4.5rem;
        font-size: 0.75rem;
        line-height: 1.2;
    }

    .lang img {
        width: 2.75rem;
        height: 2.75rem;
        padding: 0.45rem;
        background-color: white;
        border-radius: 0.75rem;
        box-shadow: 0 3px 8px rgba(25, 35, 75, 0.25);
        transition: transform 0.2s ease;
    }

    .lang:hover img {
        transform: translateY(-3px) scale(1.1);
    }

    body {
        margin: 0;
        padding: 2rem;
        font-family: Arial, sans-serif;
    }

    section {
        padding: 2rem 1rem;
        background-color: #6976af;
        border-radius: 1.5rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 1rem;
        max-width: 900px;
        margin: 0 auto;
        box-shadow: 0 8px 25px rgba(45, 55, 100, 0.15);
    }

    .nameTitle {
        font-size: clamp(2.5rem, 6vw, 3.5rem);
        color: white;
        font-weight: 800;
        margin: 0 0 1rem;
        letter-spacing: 2px;
        text-shadow: 2px 3px 0 rgba(0, 0, 0, 0.15);
    }

    .tagline {
        color: rgba(255, 255, 255, 0.85);
        font-size: 1.15rem;
        margin: -1.5rem 0 0.5rem;
        text-align: center;
    }

    .item {
        color: white;
        font-size: 1.2rem;
        line-height: 1.7;
        border: 2px solid rgba(255, 255, 255, 0.2);
        background-color: #5565ac;
        padding: 1.25rem;
        border-radius: 1rem;
        width: min(90%, 500px);
        margin: 0;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        box-shadow: 0 4px 10px rgba(25, 35, 75, 0.15);
        transition:
            transform 0.25s ease,
            background-color 0.25s ease,
            box-shadow 0.25s ease;
    }

    .item:hover {
        background-color: #46569c;
        transform: translateY(-5px);
        box-shadow: 0 8px 18px rgba(25, 35, 75, 0.25);
    }

    @media (max-width: 600px) {
        body {
            padding: 1rem;
        }

        section {
            padding: 1.5rem 0.5rem;
        }

        .item {
            width: 95%;
            font-size: 1.05rem;
        }
    }

    @media (prefers-reduced-motion: reduce) {
        .item,
        .lang img {
            transition: none;
        }

        .item:hover,
        .lang:hover img {
            transform: none;
        }
    }
</style>

<section>
    <p class="nameTitle">EZkleps</p>
    <p class="tagline">Making games, apps &amp; websites.</p>
    <p class="item">
        Coding languages
        <span class="langIcons">
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python"><small>Python</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/lua/lua-original.svg" alt="Lua"><small>Lua</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL"><small>SQL</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML"><small>HTML</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS"><small>CSS</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sass/sass-original.svg" alt="SCSS"><small>SCSS</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript"><small>JS</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript"><small>TS</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" alt="C#"><small>C#</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React"><small>React</small></span>
        </span>
    </p>
    <p class="item">
        Tools
        <span class="langIcons">
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" alt="VS Code"><small>VS Code</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git"><small>Git</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" alt="GitHub"><small>GitHub</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" alt="Node.js"><small>Node.js</small></span>
            <span class="lang"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/godot/godot-original.svg" alt="Godot"><small>Godot</small></span>
        </span>
    </p>
</section>