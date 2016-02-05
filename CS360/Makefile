all: client server download
download: download.c
	g++ -o download download.c
client: cient.c
	gcc -o client client.c
server: server.c
	gcc -o server server.c
clean:
	rm client server
