# docker-compose project setup

Ensure you have back-end and front-end projects cloned alongside this repository in a common parent directory, for example:
```
- example_directory
  |
  |- back-end
  |
  |- docker-compose
  |
  |- front-end
  |
  |- ...
```

Then, after entering the `docker-compose` directory using CLI, just run `docker-compose up` and wait until all required images are built.

The application should be available at [http://localhost:3000/](http://localhost:3000/).
