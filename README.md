Running `bazel build //...` fails with an error while running the following does not:

```
cd B
python3 -m venv .venv
. .venv/bin/activate
pip3 install -r child-requirements.txt
```
