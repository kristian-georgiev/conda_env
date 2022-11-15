# Conda environments

---

`ffcv_torch_1_11` is compatible with `functorch`. To install `functorch` and `ffcv` on it (together with some additional common libraries not on conda), after installation do
```
conda create --name <name> --file ffcv_torch_1_11.txt python=3.9
pip install ffcv fastargs tqdm ipdb scipy urllib3
pip install functorch==0.1 --no-deps
```

---
