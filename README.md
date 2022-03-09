# gopy
Example of golang call from python

From the excellent [article](https://medium.com/analytics-vidhya/running-go-code-from-python-a65b3ae34a2d) from [Rene Manqueros](https://manqueros.com)

Build a shared object with:
```bash
go build -buildmode=c-shared -o library.so library.go
```