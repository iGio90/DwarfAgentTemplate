#### Dwarf agent template

Edit **agent.ts** with Dwarf + Frida api suggestions and documentations.

Check out - <a href="https://igio90.github.io/Dwarf/">Dwarf javascript api</a> - <a href="https://www.frida.re/docs/javascript-api/">Frida javascript api</a> 

```
git clone https://github.com/iGio90/DwarfAgentTemplate.git MyProjectName

cd MyProjectName
npm install
npm run build

dwarf -s agent.js /usr/bin/man open
```
