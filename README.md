# IWSLT2024 - Dialectal and Low-resource speech translation track: North Levantine Arabic

Repository for sharing the audio and textual data in the North Leventine Arabic language (ISO-3 code: _apc_), one of the languages for the low-resource speech translation track at IWSLT 2024.


## Training data
Please see the [IWSLT website](https://iwslt.org/2024/low-resource).


## Validation data
We follow the same format as the previous shared task editions, see `data/valid/txt`. The audio files can be downloaded from [here](https://storage.ms.mff.cuni.cz/d/a9a75b8286af4ec28b1b/). When prompted for password, use  __lowercased name of this repository__, e.g., `github.com/xyz/Foo_Bar_1 -> foo_bar_1`.

In the `segments` file, we follow the `offset ||| duration` formulation, formating the timestamps in the `"%S.%03d"` format, i.e., seconds and miliseconds, see the `valid.yaml`.

## 2024 Test data
To be released soon.


## License
The data is property of the Institute of Formal and Applied Linguistics, Faculty of Mathematics and Physics, Charles University.

<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International  License</a>.


## Acknowledgements
This work was supported by the European Commission via its H2020 Program [WELCOME](https://welcome-h2020.eu/) (contract no. 870930).

