# RESOURCE DIRECTORY — самостоятельный учебный каталог

Все нужные ориентиры для PAYDAY-обучения собраны **здесь**; для них не нужен каталог в другом RPG-репозитории. Перед началом задания перепроверять доступность, актуальность, платность и разрешённый scope конкретной площадки. Одна ссылка в этом файле НЕ разрешает тестировать произвольные сторонние системы.

## TryHackMe — основной учебный ресурс
| Задача | URL | Статус/назначение |
|---|---|---|
| Further Nmap | https://tryhackme.com/room/furthernmap | Практика была; полного зачёта комнаты не подтверждено |
| Content Discovery | https://tryhackme.com/room/contentdiscovery | **Полностью пройдена** |
| ffuf | https://tryhackme.com/room/ffuf | Доступная практика и материал пройдены, полного платформенного зачёта нет |
| Linux Privilege Escalation: Enumeration | https://tryhackme.com/room/linprivenum | **Начата, не подтверждена завершённой** |
| Linux Privilege Escalation: Basics | https://tryhackme.com/room/linprivbasics | Возможный следующий модуль |
| Cheese CTF | https://tryhackme.com/room/cheesectfv10 | Итоговое испытание, не спойлерить |
| Дополнительные машины | https://tryhackme.com/room/b3dr0ck · https://tryhackme.com/room/mustacchio · https://tryhackme.com/room/smaggrotto · https://tryhackme.com/room/lofi · https://tryhackme.com/room/tomghost | Не пройдены, по готовности |

Pre Security / Cyber Security 101 — только для точечного закрытия пробелов, не обязательная повторная учёба с нуля: https://tryhackme.com/beginner-path

## Инструменты и справочники
- [SecLists](https://github.com/danielmiessler/SecLists) и [инструкция Kali](https://www.kali.org/tools/seclists/) — словари (не эксплойт).
- [ffuf](https://github.com/ffuf/ffuf), [Gobuster](https://github.com/OJ/gobuster) — веб-/DNS-обнаружение на разрешённой цели.
- [GTFOBins](https://gtfobins.github.io/) — свойства легитимных Unix-программ, зависимость от sudo/SUID/capabilities.
- [PEASS-ng](https://github.com/peass-ng/PEASS-ng) — linPEAS, winPEAS и доступные связанные варианты; для Darwin проверять текущие официальные сборки, не обещать «macPEAS».
- [Exploit-DB](https://www.exploit-db.com/), [NVD](https://nvd.nist.gov/) — CVE/PoC/версии, проверить применимость, не подменять вероятную уязвимость подтверждённой.
- [Hydra](https://www.kali.org/tools/hydra/) — учебная проверка собственных тестовых записей только с явным разрешением полигона.

## Другие площадки
[OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) · [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/) · [PortSwigger Academy](https://portswigger.net/web-security) · [Hacker101](https://ctf.hacker101.com/) · [Root-Me](https://www.root-me.org/) · [CTFLearn](https://ctflearn.com/) · [Pentest-Ground](https://pentest-ground.com/) · [VulnHub](https://www.vulnhub.com/) · [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/) · [LiveOverflow](https://www.youtube.com/@LiveOverflow).

Изначально пользователь также давал открытый справочный сборник [awesome-ethical-hacking-resources](https://github.com/husnainfareed/awesome-ethical-hacking-resources). Это **не другой RPG-архив** и не обязательная зависимость: нужные учебные направления перечислены здесь.

## Алгоритм выбора урока
Проверить [PROGRESS](PROGRESS.md), выбрать из [ROADMAP](ROADMAP.md) одну неосвоенную тему → проверить конкретную лабораторию/доступ → обозначить один измеримый результат → практика → разбор защитных мер. Не сохранять пароли, токены, личные данные и динамические IP машин в **публичный** репозиторий.
