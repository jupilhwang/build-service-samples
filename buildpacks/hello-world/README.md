# Sample: Hello World Buildpack

A no-op buildpack whose intent is to show minimal requirements of a buildpack.

### Usage

```bash
pack build sample-hello-world-app --builder cnbs/sample-builder:alpine --buildpack .
```

OR

```bash
pack build sample-hello-world-app --builder cnbs/sample-builder:bionic --buildpack .
```

THEN

```
docker run sagmple-hello-world-app echo hello
```
