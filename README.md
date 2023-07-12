# lingua-franca-hello-world

play around with lingua franca

## Install

```bash
git submodule update --init lingua-franca
cd lingua-franca
./gradlew assemble
export PATH="$PATH:$PWD/bin"
```

## c examples

```bash
lfc hello_world_cc.lf
./bin/hello_world_cc
```

## python examples

```bash
lfc hello_world_python.lf
python3 src-gen/hello_world_python/hello_world_python.py
```