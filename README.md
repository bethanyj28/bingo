# bingo
A bingo board generator

## Quickstart

1. Clone repo onto machine
2. Build the image by running `docker build -t bingo .` in the `api` directory of `bingo`
3. In the same `api` directory, run `docker run -p 5000:5000 bingo`, now you can access the API at http://localhost:5000
   * Note: if port 5000 is already in use on your machine, map to a different port. i.e. `docker run -p 5001:5000 bingo`
