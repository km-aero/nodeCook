# node

Description

## what installs
- NodeJs
- Nginx
- npm
- pm2

## commands

### local tests

Unit test:
```
chef exec rspec
```

integration test:
```
kitchen test
```

### aws tests

run kitchen test on aws - KITCHEN_YAML=.kitchen9.yml kitchen test
