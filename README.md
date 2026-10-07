# Practical AppSec Handbook
Комплексная практическая выжимка требований по безопасности для SDLC, разработчиков (Backend, Frontend, AI, Files) и эшелонированной защиты инфраструктуры.

Стандарты ИБ обширны: сотни страниц OWASP ASVS, NIST SSDF, ISO 27034... У разработчиков и DevOps-инженеров во время спринтов просто нет времени читать фундаментальные фолианты. 

В результате безопасность либо откладывается «на потом», либо сводится к формальностям.

Чтобы решить эту проблему, я собрал и структурировал компактную выжимку практических требований по безопасности в один открытый GitHub-репозиторий. Без лишней теории — только то, что реально нужно внедрять в код и инфраструктуру.

Что внутри репозитория:

1️⃣ SDLC & DevSecOps Framework — верхнеуровневый процесс безопасной разработки для архитекторов и лидов (моделирование угроз, Supply Chain security, SBOM, Security Gates в CI/CD).
2️⃣ Developer Security Guidelines — четкий чек-лист для Backend, Frontend и AI-разработчиков:
   • OWASP Top 10 & API Security Top 10 (BOLA, BFLA, Mass Assignment, Rate Limiting).
   • Защита от Prompt Injection и безопасная обработка вывода LLM/AI.
   • Безопасная загрузка файлов (Magic Bytes, изоляция, UUID).
   • Требования к MFA для админов и правила полнотекстового Audit Log.
3️⃣ Infrastructure & Edge Security — архитектура периметра: Anti-DDoS, WAF, NGFW, Hardening ОС/Nginx и мониторинг.

#AppSec #DevSecOps #CyberSecurity #OWASP #SecureCoding #SoftwareSecurity #GitHub #InformationSecurity #WebSecurity
