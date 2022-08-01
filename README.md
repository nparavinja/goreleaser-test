# goreleaser-test

# check gorealeaser.yaml config
goreleaser check

# local build
goreleaser release --snapshot --rm-dist

# pushing to git
export token ..
git tag -a v1.0.0 -m "Release message"
git push master v1.0.0

