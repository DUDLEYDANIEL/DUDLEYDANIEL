```assemby
section .intro                 
    db "Hello, World! I'm Dudley Daniel Raj.", 0   
    db "Welcome to my GitHub profile!", 0

section .about_me              
    db "Occupation: Bug Hunter, red Teamer, CTF player", 0
    db "Current Distro: Kali Linux", 0
    db "Skills: Bug Bounty, Vulnerability Analysis, Assembly (NASM), Malware Analysis(studying), Log ingestion in SIEM, binary exploitation ", 0
    db "Learning: In depth red team penetration tool for network(in research)", 0 ; Trying to code it
    
section .skills                ; Technologies I Work With
    mov eax, Languages         ; Loading the list of languages
    db "Python, Rust(readable), C, C++, Assembly, javascript, go", 0
    mov ebx, Tools             ; Loading the list of tools
    db "Git, Docker, PowerShell, Windows APIs, pentesting tools , reverse engineering tool, bash", 0

section .projects              ; Projects Section
    db "Projects:", 0
    db "- 'Cyber Practice projects': A project for the remote code dll injection", 0
    db "- 'Garbage collector in C', 0
    db "- 'Active directory pentesting simulation", 0

section .connect               ; Connect with Me
    db "LinkedIn: https://www.linkedin.com/in/dudley-daniel-raj/", 0
    db "Medium: https://medium.com/@dudleydaniel.raj2005", 0

section .end                   ; End of ReadMe
    db "Thanks for visiting my GitHub profile!", 0
    int 0x20                   ; Exit 
```
