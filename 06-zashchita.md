Прилагаю скриншот oom_score и oom_score_adj до изменения

<img width="1004" height="195" alt="image" src="https://github.com/user-attachments/assets/f910f59a-ae80-4840-a759-d83594a2468a" />

На скриншоте мы создали файл и посмотрели его oom_score 666 и oom_score_adj 0 
Теперь прилагаю скриншот oom_score и oom_score_adj после изменения

<img width="739" height="132" alt="image" src="https://github.com/user-attachments/assets/62352a47-da65-4448-a04e-23b7e16ad6f2" />

На скриншоте теперь видно изменение oom_score -500 и oom_score_adj 334
Sudo нужна для использования действия именно суперпользователем , дабы обезопасить такие действия от любых пользователей 
Я бы понизил oom_score_adj можно понизить, чтобы базу данных не убили первой, ведь потеря базы данных значит потеря всего .
