# L1 - 2019

## Scope

1. Linux - bash, ssh, scp, tmux, htop, kill, killall, operator pipe, ls, sed, vim, cat
2. Docker - Dockerfile, docker-compose, containers in general
3. Work queues - rabitmq, redis, celery
4. Python - conda, pip, virtualenv, requirements, poetry, tox

## Tasks

1.  Napisz skrypty:
	- kopiujące pliki między maszynami
	- uruchamiający w tle nieskończony proces oraz zabijający go
		- &
		- kill/killall/pidof
	- filtrujący losowy strumień danych
		- /dev/urandom
		- sed/tr
2. pokaż że potrafisz obsługiwać vima
	- wuszukiwanie
	- skocz do linii
	- zamiana
	- zapisanie
	- wyjście (2 sposoby)
3. Docker - napisz swój własny przykładowy Dockerfile oraz opublikuj go w [https://hub.docker.com/](https://hub.docker.com/)
	- FROM
	- RUN
	- ADD
	- ENV
	- ARG
	- ENTRYPOINT
	- CMD
4. Zdefiniuj docker-compose, z 2 kontenerami które się między sobą komunikują (nginx + curl)
	- version 3
	- links
	- restarts
	- resources
5. Python -GIL
	- Generator danych do zadania regresji liniowej parametryzowany ilością
	- Wyliczanie regresji z wykorzystaniem wątków
	- JW. tylko Multiprocessing
	- JW. Cellery
	- Wygeneruj wykresy prezentujące czasy wykonania zależnie od ilości danych