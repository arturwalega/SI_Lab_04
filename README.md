Plik dockera pozwalający uruchomienie narzędzia do wyznaczania punktów kluczowych na obrazie na labolatoria nr 4 z SI
Wymagania:
	-docker
	-docker compose
Uruchomienie:
	docker-compose up
	
Gdyby komuś się nie chciało instalować composera wystarczy wpisać komendy w konsoli windows:
	docker pull crackaw/app:latest
	docker run -v %cd%/images:/app/images crackaw/app
Linux/Mac:
	docker run -v $(pwd)/images:/app/images crackaw/app