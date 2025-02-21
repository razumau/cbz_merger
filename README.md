# cbz_merger

Merges multiple CBZ/CBR files into one, so that 
```
comic/
├── 01.cbz
├── 02.cbz
└── 03.cbz
```

becomes

```
comic/
├── 01.cbz
├── 02.cbz
├── 03.cbz
└── result.cbz
```

## Installation and usage
Run it with uvx:

```
uvx cbz_merger [-r result_filename] folder_name
```

Or install with pip/pipx:

```
pipx install cbz_merger
```
