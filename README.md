# Setup


# Run:

```bash
docker run \
   -it \
   --rm \
   --name ma-instance \
   -p 8080:8080 \
   -v /app/MathApp:/go/src/MathApp -w /go/src/MathApp ma-image
```
