# Conda environments

---

`ffcv_torch_1_11` is compatible with `functorch==0.1`. To install the env, together with `functorch` and `ffcv`, do
```
conda create --name <env> --file ffcv_torch_1_11 python=3.9
conda activate <env>
pip install ffcv ipdb scipy
pip install functorch==0.1 --no-deps
```

---

`ffcv_torch_13` has `torch=1.13` which comes with `functorch` built in. To
install it, together with `ffcv`, do
```
conda create --name <env> --file ffcv_torch_13
conda activate <env>
pip install ffcv ipdb
```
