# 📦 setup.py

setup.py 是分发 Python 模块的标准，运行它可以打包应用并将其上传到 [Pypi] 或你自己的服务器。

但是在新开始一个 Python 项目的时候 `setup.py` 文件总让人望而生畏，因此本项目希望能够提供一些 `setup.py` 的先进模式和最佳实践，通过注释和模板来引导你快速开始一个项目。

一些最佳实践：

- 使用 `$ python setup.py upload` 命令创建 _universal wheel_ (和 _sdist_) ，然后通过 [Twine] 把包上传到 [Pypi]，这样就不再需要烦人的 `setup.cfg` 文件了。另外，它还会自动创建/上传一个新的 git tag。

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any means.

✨🍰✨

[pypi]: https://docs.python.org/3/distutils/packageindex.html

[twine]: https://pypi.python.org/pypi/twine