# example-package-DamianAgi
Example repo on packaging and distribution. The source code is a simple rescaling function.

Based on the INTERSECT training material: https://docs.google.com/presentation/d/1w2V5Bp2l_ARCdeLeHAg6ACOQWcL3op10FXZ20rf5UGA/edit?slide=id.g3704a16c9f7_1_103#slide=id.g3704a16c9f7_1_103

# Example Package YOUR USERNAME HERE

`example-package-YOUR-USERNAME` is a simple Python library that contains a single function for rescaling arrays.

## Installation

Download the source code and use the package manager [pip](https://pip.pypa.io/en/stable/) to install `package`:

```bash
pip install .
```

## Usage

```python
import numpy as np
from example_package_YOUR_USERNAME_HERE.rescale import rescale

# rescales over 0 to 1
rescale(np.linspace(0, 100, 5))
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

TBD




