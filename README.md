# waldl

Browser [wallhaven](https://wallhaven.cc/) using `sxiv`

## Usage
```
waldl <query>
```
> Leave query empty to use `dmenu`

- Select wallpapers by marking them using `m` in `sxiv`.
- Quit `sxiv` using `q`.

Selected images would be downloaded. The default download directory is

	~/.local/share/wallhaven

Defaults can be changed by changing the user variables, in the of the script.


## Dependencies

* sxiv
* dmenu ( *optional* )
