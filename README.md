# IWSLT2024 - Dialectal and Low-resource speech translation track: North Levantine Arabic

Repository for sharing the audio and textual data in the North Leventine Arabic language (ISO-3 code: _apc_), one of the languages for the low-resource speech translation track at IWSLT 2024.


## Training data
Please see the [IWSLT website](https://iwslt.org/2024/low-resource).


## Validation data

~~[**17.02.2024**] We fixed the incorrect timestamps for two dialogues: __Tar_13052022_Food__ and __Tar_13052022_Czechia__. Both `segments` and `valid.yaml` files were effected, `valid.{apc,eng}` have not changed.~~

~~We follow the same format as the previous shared task editions, see `data/valid/txt`. The audio files can be downloaded from [here](https://storage.ms.mff.cuni.cz/d/a9a75b8286af4ec28b1b/). When prompted for password, use  __lowercased name of this repository__, e.g., `github.com/xyz/Foo_Bar_1 -> foo_bar_1`.~~

The data corresponding to the IWSLT 2024 validation split is available [here](http://hdl.handle.net/11234/1-5518).

In the `segments` file, we follow the `offset ||| duration` formulation, formating the timestamps in the `"%S.%03d"` format, i.e., seconds and miliseconds, see the `valid.yaml`.

## 2024 Test data
~~[01.04.2024] We have released the segments file corresponding to 2024 test data, see `data/test2024/txt`. The audio files can be now downloaded from [the same source](https://storage.ms.mff.cuni.cz/d/a9a75b8286af4ec28b1b/) as validation data, using the same password.~~

The data corresponding to the IWSLT 2024 test split is available [here](http://hdl.handle.net/11234/1-5519).

## 2025 Test data
~~[07.04.2025] We have released the segments file corresponding to 2025 test data, see `data/test2025/txt`. The audio files can be now downloaded [here](https://storage.ms.mff.cuni.cz/f/20b053e0895940a0b58f/). When prompted for password, use  __lowercased name of this repository__, e.g., `github.com/xyz/Foo_Bar_1 -> foo_bar_1`.~~

~~[18.04.2025] If you are unable to download the audio data from the link above, please use [this](https://mega.nz/#P!AgH1kFVErhHRiLXe1VOUrdPtry58GpUeoTOV6R8XMZnTePMg2FchZO5CdjjxJWWSknQnFgXwyYw0HDtxDs-NeCdoJtfOLHMRQ_1Wzn0SYC_JEbUWpCg9ixscTe_jTL_Ff4gcyDeXBcw) one. The password is the same, i.e __lowercased name of this repository__, e.g., `github.com/xyz/Foo_Bar_1 -> foo_bar_1`.~~

The data corresponding to the IWSLT 2025 test split is available [here](http://hdl.handle.net/11234/1-5924).

## License
The data is property of the Institute of Formal and Applied Linguistics, Faculty of Mathematics and Physics, Charles University.

<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International  License</a>.


## Acknowledgements
This work was supported by the European Commission via its H2020 Program [WELCOME](https://welcome-h2020.eu/) (contract no. 870930).

