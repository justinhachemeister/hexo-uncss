# uncss plugin for [Hexo](https://hexo.io)
> Remove unused styles from CSS with [uncss](https://github.com/giakki/uncss).

## Install
```bash
$ npm install hexo-uncss --save
```

## Options
You can configure this plugin in `_config.yml`.

```yaml
uncss:
  enable   : true
  ignore   : "#added_at_runtime"
  media    : (min-width: 700px) handheld and (orientation: landscape)
  priority : 10
  timeout  : 1000
  uncssrc  : .uncssrc
```

- **enable** - Enable the plugin. Defaults to `true`.
- **priority** - Set the filter priority. Lower priorities execute first. Defaults to `10`.
- All other options correspond to their [uncss](https://github.com/giakki/uncss#usage) equivalent.

## Debugging
Launch the node process like `DEBUG=hexo:uncss hexo ...` to inspect debug messages.

## Changelog
See the [Changelog](./CHANGELOG.md) for a list of changes.

## License
    The MIT License (MIT)

    Copyright (c) 2016 Mark van Seventer

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.