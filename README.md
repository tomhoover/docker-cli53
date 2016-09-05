# docker-cli53
Docker container for [cli53](https://github.com/barnybug/cli53) (command line tool for Amazon Route 53).

## Usage
```bash
$ docker run --rm \
  -e AWS_ACCESS_KEY_ID="your aws access key" \
  -e AWS_SECRET_ACCESS_KEY="your aws secret key" \
  tomhoover/docker-cli53 list
```