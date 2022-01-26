# ```libasm```
A few basic C functions reimplemented in x86 (Intel syntax) assembly code. Here are the function prototypes:

```c
size_t	ft_strlen(const char *s);
ssize_t	ft_write(int fd, const void *buf, size_t count);
ssize_t	ft_read(int fd, void *buf, size_t count);
int	ft_strcmp(char *s1, char *s2);
char	*ft_strcpy(char *dst, const char *src);
char	*ft_strdup(const char *s);
```

## How to use it

To compile the library, execute the following command:
```bash
make
```

In order to compile the test files using the library:
```bash
make test
```

To test the library:
```bash
./test
```

## Acknowledgments
- Davy Wybiral's excellent [Intro to x86 Assembly Language](https://www.youtube.com/watch?v=wLXIWKUWpSs&list=PLmxT2pVYo5LB5EzTPZGfFN0c2GDiSXgQe)
- Yaroslav Soroko's [libasm](https://github.com/Ysoroko/Libasm)
- Charles Cabergs' [libasm](https://github.com/cacharle/libasm)
- fdeĉ's [libasm](https://git.42l.fr/frdescam/libasm)

## License
Everything in this repository is released under the [Unlicense](https://github.com/maxdesalle/libasm/blob/main/LICENSE).
