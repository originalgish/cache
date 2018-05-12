Инструкция по установке и запуску

- запустить Ensemble;
- войти в веб-интерфейс http://localhost:57772/csp/sys/%25CSP.Portal.Home.zen;
- создать новый namespace, назвать его gs;
- создать web-application:
  1. name: /gs/api
  2. namespace: GS
  3. Dispatch Class: Todo.REST
- поместить исходные файлы проекта в ./CSP/gs 

- создать в Eclipse новый Atelier Project
- добавить в проект исходные файлы
- скомпилировать проект с помощью Atelier
- перейти по http://localhost:57772/csp/gs/index.html#!/