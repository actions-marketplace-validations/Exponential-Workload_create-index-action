# [![create-index-action](https://exponential-workload.github.io/create-index-action/banner.png)](https://github.com/marketplace/actions/create-indexes)

Action for [create-autoindex](https://npm.im/create-autoindex) & [@3xpo/create-index](https://npm.im/@3xpo/create-index) using [create-index-bin](https://github.com/Exponential-Workload/create-index-bin/tree/master).

## Usage

```yml
      - name: Create Indexes
        uses: Exponential-Workload/create-index-action@0.1.0
        with:
          dir: '.' # optional - directory to create indexes in
          # path: <some path> # optional, discouraged - path to write executable
          # source: https://<some url> # optional, discouraged - source url of executable
```
