[< к содержанию](./readme.md)

## git bisect

**git bisect** - это чрезвычайно полезная утилита для поиска коммита, в котором впервые проявился баг или проблема с помощью автоматического бинарного поиска.

```bash=
git bisect start
git bisect bad
git bisect good v1.0
```