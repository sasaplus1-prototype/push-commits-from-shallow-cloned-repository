# push-commits-from-shallow-cloned-repository

push commits from shallow cloned repository

## Example

```console
$ git clone --depth 1 https://github.com/sasaplus1-prototype/push-commits-from-shallow-cloned-repository.git ./shallow
$ cd ./shallow
$ touch c
$ git add .
$ git commit -m "added c"
$ git push origin master
$ cd ../
$ git fetch
```

## License

The MIT license.
