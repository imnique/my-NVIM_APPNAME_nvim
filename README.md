# `NVIM_APPNAME`

> Read for details
[https://michaeluloth.com/neovim-switch-configs/](https://michaeluloth.com/neovim-switch-configs/)

- each branch `<nvim-config>/main` is represented git history of config for some nvim version
- the near default way is to clone this repo into `.config/<nvim-config>` folder and switch to `<nvim-config>` branch
> _so it's ok to clone this repo many times (up to you handle unused branches or introduce more elegant solution)_
- so to run for example `lazyvim` (which you should store in `.config/nvim-lazyvim`) you should:
  ```bash
    NVIM_APPNAME=nvim-lazyvim nvim
  ```

---

