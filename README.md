# test_case

# Startup script
```bash
# Build
$ docker-compose build

# Run
$ docker-compose up -d

# Deploy
$ ansible-playbook playbook.yaml

# Test
curl localhost:8080/images/

# Destroy 
$ docker-compose down
```

# Questions
1. Zsh setup role skipped.
2. Gzip is already on by default.
3. Request logs configured by default.
4. There is no clarification about the cache (browser of server side). Set it on browser side.
