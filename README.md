📦 setup.py (for humans)
=======================

`setup.py` 文件在刚开始的时候总让人望而生畏，本项目提供了一个 `setup.py` 的最佳实践，让你可以通过复制粘贴快速创建自己的 `setup.py`。

最佳实践：

-  `$ python setup.py upload` 命令来创建  *universal wheel* (和 *sdist*) ，然后使用 [Twine] 把包上传到 [Pypi]，这样就不再需要烦人的 `setup.cfg` 文件。它还会自动创建/上传一个新的 git tag。
- 待补充...

To Do
-----

-   Tests via `$ setup.py test` (if it's concise).

欢迎 Pull requests ！

更多资源
--------------

-   [What is setup.py?] on Stack Overflow
-   [The Hitchhiker's Guide to Packaging]
-   [Cookiecutter template for a Python package]

License
-------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any means.

✨🍰✨

[an example setup.py]: https://github.com/kennethreitz/setup.py/blob/master/setup.py
[PyPi]: https://docs.python.org/3/distutils/packageindex.html
[Twine]: https://pypi.python.org/pypi/twine
[image]: https://farm1.staticflickr.com/628/33173824932_58add34581_k_d.jpg
[What is setup.py?]: https://stackoverflow.com/questions/1471994/what-is-setup-py
[The Hitchhiker's Guide to Packaging]: https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/creation.html
[Cookiecutter template for a Python package]: https://github.com/audreyr/cookiecutter-pypackage
