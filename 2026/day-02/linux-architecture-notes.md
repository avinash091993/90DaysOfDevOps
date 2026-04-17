# Linux Architecture Notes

## Core Components
- Kernel → manages CPU, memory, hardware
- User Space → where apps run (bash, nginx)
- systemd → manages services (PID 1)

---

## Processes
- Process = running program (has PID)

### States
- Running → using CPU  
- Sleeping → waiting  
- Stopped → paused  
- Zombie → finished but not cleaned  

---

## Commands I Use
- ps aux → list processes  
- top → CPU/memory usage  
- htop → better monitoring  
- kill -9 PID → stop process  
- systemctl status nginx → check service  

---

## systemd
- Manages services and startup  
- Restarts failed services  

### Commands
- systemctl start nginx  
- systemctl stop nginx  
- systemctl restart nginx  
- systemctl status nginx  
- systemctl enable nginx  

---

## Why Important
- Debug service issues  
- Monitor system performance  
- Manage production services  
