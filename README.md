# Go Benchmark

```
go test -bench . -cpu 8 -benchmem -benchtime 5s -count 5 ./words
```

```
go test -bench . -cpu 8 -benchmem -benchtime 5s -count 5 -memprofile mem.prof ./words
```

```
go tool pprof -http :8081 mem.prof
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

by **Eduardo Raider** - Software Engineer