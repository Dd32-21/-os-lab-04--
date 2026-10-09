Я написал скрипт в нано, прилагаю скриншот 

<img width="975" height="478" alt="image" src="https://github.com/user-attachments/assets/bc09f58c-6d5c-425f-b44e-b8307c85b65e" />

Система упала на результате 280Mib , прилагаю скриншот 

<img width="680" height="96" alt="image" src="https://github.com/user-attachments/assets/6fc6a983-e0f7-4c8f-a815-fa5e5e0d90c5" />

ulimit -v  устанавливает лимит на виртуальную память это безопаснее т.к процесс останавливается сам и не дает системе убить один файл 
По oom_score: больше всех памяти, не критичный для системы чее больше значение тем самым выбор упадет на него 
oom_score показывает приоритет убийства файла . Вот способ просмора cat /proc/<PID>/oom_score
