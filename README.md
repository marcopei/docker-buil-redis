# dockerbuild-redis-trib
### 使用
```bash
docker run -it --rm exxk/redis-trib ruby redis-trib.rb create --replicas 1 10.82.12.95:7000 10.82.12.95:7001 10.82.12.95:7002 10.82.12.98:7000 10.82.12.98:7001 10.82.12.98:7002
```
