To keep a docker container alive add this as Entrypoint

```
ENTRYPOINT ["tail", "-f", "/dev/null"]
```
