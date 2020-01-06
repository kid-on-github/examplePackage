python -m venv env
env
python -m pip install ./package

import package
package.hello('x')

> Hello x!