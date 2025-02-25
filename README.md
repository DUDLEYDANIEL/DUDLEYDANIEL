w
```assemby
section .intro                 
    db "Hello, World! I'm Dudley Daniel Raj.", 0   
    db "Welcome to my GitHub profile!", 0

section .about_me              
    db "Occupation: Cybersecurity Enthusiast, red Teamer, CTF player", 0
    db "Current Distro: Kali Linux", 0
    db "Skills: Incident Response, Vulnerability Analysis, Assembly (NASM), Malware Analysis(studying) ", 0
    db "Learning: Machine Learning for Firewall Projects", 0 ; Trying to code it
    
section .skills                ; Technologies I Work With
    mov eax, Languages         ; Loading the list of languages
    db "Python, Rust, C, C++, Assembly, javascript, java", 0
    mov ebx, Tools             ; Loading the list of tools
    db "Git, Docker, PowerShell, Windows APIs, pentesting tools , forensic tools", 0

section .projects              ; Projects Section
    db "Projects:", 0
    db "- 'Cyber Practice projects': A project for the remote code dll injection", 0
    db "- 'snake-game-asm': coding an snake game in boot sector using asm, 0
    db "- 'Active directory pentesting simulation", 0

section .connect               ; Connect with Me
    db "LinkedIn: https://www.linkedin.com/in/dudley-daniel-raj-473a22276/", 0
    db "Medium: https://medium.com/@dudleydaniel.raj2005", 0

section .end                   ; End of ReadMe
    db "Thanks for visiting my GitHub profile!", 0
    int 0x20                   ; Exit 
```
